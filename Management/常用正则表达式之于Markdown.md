

# 常用正则表达式之于Markdown



##### 实现功能：未添加的专有词汇添加“【】”外框；

查找：
```text
(?<!【)(X)(?!=】)
```

替换：
```text
【$1】
```



