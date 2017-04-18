![screenshot](https://raw.githubusercontent.com/shuibaco/blogger-theme-simplicity/master/screenshot.jpg)

# 特点

- **墙内可见**
- 简洁单栏
- 浅灰色柔和色调，易于阅读
- 底部工具栏有两种形式：三小列和一大列
- 当前页面菜单栏高亮
- 页码导航
- 存档页面只显示标题
- 平滑滚动
- 代码高亮
- “上一篇”“下一篇”链接改为文章标题
- 图片的 Lightbox 弹出效果
- 相关文章（需要另外安装步骤 [LinkWithin](http://www.linkwithin.com)）
- Disqus 评论系统（需要更改部分设置）

# 不足

- 无二级菜单
- 非响应式设计，手机阅读较吃力

# 安装

在线预览：https://theme-simplicity.blogspot.com

下载 blogger-theme-simplicity.xml，进入 Blogger 后台，选择 Template（模板） 选项，点击右上角 Backup / Restore（备份/还原），先 Download full template（下载使用中的模板）以做备份，然后再 Choose File（选择文件），选择刚刚解压的 blogger-theme-simplicity.xml，点击 Upload（上传）。上传完成后可以刷新一下博客页面，这时候应该已经有了基本版面，接着我们就来修改一下细节。选择 Layout（布局）选项，按照以下图片中所示结构调整相应模块：

![layout](https://raw.githubusercontent.com/shuibaco/blogger-theme-simplicity/master/layout.jpg)

- **Favicon 网站图标**：可以上传自己喜欢的图片；
- **Simplicity (Hearder)  网站名称**：在 Setting（设置）里更改；
- **Pages 菜单栏**：标题留空，否则会出现在菜单栏上方；
- **Blog Posts 博文**：更改发布时间、标签等点击右下角 Edit（编辑）；
- **Disqus**：需要删除，然后到 [disqus.com](http://disqus.com) 重新安装一次；另外需要修改 Recent comments 里的代码，将 `your-disqus-shortname` 更换为你的 Disqus shortname（Disqus 后台可以找到）；
- **Add a Gadget 添加小工具**：此部分一共分为四块1234，前三块123分别对应三列小工具栏，最后一块4是一长列大工具栏。应该已经有人注意到4里面有一个叫 HTML/JavaScript 的模块，这里面装的是显示相关文章的 [LinkWithin](http://www.linkwithin.com) 的代码。
