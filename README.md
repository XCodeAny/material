## Material
一款基于Google Material Design的Material Typecho主题
A Material Typecho Theme based on Google Material Design
>Refer to Google  Material-Design-Lite

## 基本特性
- [主题 Demo](https://blog.viosey.com)
- 侧边栏含有有关博客的详细信息以及相关操作
- 极其丰富的自定义设置
- 自带中英文界面语言
- 自带多种功能与特效
- Material Design 交流 / bug 反馈群：566308505


## 使用方法
- [Github 地址](https://github.com/viosey/typecho-theme-material), 点击"Download ZIP"下载, 解压后将文件夹改名为 "Material"(或其他) 后上传到```/usr/themes```, 并启用主题
- 在 "设置外观" 中打造一个属于你自己的博客
- 关于文章缩略图
	- 文章缩略图为文章内第一张图片
	- 缩略图支持 Markdown 格式, HTML 格式以及附件形式, Markdown 格式为 ```![图片描述](图片链接)```
	- 如果想要自定义某篇文章的缩略图, 但是不想让该图片在文章中出现, 则可以使用该格式 ```<img src="图片链接" width="0px" /> ```
- 首页文章概览默认最大输出80个字符, 可手动添加截断符```<!-- more -->```控制输出
- 由于 Gravatar 被墙, 解决方案是将 ```var/Typecho/Common.php``` 中的第 939 行中的 ```http://www.gravatar.com``` 中的 ```www.``` 去掉即可, 或者使用主题设置外观中的自定义头像功能.
- 在侧边栏中使用友情链接, 需安装此友情链接插件  [typecho-links-material](https://github.com/viosey/typecho-links-material)
- 安装使用 [浏览次数统计插件](http://qiniu.viosey.com/typecho/plugins/Stat.zip) 后, 首页文章信息与文章页分享按钮下拉选项中会显示浏览次数统计
- 点赞功能需使用该 [点赞插件](http://7xqdyf.com1.z0.glb.clouddn.com/zipTeStat.zip)

## 预览
![](https://viosey.com/img/screenshot.jpg)

![](https://viosey.com/img/verticalpageview.jpg)

## License
Open sourced under the GPL v3.0 license.
