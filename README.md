# creator to quick

Creator plugin to support Lua in Quick-Cocos2dx-Community.

采用 https://github.com/cocos2d/creator_to_cocos2dx 提供的方案。
选择转出的json为基础，纯lua端做解析，如果需要副以引擎的部份cpp支持。
不选择flatbuffers是因为它与显存的cocosStudio 的 flatbuffers 版本冲突，另考虑部分控件会在lua端扩张，在lua端解析加载界面更灵活。

## 导出用法

1. creator-luacpp-support 拷贝到Creator工程的 packages 目录下。
2. 打开 creator project。
3. 点击click Project -> LuaCPP Support -> Setup Target Project，填入导出路径（初次设置，之后就不用了），
4. 点击 Project -> LuaCPP Support -> Build。

导出的 ExprotRootDir/Resources/creator 为资源文件，拷贝到 Quick 项目的 res目录下待用。

## 加载 TBD