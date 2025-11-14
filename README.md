# Nic

- 关于置顶

Front-matter 中设置 `top` 为 `true` 即可

- 关于分类和标签

参考：[官方文档 Front-matter](https://hexo.io/zh-cn/docs/front-matter)


## 仓库项目说明
主分支推送会触发 actions 构建

生成 gh-pages 分支

仓库/Settings 中可以设置分支及个人域名绑定等


快速创建一个文章页面
```shell
npx hexo new [layout] <title>
```

默认 <code>layout</code> 为 <code>post</code>

可以在 <code>_config.yml</code> 文件中修改 <code>default_layout</code> 字段

会在 <code>source/<_layout>/</code> 下创建名称为 <code>title</code> 的文件

draft 新建的是草稿，需要 publish（发表） 到 post 中才会展示

test merge
