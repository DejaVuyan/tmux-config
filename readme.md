## 安装使用

```
git clone https://github.com/DejaVuyan/tmux-config.git
./tmux-config/install.sh
```

vim如果和tmux有配色冲突解决配色问题
在.bashrc中加上


`alias tmux="TERM=screen-256color tmux"`


## 快捷键
d 退出tmux  
w 呼出窗口  
方向键 选择窗口  
c 新建一个window  
X 杀掉一个window  
r 重命名  

#### pane操作
\ 左右分屏(其实是|，很形象的一个词但是按shift太麻烦了)  
`-` 左右分屏  
z 最大化pane  
s 交换当前pane和下一个pane  
h 切换到左边的pane  
l 切换到右边的pane  
j 切换到下边的pane  
k 切换到上边的pane  
x 杀掉一个pane  

## copy mode
按下`pageUp`或者`pageDown`进入copy mode后，使用空格开始选取文字，`y`复制,`p` 粘贴
`perfix`+`ctrl+p`打开粘贴板
