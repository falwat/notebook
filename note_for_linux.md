# NoteBook for Linux

download this file from [github](https://github.com/falwat/notebook)

## Best applications

- ** franz ** ： messenger services
- ** wps-office** ： WPS Office for Linux
- ** youdao-dict** : 有道词典 
- ** chrome** : google 浏览器
- ** spyder** ≈ Matlab
- ** Inkscape** ≈ visio
- ** yEd Graph Editor** ≈ visio
- ** Eclipse** - WebDevelopment
- ** LightTable**
- ** Code::Blocks**
- ** uget** - download manager
- ** Gufw** - firewall for Linux
- ** Atraci** - search and stream music directly from YouTube
- ** Tomahawk**
- ** Kodi** - media center software
- ** graphviz **
- ** Beyond Compare ** : 文件比较工具
- ** freeFileSync ** 文件同步工具
- ** Kazam ** : 录屏&截屏软件
- ** GParted** : 磁盘分区工具
- ** AcetoneISO ** : 光盘镜像工具，CD/DVD烧写、虚拟光驱
--------------------------
website for learning Linux
30 Best Linux Apps And software <http://beebom.com/best-linux-apps/>


## Usefull package on apt
build-essential

## 常用命令
- ** man ** 查看在线命令参考手册
```
man <cmd>
man man
```
```
touch
```

## git 教程
- 常用命令
-- add
-- clone
-- commit
-- push

## 从youtube 下载视频
- ### 安装 Video Downloader
使用 curl
```
sudo curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl
sudo chmod a+rx /usr/local/bin/youtube-dl
```
或者 使用 wget
``` 
sudo wget https://yt-dl.org/downloads/latest/youtube-dl -O /usr/local/bin/youtube-dl
sudo chmod a+rx /usr/local/bin/youtube-dl 
``` 
或者 使用 pip
``` 
sudo pip install --upgrade youtube_dl
``` 
- 将URL替换为所需下载的视频地址，视频将会下载到用户的根目录
``` bash
youtube-dl --proxy socks5://127.0.0.1:1080/  URL
``` 

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
