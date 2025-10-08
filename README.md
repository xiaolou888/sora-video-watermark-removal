# sora2-video-watermark-removal
sora2视频秒去水印源码
- soar2很强大，但是有水印很不方便，我找到了一个去sora2水印的接口，分享给大家

### 解析接口
解析接口地址：
```bash
https://sora.codeai.my/links/{视频地址}
```
响应示例：
```bash
{
  "post_id": "s_68df3f261e6081919c0e1ceffc14c8b9",
  "links": {
    "mp4_wm": "https://soapi.codeai.my/wm/s_68df3f261e6081919c0e1ceffc14c8b9.mp4",
    "gif": "https://sora.codeai.my/GIF/s_68df3f261e6081919c0e1ceffc14c8b9.gif",
    "api": "https://sora.codeai.my/api/s_68df3f261e6081919c0e1ceffc14c8b9",
    "thumbnail": "https://sora.codeai.my/THUMBNAIL/s_68df3f261e6081919c0e1ceffc14c8b9.webp",
    "mp4": "https://sora.codeai.my/MP4/s_68df3f261e6081919c0e1ceffc14c8b9.mp4",
    "md": "https://sora.codeai.my/MD/s_68df3f261e6081919c0e1ceffc14c8b9.mp4"
  },
  "original_input": "https://sora.chatgpt.com/p/s_68df3f261e6081919c0e1ceffc14c8b9",
  "post_info": {
    "title": "@sama 来到中国白沟，白沟河道国际箱包交易城，并称赞这里，走进男包店和店主沟通，并且拿起一个包背在身上，然后称赞这个包包，全程中文交流",
    "attachments_count": 1,
    "view_count": 20,
    "like_count": 0
  }
}
```
- 目前是免费的，大家且用且珍惜
- 前端大家自己去找代码搞一个就行
- 感谢https://sora.codeai.my 提供的接口
