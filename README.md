# Touchbar_Lyric_Netease

Touchbar显示网易云音乐歌词

需要配合软件使用 用以返回网易云播放状态
https://github.com/Timidvb/NeteaseControl

基于BTT论坛分享项目修改
https://github.com/ChenghaoMou/touchbar-lyric

使用方法：
1、安装pip3

2、下载项目并放到相应的路径

3、终端cd到项目内，安装

    pip install --editable .
  
4、把lyric.json导入BTT

5、修改脚本中的内容

    ${PYTHONPATH} -m touchbar_lyric --proxy ${PROXY} --logpath ${LOGPATH}
    
PYTHONPATH：PYTHON路径可以通过

    whereis python3
    
PROXY：开启解锁网易云服务则需要代理绕开解锁代理

    socks5://x.x.x.x:xxxx / http://x.x.x.x:xxxx
    
LOGPATH：网易云音乐log地址

    Users/yourname/Library/Containers/com.netease.163music/Data/Documents/storage/Logs/music.163.log
