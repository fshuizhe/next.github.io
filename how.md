# 本文档试图将整个网站的结构摸索清楚

## _data 文件夹
只有languages一个子文件夹，里面放了各种语言的翻译文件。

## _includes 文件夹
存放所有的网站结构文件。
### _blocks文件夹
按照page.layout的值来设置一系列变量的值。
- page_class.html 按照page.layout设置page_class，分为index首页，post、page文章页，archive归档列表页和schedule主题切换
- script_extra.html 按照page.layout设置script_extra，分为post文章页，archive归档列表页,分类、标签页和其他
- sidebar.html 按照page.layout设置sidebar的值。且如果page.layout为post，则is_post为真。
- title.html 按照page.layout设置title的值。
### _custom文件夹
应该是可以自定义设置header和sidebar内的内容。
### _helper文件夹
应该是一些辅助文件。

