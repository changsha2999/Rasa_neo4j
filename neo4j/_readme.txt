安装neo4j


数据导入neo4j
前提是已经有了可以连接的neo4j graph

解压MedicalSpider/data/data.tar.gz，直接解压到MedicalSpider/data下，
不要新建文件夹，则medical.json是所有数据的汇总， 将会被导入到你的知识图谱中

修改process_data下的create_graph.py，把neo4j数据库的链接信息改成你自己的，
然后运行该文件 （为了防止路径问题，建议使用Pycharm打开本项目后运行）