## 使用方法

1. 首先你得有个[博客](http://www.cnblogs.com/)

2. 打开 [博客后台管理](https://i.cnblogs.com/Configure.aspx)

3. 申请js权限

4. 在博客皮肤选项卡中将博客皮肤设置为： [BlueSky](http://www.cnblogs.com/SkinUser.aspx?SkinName=BlueSky)

5. 将[页面定制.css ](https://github.com/ranxi169/cnblogs-beautify/blob/main/页面定制.css) 复制到 `页面定制CSS代码` 代码框内

6. 将[页首.html](https://github.com/ranxi169/cnblogs-beautify/blob/main/页首.html) 复制到 `页首Html代码` 代码框内

7. 将[页尾.html](https://github.com/ranxi169/cnblogs-beautify/blob/main/页尾.html)  复制到 `页脚Html代码` 代码框内

8. 根据自身情况修改`页尾.html`中的`js`

```javasript
<script type="text/javascript">
    //博主名称 可不改，默认取博客园提供的，改了加载速度会稍快
    var nickName =null;
    //slogan 标语
    var slogan = '全职法师，浅尝辄止';
    //下列图片可以直接用博客园的相册功能《查看原图》可以获取链接
    //icon 博客徽标（左上角），需要自己ps制图[网站logo]
    var icon = "https://images.cnblogs.com/cnblogs_com/blogs/757245/galleries/
2178271/o_220806112142_blog_logo.png";
    //默认博客背景图片，可以使用ps放一个头像[长横幅]
    var defaultPic="https://images.cnblogs.com/cnblogs_com/blogs/757245/galleries/
2178271/o_220806113414_background.jpg";
    //icon(浏览器标题栏上的)，直接用的博客园的标志
    var iconB="https://img2018.cnblogs.com/blog/1138447/201909/1138447-20190911161817172-1737762696.png";
    //微信公众号地址
    var friendLink="https://images.cnblogs.com/cnblogs_com/blogs/757245/galleries/
    2178271/o_220723103231_wechat.png";
    //关于我地址
    var aboutMe="https://onefly.top";
    //Github地址,假如博客username与Github username相同，不用改。
    //如 cnblogs.com/username github.com/username 这样就不用改
    var myGayhubUrl = null;
</script>
```

8. 保存，即可食用

## 博客示例

------------------------>>> [孤飞 - 博客园 (cnblogs.com)](https://www.cnblogs.com/ranxi169/)

## 注意事项

①icon：网站logo需要注意宽度，默认用76像素（ppi），长度没有很多限制

②defaultPic：在psd文件指定位置更换头像即可

以上文件在picture文件夹内，logo可以用标志客生成，然后去水印(bushi)。

③另外js运行需要借用一个库函数[nprogress.js](https://github.com/ranxi169/cnblogs-beautify/blob/main/nprogress.js)，需要提前上传到博客园-文件[博客后台 - 博客园 (cnblogs.com)](https://i.cnblogs.com/files)

![](https://github.com/ranxi169/cnblogs-beautify/blob/main/picture/files.png)

![](https://github.com/ranxi169/cnblogs-beautify/blob/main/picture/nprogress_file.png)
