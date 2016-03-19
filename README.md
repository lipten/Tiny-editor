# Tiny-editor
Demo:http://lipten.link/demo/editor

###-update v0.1-
1.测试版，目前有个别功能不稳定。

-----
###Usage

####1、下载slidePage
```
git clone https://github.com/lipten/Tiny-editor.git
```


####2、引用相关文件
```
<link rel="stylesheet" href="Tiny-editor.css"/>
```

####3、引用js文件
```
<script src="http://cdn.bootcss.com/ace/1.2.3/ace.js" type="text/javascript" charset="utf-8"></script>
<script type="text/javascript" src="Tiny-editor.js"></script>

```

####4、html结构
```
//--html结构比较复杂，看下载后的editor.html比较完整
```


####5、初始化代码
```
var Tiny = new TinyEditor()
```

-------

##Method

####Tiny.tab(num)
tab显示第几个面板，num传序号，从1开始

####Tiny.run()
运行结果并跳到result面板

####Tiny.save()
保存代码至缓存

####Tiny.fullScreen()
全屏模式开启或关闭

####Tiny.dockMode()
dock边栏模式开启或关闭

####Tiny.liveMode()
实时运行模式，发生change事件时执行一次，仅开启dock模式的前提下才能开启

