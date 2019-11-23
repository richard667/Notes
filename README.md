# LeoHsiao的笔记

- 该笔记的主要目的是记录知识点，没有平滑的原理讲解。
- 笔记保存为MarkDown格式，按文档目录排序
- 基于docsify显示静态网站，访问URL：<http://leohsiao.com/>
- 欢迎指正


<!-- 该文件内不能再使用 # 标题，以免破坏目录排版 -->

执行以下命令即可启动一个HTTP服务器：

```
python -m http.server 80 --bind 127.0.0.1
```

部署命令：
```
docker run -d --name nginx -p 80:80 -v /root/Notes/www:/root/Notes/www -v /root/Notes/nginx.conf:/etc/nginx/nginx.conf nginx
```
