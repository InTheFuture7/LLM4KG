coming soon!


# 基于大模型 api 生成课程知识图谱

## 环境配置
win11
docker 部署 milvus 2.4.4
MongoDB 7.0.11 Community
neo4j desktop 5.20.0（apoc插件）
umi-ocr

python 3.10
torch 2.3.0 + cu121

## 文件层级
.env  # 大模型api
LLM4KG.ipynb  # 生成知识图谱的代码
upload_file_mongodb.ipynb  # 上传文件到知识图谱的代码
zhipuai_llm.py  # 忘记是否有用了
zhipuai_embedding.py  # 忘记是否有用了
database/resource  # 存放待上传的文件
databse/教材名/part_textbook  # 教材的word文件（多个）
databse/教材名/part_keywords/all_keywords.txt  # 手工提取的教材关键词文件
output  # 里面存放 json 文件

## 运行
启动服务后，运行两个 jupyter 文件即可
