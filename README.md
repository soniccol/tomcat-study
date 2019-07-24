Tomcat-Study
==================

Tomcat源代碼學習研究(包括源代碼註解、文檔、用於代碼分析的測試用例)


## 使用的Tomcat版本

保持與官方[trunk](https://github.com/apache/tomcat)版本同步


## 建構與運行環境

需要JDK7以及[Apache Maven](http://maven.apache.org/)


## 產生Eclipse Project

mvn eclipse:eclipse <br><br>

在eclipse中導入 <br>
File->Import->General->Existing Projects into Workspace


## 啟動Tomcat

在Eclipse中右鍵start-tomcat.launch這個文件，點Run As啟動Tomcat，點Debug As可以驗測Tomcat。

<p>啟動並打開你的瀏覽器，輸入 http://127.0.0.1:8080/examples/ 看看例子吧。
