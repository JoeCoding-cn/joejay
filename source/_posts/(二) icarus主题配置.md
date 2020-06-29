#### 国际化

hexo支持国际化, icarus主题自带了多个语言

进入到blog目录下 `/themes/icarus/languages`

![](https://joe-1253912574.cos.ap-shenzhen-fsi.myqcloud.com/images/Snipaste_2020-06-29_11-39-28.png)

可以看到这里已经内置了中文简体

接下来修改配置文件`_config.yml`  需要注意的是 `_config.yml` 有两个 一个是hexo的  一个是icarus主题的 icarus的配置文件在 `/themes/icarus/_config.yml`  

我们需要修改的是hexo的_config.yml 千万不能搞错了 修改languages为 zh-CN 繁体就是zh-TW咯上图文件夹下有的都可以配置 或者你也可以自定义国际化,随便打开一个yml照着改就行了

![](https://joe-1253912574.cos.ap-shenzhen-fsi.myqcloud.com/images/Snipaste_2020-06-29_11-49-28.png)





#### 个人信息修改

也就是 网页中这一块

![](https://joe-1253912574.cos.ap-shenzhen-fsi.myqcloud.com/images/E5F85CBC-DB70-4C36-9374-820C72E2F7EF.png)

在博客根目录 `cd themes/icarus`  修改 `_config.yml` 这是icarus主题下的配置文件 `vim _config.yml` 或者直接用编辑器编辑

找到widgets 然后需要啥就配啥不需要就注释掉