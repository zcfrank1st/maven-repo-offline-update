## 离线更新maven repo index

1. 首先下载如下两个文件:

	http://repo1.maven.org/maven2/.index/nexus-maven-repository-index.properties

	http://repo1.maven.org/maven2/.index/nexus-maven-repository-index.gz

2. 将两文件放入 根目录/maven2/.index/中

3. 在根目录启动 http 服务器: sudo python https-server.py

4. 修改hosts 127.0.0.1 repo1.maven.org

5. 结束后改回
