本爬虫使用的是以java的jsoup的html解析器对html进行解析
工程使用maven生成，需要下载相对应的jsoup版本
数据源是使用搜狗搜索的结果，暂时还没做自定义迭代搜索页，这个要做的话只需要对URL进行拼接
得到的数据存储在同目录下的result.txt中，暂时是使用换行来作为文章分割符号