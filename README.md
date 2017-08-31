## Welcome to GitHub Pages

<div id="plus"></div>
<script src="https://qingqing.com/static/js/plus.js"></script>

  
***

### +QingQing 开放服务


**简介：**+QingQing 开放服务为您的博客文章自动生成评论社区，让您与读者、读者与读者之间更方便的互动交流。只须 2 行代码，即可轻松接入，实时生效，适用所有博客系统。

奇文共欣赏，谈笑已忘时 ~


**二行代码，轻松接入：**

    <div id="plus"></div>
    <script src="https://qingqing.com/static/js/plus.js"></script>


方法：只须将上面 2 行代码，粘贴到博客应用的模板中即可。


使用说明：

* 无须注册开发者账号，在博客应用的模板中加入以上 2 行代码即可。
* 自适应所有PC、平板及手机移动页面。
* 线程式会话，简单轻快。
* 双向连接，流量回源。
* 话题及参与数，实时更新。
* 异步加载，不影响原网页速度。
* 无广告及弹窗，完整保持原站设计风格。
* 支持 Markdown 语法及代码格式。
* 支持 https 和 IPv6 。
* 支持自定义CSS样式（见示例）。


### 建议&反馈： [QingQing.com/plus](https://qingqing.com/post/1021205/time#next)

<br/>

**示例1：WordPress 接入 +QingQing**

以免费模板 hueman 为例，模板文件路径 wp-content/themes/hueman/parts/single-heading.php，在模板文件 single-heading.php 中粘贴 +QingQing 开放服务的 2 行代码即可：

    <h1 class="post-title entry-title"><?php the_title(); ?></h1>  
    <?php get_template_part('parts/single-author-date'); ?>

    <div id="plus"></div>
    <script src="https://qingqing.com/static/js/plus.js"></script>

> 或者把 +QingQing 开放服务的 2 行代码粘贴到模板文件 single.php 中也可。通常 single.php 文件的路径在：wp-content/themes/模板名称/single.php。

![](https://qingqing.com/static/wordpress.png)

<br/>

**示例2：静态博客 Jekyll  接入 +QingQing**

只须将接入 +QingQing 开放服务的 2 行代码，粘贴到 _layouts/post.html 模板文件 post.html 中即可。


自定义CSS样式示例：

```<style type="text/css">div#plus a { color:#00909f; font-size:16px;}</style>```


<br/>
