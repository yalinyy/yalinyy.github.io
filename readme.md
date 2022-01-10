## 目录结构

  ├── _config.yml # 网站的配置信息，可以配置网站的绝大部分信息
  ├── package.json # 应用程序的信息，可以不关注
  ├── scaffolds # 模版文件夹，我们在创建新文章时，可以指定某一个模板来生成新文章（.md文档）
  ├── source # 存放用户资源文件的地方，同时这里也会存放我们的博客、标签、目录等内容，这里的.md和html文件会被编译到public文件夹
  |   ├── _drafts # 草稿文件
  |   └── _posts # 博客文件，这里的博客文件会被编译到public文件夹中
  └── themes # 主题文件夹，hexo会根据主题生成博客静态页面

### _config.yml 文件结构

    title: 网站标题
    subtitle: 网站副标题
    description: 网站描述
    keywords: 网站的关键词。支持多个关键词
    author: 作者姓名
    language: 语言，对于简体中文用户来说，使用不同的主题可能需要设置成不同的值，请参考你的主题的文档自行设置，常见的有 zh-Hans和 zh-CN。
    timezone: 网站时区。Hexo 默认使用您电脑的时区。请参考 时区列表 进行设置，如 America/New_York, Japan, 和 UTC 。一般的，对于中国大陆地区可以使用 Asia/Shanghai。
    url: 网址, 必须以 http:// 或 https:// 开头
    theme: 主题，这个是关键，我们可以在网上找一些好看主题
    deploy:
      type: git
      repo: 仓库地址
      branch: 分支，一般是master
