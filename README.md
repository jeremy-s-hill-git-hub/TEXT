# TEXT

本仓库主文件: [main](./main.md)

Markdown语法可自行上网搜索, 或者浏览[实例文档](./example.md)以了解语法, 虽然如此, 强烈建议使用基础语法而少使用甚至不使用扩展语法以确保兼容性.

该仓库的笔记方法与**卡片盒笔记法**一致, 虽然如此, 确实是本人独立想到的.  
参考[卡片盒笔记法：一个改变我思维方式的笔记系统 - 少数派](https://sspai.com/post/95590)

---

# 日志: 

2023年2月3日, 黄历四七二一年正月十三: 正式将第一个未命名命名为 ***肆元子***  (乐思子 著) 

黄帝纪年四七二一年正月廿九雨水: 从此开始, 该项目固定上传 (push) 于二十四节气日. 

# 旧的提交说明格式 (old git commit format)

> 待新方案制定后 立即宣布废除

另外, 提交文档时, 提交说明格式 (git commit format) 如下: 

```
type filename1.abc; filename2.efg; ...
 (scope: content1; content2; ...) 

here's paragraph1

here's paragraph2

...

significant
traditional_year
traditional_month&traditional_day&solar_term
```

说明: 

head部分: 这里type指的是Update, Create, Delete三者之一; 
filename1.abc等是包含后缀名的完整文件名; 
scope指的是新增, 添加, 完成, 修改, 清除五者之一; 
content1等是简短的说明, 一般是较短的祈使句; 

body部分: here's paragraph1等是详细说明; 

foot部分: significant, traditional_year, traditional_month_day, solar_term
依次是签名, 上传年份 (黄帝纪年) , 上传日期 (农历月日) , 上传当天节气 (二十四节气) 

另外, 如果filename和content过长, 可以进行调整, 比如: 

```
type (scope: )

contents: content1; content2; ...
files: filename1.abc; filename2.efg; ...

here's paragraph1
...
```

具体环境下可以稍作变动, 一个很好的示例如下: 

```
Update README.md
 (新增: 上传时间点声明; 提交说明格式说明) 

乐思子
黄帝纪年四七二一年
正月廿九雨水
```

也可以这样写: 

```
Update README.md
 (新增: 两项内容) 

上传时间点声明; 
提交说明格式说明

乐思子
中元四七二一年
正月廿九雨水
```
