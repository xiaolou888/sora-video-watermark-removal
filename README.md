# sora2-video-watermark-removal
sora2视频秒去水印源码
- sora2很强大，但是有水印很不方便，我找到了一个去sora2水印的接口，分享给大家

### 解析接口
解析接口地址：
```bash
https://api.dyysy.com/links1115/{视频地址}
```
响应示例：
```bash
{
  "post_id": "s_691a02ebf3108191a0378a6cf87abd0a",
  "original_input": "115/https:/sora.chatgpt.com/p/s_691a02ebf3108191a0378a6cf87abd0a",
  "links": {
    "gif": "https://oscdn1.dyysy.com/GIF/s_691a02ebf3108191a0378a6cf87abd0a.gif",
    "mp4_wm": "https://oscdn2.dyysy.com/MP4/s_691a02ebf3108191a0378a6cf87abd0a.mp4",
    "thumbnail": "https://oscdn1.dyysy.com/THUMBNAIL/s_691a02ebf3108191a0378a6cf87abd0a.webp",
    "md": "https://oscdn1.dyysy.com/MD/s_691a02ebf3108191a0378a6cf87abd0a.mp4",
    "mp4": "https://oscdn2.dyysy.com/MP4/s_691a02ebf3108191a0378a6cf87abd0a.mp4"
  },
  "post_info": {
    "view_count": 241554,
    "like_count": 4686,
    "title": "Red Bull gave her wings… and she never came back 😭🪽",
    "prompt": null,
    "attachments_count": 1
  }
}
```
- 这个是公共接口
- 前端大家自己去找代码搞一个就行
- 感谢[大洋芋去水印](https://api.dyysy.com/links1115/)提供的公共接口，如果有商业行为，我还是建议大家去购买

### 去水印源码
- 我也找了几个去水印的源码，都是网上的，我放在这里，需要的自己拿
- [橘猫去水印小程序](https://github.com/xiaolou888/jumao)
- [陆大湿去水印小程序](https://github.com/xiaolou888/ludashi)
- [简易单网页sora去水印](https://github.com/xiaolou888/qushuiyin-jianyi)
### 下载sora原地址无水印视频接口
- 如果需要下载原地址视频，可以使用https://api.yuantoai.com 他家的接口
- 登录后在接口查询页面可以找到接口地址，复制下来
- 最主要的是这个接口可以下载官方原地址视频，是的，***<span style="color:red">官方原地址视频</span>***
- 只需要把解析出来的地址域名换成官方的域名就是原地址了
![图片/api.png](https://github.com/xiaolou888/qushuiyin-jianyi/blob/main/图片/api.png)
![图片/3.png](https://github.com/xiaolou888/qushuiyin-jianyi/blob/main/%E5%9B%BE%E7%89%87/3.png)
