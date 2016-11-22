# NoteBook for vim 

## 快捷键
- ** 撤销&重做**
```
正常模式下：
- [u] : 撤销
- [clt+r] ： 重做
```
- ** 查看快捷键映射 ** 
参考：[Mapping keys in Vim - Tutorial (Part 1)](http://vim.wikia.com/wiki/Mapping_keys_in_Vim_-_Tutorial_(Part_1)) 
``` 
 # 显示已有的键映设，“：”可有可无
:map  # 常规模式下的...
:map! # 插入模式下的...
:help map-which-keys
:map-alt-keys|
```
## 安装插件
参考：[README on GitHub](https://github.com/tpope/vim-pathogen) 

- 首先安装vim插件管理器：pathogen
```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
- 在 ～/.vimrc 中添加：
``` 
execute pathogen#infect() 
```
- 将需要安装的插件解压到 ~/.vim/bundle

## 实用Vim插件
1. [taglist](https://github.com/vim-scripts/taglist.vim) 标签列表
2. [nerdtree](https://github.com/scrooloose/nerdtree)  文件系统浏览
3. [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)  自动补全
4. [tagbar](https://github.com/majutsushi/tagbar)
