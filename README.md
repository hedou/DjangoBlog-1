# DjangoEast
# 更新日志
## 2019.3.7
- 修复mdeditor编辑器上传图片无法显示的问题
- 删除templates/blog/base.html文件（还未同步）
- 修改文章列表页文章标题显示长度，30→50
- 修改相关文章的文章标题的显示效果
- 取消git对项目下的upload与media文件夹的跟踪
- 去除文章摘要中的">"字符，在结尾添加"......"
- 文章目录去掉无序列表的圆点
- 修改了STATIC_ROOT的参数，使collectstatic操作正常
- 修改tag_list页面下文章显示顺序，刚发表的排在前面

## 2019.3.8
- 修复分类归档页面使用regroup产生的分组重复的问题
- 修改文章页底部相关文章的个数：8→4

## 2019.3.10
- 修改分类目录页文章显示顺序
- 首页添加按分类展示的文章块:blockposts