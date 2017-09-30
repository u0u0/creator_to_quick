# creator_to_quick
 Creator plugin to support Lua in Quick-Cocos2dx-Community

采用 https://github.com/cocos2d/creator_to_cocos2dx 提供的方案。
选择转出的json为基础，纯lua端做解析，如果需要副以引擎的部份cpp支持。
不选择flatbuffers是因为它与显存的cocosStudio 的 flatbuffers 版本冲突，另考虑部分控件会在lua端扩张，在lua端解析加载界面更灵活。
