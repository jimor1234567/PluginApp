# PluginApp
插件化技术实现App模块化隔离--实践

正常app模块结构：

- root gradle
	- app
	- librarya
	- libraryb

插件化后的结构

- app
	- assets	
		- plugina->librarya  
		- pluginb->libraryb
- plugina-wrap 
	- librarya
	
- pluginb-wrap
	- libraryb

参考下图：
<img src="./pic/app_module.png" width="640" />