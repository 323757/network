# Python基础备忘录：  
1. 发展历史：荷兰小伙为了改善c语言开发周期慢进行编写
2. 应用场景:web开发（flask） 服务器运维操作系统管理的自动化脚本 网络爬虫 桌面软件pyqt 服务器软件 游戏（py写逻辑c++写高性能图形模块）
3. [py虚拟环境讲解](https://www.bilibili.com/video/BV1U54y1G7DV?vd_source=1554c8023b63d7b8c9f88e02c0abf230&spm_id_from=333.788.videopod.episodes&p=6)
4. 交互模式 ：ipython更好用 ```pip install ipython``` 放在py的python/scripts下
5. if格式：
```
if condition_1:
    statement_block_1 #一个tab或者四个空格缩进
elif condition_2:
    statement_block_2
else:
    statement_block_3
```
6. 列表：```list1 = ['Google', 'Runoob', 1997, 2000] #存储相同类型变量可以增删改```
7. 
```
import sys #system模块
sys.argv[1] #提取终端参数
```
8. 元组 ```tup1 = ('Google', 'Runoob', 1997, 2000)#不可修改保证数据安全性，可以没有括号, 访问也是tup1[0]```
9. 集合数据不可重复
```
set1 = {1, 2, 3, 4}            # 直接使用大括号创建集合
set2 = set([4, 5, 6, 7])      # 使用 set() 函数从列表创建集合
```
10. 列表·元组·集合三者对比：一般使用列表，
三者转换：
```
set()#转集合
tuple()#转元组
list()#转列表
```
11. 字典
```
tinydict = {'name': 'runoob', 'likes': 123, 'url': 'www.runoob.com'}#键对值

```
12. 拆包:，集合拆包无序，字典也可以默认取key无序（字典有其它更多方法待补充）
```
a=[1,2,3]
aa,bb,cc=a 
print('aa=%d'% aa)
rint('bb=%d'% bb)
rint('cc=%d'% cc)  #aa=1,bb=2,cc=3

```
13. 函数
```
def 函数名（参数列表）:
   ''' 这里是函数说明文档是内部第一行将鼠标放置在函数名上即可看到我功能是说明函数功能 '''
    函数体 #pass 占位

```
14. return多个返回值 返回元组列表集合字典 
```
return a,b,c #相当于return (a,b,c)
```
15. 函数要‘高内聚低耦合’就是函数要独立但是不是没有联系 
```
def first():
    return 1
def second(a=first()): #函数返回值当参数
     b=a
```
16. 函数缺省参数(默认参数)
```
# 必填参数a,缺省参数b
def test1(a, b=3):
    print(a, b) 
```
17. [命名参数](https://doc.itprojects.cn/0001.zhishi/python.0001.python3kuaisurumen/index.html#/05.01.canshu)

18.  

   
