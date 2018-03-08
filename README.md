# 幻想领域

哇塞，终于有一款属于自己的图床了.

幻想领域是使用 PHP 语言开发的一款轻量级的新浪图床系统.

它的诞生，并不是最终的解决方案，开发它的目的是为了方便自己使用.



# 系统介绍

在 幻想领域中, 图床图片全部托管在 新浪云, 每张图片都有多张不同级别的缩略图.这便是幻想领域的最大特色之一.

拥有较为完善的用户系统与管理员系统。管理员在后台拥有完全权限，对网站的一切基本配置

我的图库，将会罗列出用户自己所上传的所有图片，管理员则显示系统托管的所有图片.你可以在这里对图片进行删除、预览或者复制它，但删除仅仅只是不再出现在本系统中，图片仍然是存在于新浪之上，这点你是要知道的.

探索，它是前台对用户图片预览的功能，在这里你可以发现和找到你需要的东西.如果你不需要它，可以在后台进行关闭设置.

上传新浪图床并非无要求，它需要你进行登录验证，但我们拥有一套独立的新浪登录程序，不依赖任何扩展，并且无验证码，cookie过期将自动为你进行登录，为你解决一切后顾之忧，所以你必须在后台设置你的新浪账号密码才能正常使用.


# 安装

你需要将幻想领域的源代码解压缩并上传至网站根目录，访问网站域名会自动跳转到安装程序，根据向导提示安装即可。如果未跳转，请手动访问http://您的域名/install.php 进行安装

首次安装成功后需要登录管理员后台对图床进行一些基本配置，才能使用

后台地址：http://您的域名/admin  但是讽刺的是，您需要在前台进行登录


## 环境支持

> 请注意，幻想领域自1.0版本起只支持PHP版本≥5.6，请注意更新您的PHP版本。
