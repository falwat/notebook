#NoteBook for Linux

## Best applications

-  ** franz ** ： messenger services
-   ** WPS for Linux** ： Office
-   ** 有道词典** 
-   ** chrome** 
-   ** spyder** ≈ Matlab
-   ** Inkscape** ≈ visio
-   ** yEd Graph Editor** ≈ visio
-   ** Eclipse** - WebDevelopment
-   ** LightTable**
-   ** Code::Blocks**
-   ** uget** - download manager
-   ** Gufw** - firewall for Linux
-   ** Atraci** - search and stream music directly from YouTube
-   ** Tomahawk**
-   ** Kodi** - media center software
-   ** graphviz **
- ** Beyond Compare ** : 文件比较工具
- ** freeFileSync ** 文件同步工具
- ** Kazam ** : 录屏&截屏软件

## Usefull package on apt
build-essential
website for learning Linux
--------------------------

30 Best Linux Apps And software <http://beebom.com/best-linux-apps/>

## 常见问题 

### 安装Qt 
-----
### graphviz
- 安装graphviz
``` 
apt install graphviz graphviz-dev graphviz-doc
```
- 新建graph1.gv 文件
```
digraph G {
    main -> parse -> execute;
    main -> init;
    main -> cleanup;
    execute -> make_string;
    execute -> printf
    init -> make_string;
    main -> printf;
    execute -> compare;
 }
```
- 使用dot 绘图
```
dot -Tps graph1.gv -o graph1.ps
```
![](/home/wlong/graph1.ps) 
