# TEXT

emm

这个文件夹用于电子书创作，一些Markdown语法展示在下方，原文链接：[Markdown 官方教程](https://markdown.com.cn/)

# 标题
> 引用
- 列表项
    - hello

日志：

2023年2月3日，黄历四七二一年正月十三：正式将第一个未命名命名为《肆元子》（乐思子 著）

黄帝纪年四七二一年正月廿九雨水：从此开始，该项目固定上传（push）于二十四节气日。

另外，提交文档时，提交说明格式（git commit format）如下：

~~~
def filename1.abc;filename2.efg;...
(type:content1;content2;...)
<blankline>
here's paragraph1
<blankline>
here's paragraph2
<blankline>
...
<blankline>
significant
traditional_year
traditional_month&traditional_day&solar_term
~~~

说明：

head部分：这里def指的是Update、Create、Delete三者之一；
filename1.abc等是包含后缀名的完整文件名；
type指的是新增、添加、完成、修改、清除五者之一；
content1等是简短的说明，一般是较短的祈使句；

blankline指的是空行；

body部分：here's paragraph1等是详细说明；

foot部分：significant、traditional_year、traditional_month_day、solar_term
依次是签名、上传年份（黄帝纪年）、上传日期（农历月日）、上传当天节气（二十四节气）

另外，如果filename和content过长，可以进行调整，比如：

~~~
def (type:)
<blankline>
文件:filename1.abc;filename2.efg;...
内容:content1;content2;...
<blankline>
here's paragraph1
...
~~~

具体环境下可以稍作变动，一个很好的示例如下：

~~~
Update README.md
（新增：上传时间点声明；提交说明格式说明）

乐思子
黄帝纪年四七二一年
正月廿九雨水
~~~

也可以这样写：

~~~
Update README.md
（新增：两项内容）

上传时间点声明；
提交说明格式说明

乐思子
中元四七二一年
正月廿九雨水
~~~

临时：

佛家与佛教，
礼乐学术法，
智慧勇毅法，
无限自由（不可行）和绝对自由（可行）的区别，
边界，混沌边界
