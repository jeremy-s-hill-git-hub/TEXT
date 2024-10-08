## 整理方案:

> 本方案基于index-expand framework v3.0, 结合note-wiki标记, 主要使用markdown撰写

index-expand framework v3.0内容列表:

* index-expand基本框架: 节点, 网络
* 文章模块化: 多文件化, 文件夹存储
* 入口机制: entry入口, main主入口

基于此, 整理方法如下: 内容分为note和wiki两部分, note放文章, wiki放词条解释
这两者的入口, 也就是本项目的主入口, 内置到已有的README.md, 不额外设置项目主入口
note主入口为main.md, wiki主入口设为home.md
note按照内容可以分一个或多个文件夹, 但建议尽量少建文件夹
wiki按照词条分多个文件, 不可分为多个文件夹
整理方式基本参照index-expand framework v3.0, 若上述标准与本文有所冲突, 以本文为准.

note与wiki两个文件夹的作用可见这里: [note-wiki标记在本项目的应用](note-wiki标记.md "Note")
