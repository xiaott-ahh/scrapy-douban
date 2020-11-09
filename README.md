# scrapy-douban
这是一个简单的豆瓣电影爬虫，基于Scrapy开发，是我另一个项目[five-six](https://github.com/xiaott-ahh/five-six)的支撑项目,
主要爬取电影的基本信息和封面图片，并在管道中下载图片到本地和导入MySQL数据库，方便后续开发   
爬取的效果如下：


![image](https://img-blog.csdnimg.cn/2020110818093119.gif#pic_center)

# 运行本项目
## 环境和依赖
- python3.7+
- scrapy

## 克隆到本地
```
git clone https://github.com/xiaott-ahh/scrapy-douban.git
```
## 进入对应的目录运行
```
scrapy crawl movie_hot
```
