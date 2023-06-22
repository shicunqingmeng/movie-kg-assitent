# Movie-Knowledge-QS-system-using-KnowledgeGraph
## 一、简洁
利用python语言借助于知识图谱搭建电影知识问答系统
## 二、文件结构
* Clawer250.py 爬虫代码爬取豆瓣250网页电影知识
* movieInfo.csv 爬取数据构建电影知识数据集文件
* IntelligentCommunicationSystem.py 基于电影数据和知识图谱搭建知识问答系统
* KnowledgeGraph.py 知识图谱搭建
* selfDefiningFile.py 生成结巴分词自定义词典
* selfDefiningTxt.txt jieba分词自定义词典
## 三、调用方法
* 修改KnowledgeGraph.py中的用户名和密码，运行代码，生成知识图谱（neo4j需要先启动终端输入neo4j.bat console）
* 运行IntelligentCommunicationSystem.py完成电影问答
## 四、原文博客链接
这只是我学习的记录 原文：https://blog.csdn.net/DALEONE/article/details/125116858?spm=1001.2014.3001.5501
