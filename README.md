# MyUnityFrameWork
我的Unity框架，包含资源加载，配置加载，数据加载，UI管理，音频管理,日志管理，动画系统，特效系统
##应用
　1.快速配置开发模式和发布模式  
  　2.支持快速定位到某一个游戏流程（某游戏场景，结算界面等），方便测试  
  　3.游戏逻辑入口从某一个游戏流程开始  
  　(创建一个流程继承IGameStatus,例如MainMenuStatus,然后再ApplicationManager中选择它作为第一个流程)

##资源加载
　　1.可视化依赖包管理工具，打包进度可视，不再干等着了  
　　2.Resource和AssetsBundle两种加载模式，简单切换开发与发布状态  
　　3.统一加载接口，上层逻辑无需关心使用哪种方式加载资源  
　　4.多种资源管理机制，读取效率与内存占用的平衡（未完成）  
　　
##配置加载
　　1.配置不会被热更新请注意，但是可以被同步（同步代码暂未实现）  
　　2.一行代码读取和保存配置，方便快捷  
　　3.可将类序列化保存到配置中，快速使用  
　　4.配置可读可写
　　
##数据加载
　　1.数据是可以热更新的  
　　2.数据可使用默认值，可以让程序不用等策划，并且修改默认值非常方便  
　　3.数据键值对方便拓展， 策划不用等程序  
　　4.数据在运行时只读  
　　
##UI系统
　　1.方便快捷的多语言管理方案  
　　2.方便快捷的风格管理方案，一套风格，多处公用，一次修改(未完成)    
　　3.粒子系统和UI完美嵌套    
　　4.支持3DUI和2DUI  (未完成)  
　　5.支持浮动UI（血条，昵称等）  
　　6.方便好用的事件系统    
　　7.UI编辑工具(未完成)   
　　
##音频管理
　　1.总音量，音乐音量，音效音量控制  
　　2.一行代码播放各种音乐音效  
　　3.支持2D/3D音乐音效  
　　
##开发者工具
　　1.收集关键日志和崩溃日志，发送给开发者(日志在 persistent路径\.Log文件夹下)  
　　2.同时按下四根手指呼出游戏内控制台,监控帧率与内存使用量  
　　3.感谢Q框架提供技术借鉴(https://github.com/liangxiegame/QFramework) 
　　
##动画系统
　　1.支持UGUI动画，使用定位更精确  
　　2.支持多种动画方式，贝塞尔曲线，各种回弹   
　　3.参照Itween，一行代码播放各种动画  
　　4,更加方便的动画播放完毕回调
　　5,支持多种重复模式YoYo,reset等（未完成）
　　
##特效系统
　　1.提供各种预设特效，开发简单快捷 (未完成)