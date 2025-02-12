＃欢迎来到杰基尔！
＃
＃此配置文件用于影响您整个站点的设置，值
＃您期望您设置一次，并且在此之后很少需要编辑。，并且在此之后很少需要编辑。，并且在此之后很少需要编辑。
＃出于技术原因，此文件使用时 *未 *自动重新加载
＃“ jekyll服务 -l -h localhost”，。如果更改此文件，请重新启动，请重新启动
＃服务器进程。

＃基本站点设置
语言环境：“ en-us”
site_themesite_theme：“默认”：“默认”：：：：：：：：：：：
标题：“苏维埃” ＃标题：“苏维埃” ＃标题
title_separatortle_separator：“  - ”：“  - ”
名称姓名：＆名称“苏维埃”：＆名称“苏维埃”
描述描述：＆描述“个人介绍”：＆描述“个人介绍”
url：https：//hao45444444.github.io/deng.github.io/＃您的网站的基本主机名和协议.github.io ]。
baseurl：“” ＃您的网站的子路口，例如，“/博客”
存储库：“ https://hao45444.github.io/deng.github.io/”

＃站点作者-以下控制在侧栏上显示的作者内容的一部分。
＃如果字段为空白，则不会出现链接，否则将显示。，否则将显示。，否则将显示。，否则将显示。
＃其他自定义可以通过编辑 /_包括 /author-profile.html完成
作者：
  ＃传记信息
  ：“
  名称：“ Manbaot”
  代词：“他”
  简历：“个人介绍”
  位置：“住址”
  雇主：“毕业于xxx”
  uri：＃url
  电子邮件：“ dsj4088@foxmail.com”

  ＃学术网站
  arxiv：＃url-更新到您个人资料的正确链接
  googlescholar：＃“ https://scholar.google.com/citations ？用户 = ps_cx0aaaaaaj”
  ImpactStory：＃url
  orcid：＃“ http：//orcid.org/yourorcidurl”
  语义：＃url
  PubMed PubMed：＃“ https://www.ncbi.nlm.nih.gov/pubmed/?term=john+Snow”：＃“ https://wwwww.ncbi.ncbi.ncbi.nlm.nlm.nih.gov /PubMed/PubMed/PubMed/？约翰+雪””””
  ResearchGate ResearchGate：＃url：＃url
  scopus scopus：＃url：＃url

  ＃存储库和软件开发
  Bitbucket：＃用户名 -在网站上使用用户名更新-在网站上使用用户名更新
  Codepen：＃用户名
  运输：＃用户名
  github：“ hao45444” #github用户名
  Kaggle：＃用户名  
  stackoverflow：＃用户号或用户编号和名称（即，使用“ 1”或“ 1/jeff-atwood”）    

  ＃社交媒体
  蓝调：＃“ bsky.app” ＃用您替换为Bluesky用户名
：＃用户名
  flickr flickr：＃用户名：＃用户名
  foursquare foursquare：＃用户名：＃用户名
  GoodReads Goodreads：＃用户名：＃用户名
  Google_plus Google_plus：＃用户名：＃用户名：＃用户名：＃用户名
  键基础：＃用户名：＃用户名
  Instagram Instagram：＃用户名：＃用户名
  LastFM LastFM：＃用户名：＃用户名
  LinkedIn LinkedIn：＃用户名：＃用户名
  mastodon mastodon：＃url：＃url
  medium           : # URL
  pinterest        : # Username
  soundcloud       : # Username
  steam            : # Username
  telegram         : # URL
  tumblr           : # Username
  twitter          : # Username for X / Twitter
  vine             : # Username
  weibo            : # Username
  wikipedia        : # Username
  xing             : # Username
  youtube          : # Username
  zhihu            : "知乎用户名"# Username

# Publication Category - The following the list of publication categories and their headings
publication_category:
  books:
    title: 'Books'
  manuscripts:
    title: 'Journal Articles'    
  conferences:
    title: 'Conference Papers'

# Site Settings
teaser                   :  # filename of teaser fallback teaser image placed in /images/, .e.g. "500x300.png"
breadcrumbs              : false # true, false (default)
words_per_minute         : 160
future                   : true
read_more                : "disabled" # if enabled, adds "Read more" links to excerpts
talkmap_link             : false      #change to true to add link to talkmap on talks page
comments:
  provider               : # false (default), "disqus", "discourse", "facebook", "google-plus", "staticman", "custom"
  disqus:
    shortname            :
  discourse:
    server               : # https://meta.discourse.org/t/embedding-discourse-comments-via-javascript/31963 , e.g.: meta.discourse.org
  facebook:
    appid                :
    num_posts            : # 5 (default)
    colorscheme          : # "light" (default), "dark"
staticman:
  allowedFields          : ['name', 'email', 'url', 'message']
  branch                 : "gh-pages" # "master", "gh-pages"
  commitMessage          : "New comment."
  filename               : comment-{@timestamp}
  format                 : "yml"
  moderation             : true
  path                   : "_data/comments/{options.slug}"
  requiredFields         : ['name', 'email', 'message']
  transforms:
    email                : "md5"
  generatedFields:
    date:
      type               : "date"
      options:
        format           : "iso8601" # "iso8601" (default), "timestamp-seconds", "timestamp-milliseconds"
atom_feed:
  hide                   : false     # change to true to hide the RSS feed in the footer
  path                   : # blank (default) uses feed.xml


# SEO Related
google_site_verification :
bing_site_verification   :
alexa_site_verification  :
yandex_site_verification :


# Social Sharing
twitter:
  username               : &twitter
facebook:
  username               :
  app_id                 :
  publisher              :
og_image                 :  # Open Graph/Twitter default site image
# For specifying social profiles
# - https://developers.google.com/structured-data/customize/social-profiles
social:
  type                   : # Person or Organization (defaults to Person)
  name                   : # If the user or organization name differs from the site's name
  links: # An array of links to social media profiles


# Analytics
analytics:
  provider               :  "false" # false (default), "google", "google-universal", "google-analytics-4", "custom"
  google:
    tracking_id          :


# Reading Files
include:
  - .htaccess
  - _pages
  - files
exclude:
  - "*.sublime-project"
  - "*.sublime-workspace"
  - .asset-cache
  - .bundle
  - .github
  - .jekyll-assets-cache
  - .sass-cache
  - assets/js/_main.js
  - assets/js/plugins
  - assets/js/vendor
  - CHANGELOG
  - Capfile
  - config
  - Dockerfile
  - Gemfile
  - Gruntfile.js
  - gulpfile.js
  - LICENSE
  - local
  - log
  - node_modules
  - package.json*
  - Rakefile
  - README
  - tmp
  - vendor
keep_files:
  - .git
  - .svn
encoding: "utf-8"
markdown_ext: "markdown,mkdown,mkdn,mkd,md"


# Conversion
markdown: kramdown
highlighter: rouge
lsi: false
excerpt_separator: "\n\n"
incremental: false


# Markdown Processing
kramdown:
  input: GFM
  hard_wrap: false
  auto_ids: true
  footnote_nr: 1
  entity_output: as_char
  toc_levels: 1..6
  smart_quotes: lsquo,rsquo,ldquo,rdquo
  enable_coderay: false


# These settings control the types of collections used by the template
collections:
  teaching:
    output: true
    permalink: /:collection/:path/
  publications:
    output: true
    permalink: /:collection/:path/
  portfolio:
    output: true
    permalink: /:collection/:path/
  talks:
    output: true
    permalink: /:collection/:path/


# These settings control how pages and collections are included in the site
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true
  # _pages
  - scope:
      path: ""
      type: pages
    values:
      layout: single
      author_profile: true
  # _teaching
  - scope:
      path: ""
      type: teaching
    values:
      layout: single
      author_profile: true
      share: true
      comments: true
  # _publications
  - scope:
      path: ""
      type: publications
    values:
      layout: single
      author_profile: true
      share: true
      comments: true
  # _portfolio
  - scope:
      path: ""
      type: portfolio
    values:
      layout: single
      author_profile: true
      share: true
      comment: true
  # _talks
  - scope:
      path: ""
      type: talks
    values:
      layout: talk
      author_profile: true
      share: true


# Sass/SCSS
sass:
  sass_dir: _sass
  style: compressed # http://sass-lang.com/documentation/file.SASS_REFERENCE.html#output_style


# Outputting
permalink: /:categories/:title/
# paginate: 5 # amount of posts to show
# paginate_path: /page:num/
timezone: Etc/UTC # http://en.wikipedia.org/wiki/List_of_tz_database_time_zones


# Plugins
plugins:
  - jekyll-feed
  - jekyll-gist
  - jekyll-paginate
  - jekyll-sitemap
  - jekyll-redirect-from
  - jemoji

# Mimic GitHub Pages with --safe
whitelist:
  - jekyll-feed
  - jekyll-gist
  - jekyll-paginate
  - jekyll-sitemap
  - jekyll-redirect-from
  - jemoji


# Archives
#  Type
#  - GitHub Pages compatible archive pages built with Liquid ~> type: liquid (default)
#  - Jekyll Archives plugin archive pages ~> type: jekyll-archives
#  Path (examples)
#  - Archive page should exist at path when using Liquid method or you can
#    expect broken links (especially with breadcrumbs enabled)
#  - <base_path>/tags/my-awesome-tag/index.html ~> path: /tags/
#  - <base_path/categories/my-awesome-category/index.html ~> path: /categories/
#  - <base_path/my-awesome-category/index.html ~> path: /
category_archive:
  type: liquid
  path: /categories/
tag_archive:
  type: liquid
  path: /tags/
# https://github.com/jekyll/jekyll-archives
# jekyll-archives:
#   enabled:
#     - categories
#     - tags
#   layouts:
#     category: archive-taxonomy
#     tag: archive-taxonomy
#   permalinks:
#     category: /categories/:name/
#     tag: /tags/:name/


# HTML Compression
# - http://jch.penibelst.de/
compress_html:
  clippings: all
  ignore:
    envs: development
