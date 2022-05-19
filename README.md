原开源库：[https://github.com/sunfusheng/GlideImageView](https://github.com/sunfusheng/GlideImageView)

开源库博客：[https://www.jianshu.com/p/ba58ef561447](https://www.jianshu.com/p/ba58ef561447)

当前开源库的问题：



- [ ]  加载动画默认显示，需要配置成可显示和显示
- [ ] 缺少了GlideException类
- [ ] 需要支持非imageview需要加载图片
- [ ] 缓存管理不合适，缺少默认缓存路径管理
- [ ] 增加去除触摸图片有灰色阴影的效果、
- [ ] 解决控件的点击事件需有ScrollView作为容器时才能触发，不然触发不了点击事件的问题
- [ ] 优化控件的点击事件存在触发不了的情况，就是点击灵敏度与正常的ImageVew控件有很大的差距的问题
- [ ] 修复添加过度动画后transition(DrawableTransitionOptions.withCrossFade())，图片加载不会显示,使用Imageview过渡动画就没问题的问题
- [ ] 修复项目中依赖该库和官方Glide 库冲突的问题
- [ ] 增加计算gift播放时间的功能
- [ ] 增加项目注释
- [ ] 增加加载本地相册进度条的功能



改良版本开源库的地址：GlideProgressImageView



## 项目技术点

- 技术Glide 4.13.0版本
- 基于Kotlin语言编写



## 项目进度规划

- [ ] 新建GlideProgressImageView上传到GitHub中
- [ ] 编写项目MD5介绍项目现状和未来功能规划
- [ ] 将原来的开源项目集成到新的项目中
- [ ] 将Glide版本更新到最新版本
- [ ] 整理出Glide旧版本和新版本之间的差异，并写入项目介绍
- [ ] 修复上述开源库中已知的问题，作为项目迭代的内容。

