## 使用项目文件夹

无论何时使用 3ds Max 操作，都要了解我们操作的项目，并将所有的资源都保存在这个项目中。这样，如果我们将项目移动到不同的文件夹或者不同的电脑中，或者需要保存这个数据，都在一个中心地址中。另外，这些文件之间的链接跟项目文件都有关联，只要操作正确，链接或者纹理损坏的可能性更小。

如何创建项目文件夹。

启动 3ds Max，通过“自定义”菜单 > “配置用户路径”设置项目文件夹路径，也可以通过“应用程序”菜单 > “管理” > “设置项目文件夹”设置。

设置项目文件夹时，3ds Max 会自动在其中创建一系列文件夹，下面是文件夹的目录结构：

```
│  3Ds MAX.mxp  # 当 3ds Max 识别项目文件夹里有这个文件时，会默认这个文件夹就是项目的根目录
│
├─archives
├─autoback
│      MaxBack.bak
│
├─downloads
├─export
├─express
├─import
├─materiallibraries
├─previews
├─proxies
├─renderoutput
├─renderpresets
├─sceneassets
│  ├─animations
│  ├─images
│  ├─photometric
│  ├─renderassets
│  └─sounds
├─scenes  # 场景 .mxd 文件存放的地方
└─vpost
```
当我们开始操作项目时，要先指定项目文件夹，这样，当保存或打开文件时，就会默认使用此项目文件夹。
