运行爬虫程序：
scrapy crawl quotespider


指定输入文件格式：
scrapy crawl quotespider -o quote.csv

scrapy crawl quotespider -o quote.json

scrapy crawl quotespider -o quote.jl

scrapy crawl quotespider -o quote.xml

scrapy crawl quotespider -o quote.marshal 此格式一般在数据分析使用

此外还支持远程ftp保存：
scrapy crawl quotespider -o ftp://user:parse@ftp.example.com/path/quote.csv

