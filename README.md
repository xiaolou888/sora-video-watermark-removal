# sora2-video-watermark-removal
sora2视频秒去水印源码
- sora2很强大，但是有水印很不方便，我找到了一个去sora2水印的接口，分享给大家

### 解析接口
解析接口地址：
```bash
https://api.dyysy.com/links/{视频地址}
```
响应示例：
```bash
{
  "original_input": "https:/sora.chatgpt.com/p/s_68df3f261e6081919c0e1ceffc14c8b9",
  "links": {
    "mp4_wm": "https://oscdn.dyysy.com/wm/s_68df3f261e6081919c0e1ceffc14c8b9.mp4",
    "gif": "https://oscdn.dyysy.com/GIF/s_68df3f261e6081919c0e1ceffc14c8b9.gif",
    "md": "https://oscdn.dyysy.com/MD/s_68df3f261e6081919c0e1ceffc14c8b9.mp4",
    "thumbnail": "https://oscdn.dyysy.com/THUMBNAIL/s_68df3f261e6081919c0e1ceffc14c8b9.webp",
    "mp4": "https://oscdn.dyysy.com/MP4/s_68df3f261e6081919c0e1ceffc14c8b9.mp4"
  },
  "post_id": "s_68df3f261e6081919c0e1ceffc14c8b9",
  "post_info": {
    "prompt": null,
    "view_count": 21,
    "like_count": 0,
    "attachments_count": 1,
    "title": "@sama 来到中国白沟，白沟河道国际箱包交易城，并称赞这里，走进男包店和店主沟通，并且拿起一个包背在身上，然后称赞这个包包，全程中文交流"
  }
}
```
- 目前是免费的，大家且用且珍惜
- 前端大家自己去找代码搞一个就行
- 感谢[大洋芋去水印](https://api.dyysy.com/links/)提供的接口
- 如果需要下载原地址视频，可以使用https://open.api.yuantoai.com 他家的接口
### 去水印源码
- 我也找了几个去水印的源码，都是网上的，我放在这里，需要的自己拿
- [橘猫去水印小程序](https://github.com/xiaolou888/jumao)
- [陆大湿去水印小程序](https://github.com/xiaolou888/ludashi)
- [简易单网页sora去水印](https://github.com/xiaolou888/qushuiyin-jianyi)
