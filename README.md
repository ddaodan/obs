# obs
## 使用方法：
https://ddaodan.github.io/obs/ytb_wrapper.html?id=channel_id  
将后面的`channel_id`修改为对应的频道id
## 获取频道id
假设我们现在要获取的频道是https://www.youtube.com/@kumagayatakuma  
进入频道，按下F12打开开发者工具  
切换到网络(Network)选项卡  
按Ctrl+R刷新页面，点击第一个，一般是以频道名命名的  
切换到响应(Response)选项卡  
按Ctrl+F搜索`content="UC`  
会搜索到 content="UCCXME7oZmXB2VFHJbz5496A"  
引号里的就是频道id

如果没找到，可以用这个网站来找：  
https://commentpicker.com/youtube-channel-id.php