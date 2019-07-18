# AppDistribution

APP下载资源静态部署资源，可将index.html访问链接作为android/ios统一下载二维码地址，支持扫码自动安装APP。

# 说明

1. 示例代码全部部署在qcloud cos存储桶中，访问地址：https://devdata-1252923336.cos-website.ap-guangzhou.myqcloud.com/
2. 如果IOS的ipa为企业版发布，也可部署企业自建服务器，注意manifest.plist必须为https地址，否则无法安装成功
3. 如果IOS的ipa为itunes apple store应用，url修改为itunes地址即可
