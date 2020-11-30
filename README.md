# watermask
支持小红书、抖音、快手、微博、火山视频、西瓜视频、YouTube、哔哩哔哩、Tiktok、微视、全民小视频、淘宝、天猫、1688、拼多多、唯品会、一淘等各大电商平台及短视频平台的视频去水印和图片去水印功能

# 关于接口：
- 接口采用RESTful API方式提供，不限制开发语言，Java、python、node.js都可便捷接入；
- 接口支持GET和POST两种请求方式；
- 接口不限制IP和cookie”

# 视频/图集去水印解析接口
URL：https://andoly.cn/api/parse.do
请求方式：GET/POST
请求参数：
appkey  请联系作者获取
url 各大短视频平台的分享链接
返回结果：
```
{
	"code": 0,
	"msg": "success",
	"body": {
		"url": "http://xhslink.com/NrFWV",
		"platform": "xiaohongshu",
		"text": "留学生回国无社交北京 听说最近很流行这个英国—北京有木有小伙伴呀",
		"images": ["http://sns-img-qc.xhscdn.com/a2ecc0fb-c6e7-3759-b499-f57d83404bf4?imageView2/2/w/1080/format.jpg", "http://sns-img-qc.xhscdn.com/2382fb3b-6e94-34f5-b2da-0807b7f1e35c?imageView2/2/w/1080/format.jpg", "http://sns-img-qc.xhscdn.com/4b34fe46-b118-352c-93f9-36a17d81338a?imageView2/2/w/1080/format.jpg", "http://sns-img-qc.xhscdn.com/607c9470-96f0-328c-a4d9-4b93eeb1093b?imageView2/2/w/1080/format.jpg"],
		"video_info": [],
		"type": 1,
		"cover": "http://sns-img-qc.xhscdn.com/a2ecc0fb-c6e7-3759-b499-f57d83404bf4?imageView2/2/w/1080/format.jpg"
	}
}
```
# 作者联系方式
- 微信：378229185 
- QQ：同微信
