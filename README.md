## 程序使用范围：
晋江论坛在实行随机id后的帖子<br>
- 修改1.0<br>
只要有id的页码都可以爬惹！！<br>
对于一半没id一半有id的帖子，请从有id出现的那一页开始爬起

# 程序功能
- csv格式可交互.py<br>
作用：按楼层顺序，爬取某个帖子的所有内容，输出为csv格式<br>
内容包括：id，发表时间，发表内容，楼层号<br>

- csv文件读取整理.py<br>
作用：读取之前爬取的csv文件并整理，输出两个csv文件<br>
文件1：统计所有出现次数>2的id，及他们出现的次数，按出现次数降序排列<br>
文件2：统计所有id的发言，格式和读取的csv文件一致，按id发言次数降序排列

# 缺点：
1. 程序爬取内容不包括主楼<br>
2. 遇到随机id中含有【e+数字】的形式，csv文件会将其按科学计数法读取，但是不影响后续统计
