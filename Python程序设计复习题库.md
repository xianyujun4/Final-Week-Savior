# Python 综合题库

## 一、填空题

**1. Python概述**

1. Python是一门面向 "对象" 的高级编程语言。
2. Python可以在多种平台运行，这体现了Python语言的 "可移植性" 特性。
3. Python模块的本质是后缀名为 ".py" 的文件。
4. Python中使用 "import" 语句可以在当前程序中导入模块。
5. "pip" 工具是一个通用的Python模块、包或库的管理工具。

**2. Python基础**

1. 布尔类型的取值包括 "True" 和 "False" 。
2. 使用 "type() " 函数可查看数据的类型。
3. float()函数用于将数据转换为 "浮点" 类型的数据。
4. 若a=3，b=-2，则a+=b执行后a的结果为 "1" 。

**3. 流程控制**

1. Python中通过 "if" 语句实现程序中条件语句的嵌套逻辑。
2. Python中的循环语句有 "for" 循环和 "while" 循环。
3. 若循环条件的值变为 "True" ，说明程序进入无限循环。
4. "for" 循环一般用于实现遍历循环。
5. "break" 语句可以跳出本次循环，执行下一次循环。

**4. 字符串**

1. Python中可以使用 "单引号" 、双引号和三引号定义字符串。
2. Python中可以使用 "+" 运算符拼接字符串。
3. 使用find()方法查找子串时，若没有查找到则返回 "-1" 。

**5. 组合数据类型**

1. 使用内置的  "list()"  函数可创建一个列表。
2. Python中列表的元素可通过索引或  "切片"  两种方式访问。
3. 字典元素由 "键" 和 "值" 组成。
4. 字典中的键具有 "唯一性" 性。

**6. 函数**

1. Python中使用关键字 "def" 定义一个函数。
2. 若函数内部调用了自身，则这个函数被称为 "递归函数" 。
3. Python中使用 "global" 关键字可以在函数内部声明全局变量。
4. "局部变量" 是指在函数内部定义的变量，它只能在函数内部被使用。

**7. 文件与数据格式**

1. 打开文件对文件进行读写后，应调用 "close()" 方法关闭文件以释放资源。
2. seek()方法用于移动文件读写位置，该方法的 "offset" 参数表示要偏移的字节数。
3. os模块中的 "mkdir()" 函数用于创建目录。
4. "绝对路径" 从根目录开始完整地指定文件的位置。

**8. 面向对象**

1. Python中使用 "class" 关键字来定义一个类。
2. 类的成员包括 "属性" 和 "方法" 。
3. Python可以通过在类成员名称之前添加 "双下划线" 的方式将公有成员改为私有成员。
4. 当一个类继承了另一个类，被继承的类称为 "父类" 或 "基类" ，继承其他类的类称为 "子类" 。
5. 子类中使用 "super()" 函数可以调用父类的方法。

**9. 异常**

1. Python中所有异常都是 "BaseException" 类的子类。
2. 当程序中使用了一个未定义的变量时会引发 "NameError" 异常。
3. 自定义异常需要继承 "Exception" 类。
4. 若不满足assert语句中的表达式会使程序抛出 "AssertionError" 异常。
5. Python使用 "raise" 语句可以重新抛出刚刚发生的异常。

**10. Python计算生态与常用库**

1. "爬虫" 是一种按照一定的规则自动从网络上抓取信息的程序或者脚本。
2. "Python计算生态" 是由Python语言和其周边生态系统所构成的一系列工具、框架、库和应用。
3. Python中time()函数用于返回一个浮点数表示的 "时间戳" 。
4. Python中的 "random" 库用于生成随机数。




## 二、判断题

1. 实现同一功能时，Python程序比C++程序的代码量多，运行速度快。（F）
2. import语句支持一次导入多个模块。（T）
3. Python程序的执行依赖Python解释器。（F）
4. 模块文件的后缀名一定是.py。（T）
5. Python中可以使用关键字作为变量名。（F）
6. 变量名可以以数字开头。（F）
7. Python标识符不区分大小写。（F）
8. 布尔类型是特殊的浮点型。（F）
9. if-else语句可以包含多个判断条件。（T）
10. if语句不支持嵌套使用。（F）
11. elif可以单独使用。（F）
12. break语句用于结束循环。（T）
13. for循环只能遍历字符串。（F）
14. 字符串中不可以包含特殊字符。（F）
15. 无论是使用单引号或双引号定义的字符串，使用print()输出的结果一致。（T）
16. find()方法返回-1说明子串在指定的字符串中。（F）
17. strip()方法默认会删除字符串头尾的空格。（T）
18. 列表只能存储同一类型的数据。（F）
19. 列表的索引从1开始。（F）
20. 字典中的键唯一。（T）
21. 字典中的元素可通过索引方式访问。（F）
22. 函数在定义完成后会立刻执行。（F）
23. 变量在程序的任意位置都可以被访问。（F）
24. 函数可以提高代码的复用性。（T）
25. 函数的位置参数有严格的位置关系。（T）
26. Python中打开文件时默认使用的模式为只读。（T）
27. 以读写方式打开一个文件，若文件已存在，文件内容会被清空。（F）
28. 使用write()方法写入文件时，数据会追加到文件的末尾。（F）
29. Python中使用os模块中的函数实现目录相关的操作。（T）
30. 使用read()方法只能一次性读取文件中的所有数据。（F）
31. Python中通过类可以创建对象，有且只能创建一个对象。（F）
32. 实例方法可以由类和对象调用。（T）
33. 创建类的对象时，解释器会自动调用构造方法进行初始化操作。（T）
34. 子类中不能重新实现从父类继承的方法。（F）
35. try-except语句中只能有一个except子句。（F）
36. finally子句在任何情况下一定会被执行。（T）
37. raise语句可以抛出指定的异常。（T）
38. 如果一个程序没有捕获与处理异常，那么它出现异常时会终止运行。（T）
39. try-except语句可以有多个finally子句。（F）
40. 用户既可以在程序中使用内置库，也可以使用第三方库。（T）
41. Python中内置库与第三方库的使用方式相同，但使用第三方库之前需要先将库导入程序。（T）
42. 当一个模块__name__的取值为 " __main__ " 时，说明模块被导入了其他程序。（F）



## 三、选择题

**1. Python概述**

1. 下列选项中，属于Python语言特点的是（ABCD）。（多选）
   A.简洁 B.开源 C.可移植性好 D.类库丰富
2. 下列选项中，哪个不属于Python的应用领域？（D）
   A. Web开发 B.数据分析 C.人工智能 D.操作系统管理
3. 关于Python程序运行的说法中，描述错误的是（D）。
   A. Python程序的运行依赖解释器
   B. Python程序可以通过解释器逐行解释并运行
   C. Python程序只能通过解释器逐行运行
   D. Python程序可以以文件的形式运行

**2. Python基础**

1. 下列选项中，用于Python代码实现单行注释的符号是（A）。
   A. # B. / C. // D. `<! "   " >`
2. 下列选项中，不属于Python关键字的是（A）。
   A. name B. if C. is D. and
3. 下列选项中，哪个数据的类型是属于数字类型的？（B）
   A. 0 B. 1.0 C. 1+2j D. 以上全部
4. 若想要将2转换为二进制数0b10，应该使用下列哪个函数？（B）
   A. oct() B. bin() C. hex() D. int()
5. 下列选项中，不属于Python数据类型的是（C）。
   A. bool B. dict C. string D. set

**3. 流程控制**

1. 下列选项中，运行后会输出1、2、3的是（）。
   ```python
   nums = [0, 1, 2]
   for i in nums:
       print(i + 1)
   ```
2. 现有如下代码，输出结果为（C）。
   ```python
   sum = 0
   for i in range(100):
       if(i % 10):
           continue
       sum = sum + i
   print(sum)
   ```

   A. 5050 B. 4950 C. 450 D. 45
3. 已知x=10，y=20，z=30；
   ```python
   if x < y:
       z = x
       x = y
       y = z
   ```

   执行后x、y、z的值分别为（c）。
   A. 10，20，30 B. 10，20，20 C. 20，10，10 D. 20，10，30
4. 下列语句中，可以跳出循环结构的是（B）。
   A. continue B. break C. if D. while

**4. 字符串**

1. Python中使用（B）转义字符。
   A. / B. \\ C. $ D. %
2. 下列选项中，用于格式化字符串的是（D）。
   A. % B. format() C. f-string D. 以上全部
3. 关于字符串的说法中，下列描述错误的是（A）。
   A. 字符串创建后可以被修改
   B. Python中可以使用三引号定义字符串
   C. 转义字符\\n表示换行符
   D. 格式符均由%和说明转换类型的字符组成
4. 下列方法中，可以将字符串中的字母全部转换为大写的是（A）。
   A. upper() B. lower() C. title() D. capitalize()
5. 下列选项中，不属于字符串的是（D）。
   A.  " 1 "  B. 'python' C.  "  "  " ^ "  "  "  D. '1'.23

**5. 组合数据类型**

1. 下列方法中，可以对列表元素排序的是（A）。
   A. sort() B. reverse() C. max() D. list()
2. 阅读下面的程序，输出结果是（ ）。
   ```python
   li_one = [2, 1, 5, 6]
   print(sorted(li_one[:2]))
   ```
3. 下列方法中，默认删除列表最后一个元素的是（C）。
   A. del B. remove() C. pop() D. extend()
4. 阅读下面程序：
   ```python
   lan_info = {'01': 'Python', '02': 'Java', '03': 'PHP'}
   lan_info.update({'03': 'C++'})
   print(lan_info)
   ```

   输出结果是（B）。
   A. {'01': 'Python', '02': 'Java', '03': 'PHP'}
   B. {'01': 'Python', '02': 'Java', '03': 'C++'}
   C. {'03': 'C++','01': 'Python', '02': 'Java'}
   D. {'01': 'Python', '02': 'Java'}

**6. 函数**

1. 下列关于函数的说法中，描述错误的是（D）。
   A. 函数可以减少重复的代码，使得程序更加模块化
   B. 不同的函数中可以使用相同名字的变量
   C. 调用函数时，实参的传递顺序与形参的顺序可以不同
   D. 匿名函数与使用关键字def定义的函数没有区别
2. Python使用哪个关键字定义一个匿名函数？（D）
   A. function B. func C. def D. lambda
3. Python使用哪个关键字自定义一个函数？（ C）
   A. function B. func C. def D. lambda
4. 请阅读下面的代码，输出结果为（B）。
   ```python
   num_one = 12
   def sum(num_two):
       global num_one
       num_one = 90
       return num_one + num_two
   print(sum(10))
   ```

   A. 102 B. 100 C. 22 D. 12

**7. 文件与数据格式**

1. 若打开一个已有文件后在文件末尾添加数据，则应该使用下列哪种模式打开文件？（C）
   A. r B. w C. a D. w+
2. 通过open()方法打开不存在的文件时，使用以下哪种模式打开会使程序报错？（B）
   A. r B. w C. a D. w+
3. 假设file是文本文件对象，下列哪个选项用于读取file的一行内容？（C）
   A. file.read() B. file.read(200) C. file.readline() D. file.readlines()
4. 下列函数或方法中，用于向文件中写入数据的是（B）。
   A. open() B. write() C. close() D. read()
5. 下列函数或方法中，用于获取当前目录的是（C）。
   A. open() B. write() C. getcwd() D. read()
6. 下列代码要打开的文件应该在（C）。
   ```python
   f = open('itheima.txt', 'w')
   ```

   A. C盘根目录 B. D盘根目录 C. Python安装目录 D. 程序所在目录
7. 假设文本文件abc.txt中的内容如下：abcdef。编写程序读取上述文本文件的数据，具体如下：
   ```python
   file = open('abc.txt', 'r')
   data = file.readline()
   data_list = list(data)
   print(data_list)
   ```

   以上程序执行后结果为（D）。
   A. ['abcdef']
   B. ['abcdef\n']
   C. ['a', 'b', 'c', 'd', 'e', 'f']
   D. ['a', 'b', 'c', 'd', 'e', 'f', '\n']

**8. 面向对象**

1. 下列关于类的说法，错误的是（D）。
   A. 类中可以定义私有方法和属性
   B. 类方法的第一个参数是cls
   C. 实例方法的第一个参数是self
   D. 类的实例无法访问类属性
2. 下列方法中，只能由对象调用的是（B）。
   A. 类方法 B. 实例方法 C. 静态方法 D. 析构方法
3. 下列方法中，用于负责初始化属性的是（B）。
   A. __del__() B. __init__() C. __init() D. __add__()
4. 下列选项中，不属于面向对象三大重要特性的是（A）。
   A. 抽象 B. 封装 C. 继承 D. 多态
5. 请阅读下面的代码，输出结果为（D）。
   ```python
   class Test:
       count = 21
       def print_num(self):
           count = 20
           self.count += 20
           print(count)
   test= Test()
   test.print_num()
   ```

   A. 20 B. 40 C. 21 D. 41

**9. 异常**

1. 当try子句中的代码没有任何异常时，一定不会执行以下哪个子句？（B）
   A. try B. except C. else D. finally
2. 若执行代码1/0，会引发什么异常？（A）
   A. ZeroDivisionError B. NameError C. KeyError D. IndexError
3. 下列关于try-except语句的说法中，错误的是（B）。
   A. 若try子句中的代码没有出现异常，则忽略except子句中的代码
   B. 程序捕获到异常会先执行完except子句，再继续执行try子句
   C. 若执行try子句中的代码时出现异常，则会执行except子句中的代码
   D. except子句可以指定捕获的异常类
4. 阅读下面一段代码，代码运行后会出现什么异常？（B）
   ```python
   num_li = [1, 2, 3]
   print(num_li[3])
   ```

   A. SyntaxError B. IndexError C. KeyError D. NameError

**10. Python计算生态与常用库**

1. 下列选项中，不会在发布自定义库时用到的是（C）。
   A. python setup.py build B. python setup.py sdist C. python setup.py install D. 以上全部
2. 下列选项中，返回结果是时间戳的方法是（C）。
   A. time.sleep() B. time.localtime() C. time.strftime() D. time.ctime()



## 四、简答题

1. **简述Python的特点。**
开源、简单、易学、高效、可扩展、跨平台
2. **请简单介绍Python中的数据类型和数字类型。**
数据类型：字典、列表、元组、集合、字符串、数字
数字类型：整数、浮点数、复数
3. **请简述Python变量的命名规范。**
变量名只能包含字母、数字和下划线
变量名不能以数字开头
变量名不能使用Python的关键字
变量名应使用有意义的名称
4. **请简单介绍Python中的运算符。**
算术运算符：+、-、*、/、%、**、//
比较运算符：==、!=、>、<、>=、<=
逻辑运算符：and、or、not
位运算符：&、|、^、~、<<、>>
赋值运算符：=、+=、-=、*=、/=、%=、**=、//=
成员运算符：in、not in
5. **简述break和continue语句的区别。**
break语句用于跳出当前循环，执行循环后面的代码
continue语句用于跳过当前循环的剩余代码，直接进入下一次循环
6. **简述while和for语句的区别。**
while语句用于重复执行代码，直到条件不满足为止
for语句用于遍历序列中的元素，依次执行代码
7. **请简述什么是字符串。**
字符串是由字符组成的序列，用于表示文本
8. **请简述Python中格式化字符串的几种方式。**
%格式化字符串
format()方法格式化字符串
f-string格式化字符串
9. **请简述Python中字符串对齐的内置方法。**
center()方法：居中对齐
ljust()方法：左对齐
rjust()方法：右对齐
10. **列举Python中常用的组合数据类型，简单说明它们的异同。**
列表（list）：有序、可变、可以包含不同类型的元素
元组（tuple）：有序、不可变、可以包含不同类型的元素
字典（dict）：无序、可变、键值对形式存储数据
集合（set）：无序、可变、不包含重复元素
11. **简单介绍删除字典元素的几种方式。**
del语句：删除指定键值对
clear()方法：清空字典所有元素
12. **简述位置参数、关键字参数、默认参数传递的区别。**
位置参数：按参数定义的顺序传递参数
关键字参数：通过参数名传递参数
默认参数：在定义函数时为参数指定默认值，调用函数时可以不传递该参数
13. **简述函数参数混合传递的规则。**
位置参数必须在关键字参数之前传递
默认参数可以不传递，也可以在位置参数之后传递
14. **简述局部变量和全局变量的区别。**
局部变量：在函数内部定义的变量，只能在函数内部使用
全局变量：在函数外部定义的变量，在整个程序中都可以使用
15. **请简述文本文件和二进制文件的区别。**
文本文件：由字符组成的文件，每个字符占用1个字节
二进制文件：由二进制数据组成的文件，每个字节可以表示任意数据
16. **请简述读取文件3种方法read()、readline()、readlines()的区别。**
read()方法：读取整个文件内容，返回一个字符串
readline()方法：读取文件的一行内容，返回一个字符串
readlines()方法：读取整个文件内容，返回一个字符串列表，每个元素为文件的一行
17. **简述实例方法、类方法、静态方法的区别。**
实例方法：在类中定义的方法，第一个参数为self，调用时需要实例化类
类方法：在类中定义的方法，第一个参数为cls，调用时不需要实例化类
静态方法：在类中定义的方法，没有第一个参数，调用时不需要实例化类
18. **简述什么是封装、继承和多态。**
封装：将数据和方法封装在一个类中，外部只能通过类的方法来访问数据
继承：子类可以继承父类的属性和方法，子类可以添加自己的属性和方法
多态：子类可以重写父类的方法，实现不同的功能
19. **请简述3种异常类型并说明产生的原因。**
语法错误（SyntaxError）：代码不符合Python语法规则
运行时错误（RuntimeError）：代码在运行时发生错误
逻辑错误（LogicError）：代码逻辑错误，不产生异常
20. **请写出抛出异常的3种格式，并简单介绍每种格式的功能。**
raise语句：抛出指定异常
assert语句：判断条件是否为True，若为False则抛出AssertionError异常
try-except语句：捕获异常，防止程序崩溃
21. **简单列举Python计算生态覆盖的领域（至少5个）。**
数据分析、数据可视化、机器学习、深度学习、自然语言处理
22. **简述介绍Python中库、包和模块的概念。**
库（library）：一组相关的函数、类和变量的集合，用于完成特定的任务
包（package）：一组相关的模块的集合，用于组织和管理模块
模块（module）：一个Python文件，包含函数、类和变量的定义
23. **若想对两个表示时间的变量进行计算，应将时间转换为什么格式？为什么？**
将时间转换为时间戳（timestamp）格式，因为时间戳是一个浮点数，方便进行计算



## 五、编程题

1. **整数求和。输入整数n，计算1~n之和。**
n=input('请输入一个整数：')
n=int(n)
sum=0
for i in range(1,n+1):
    sum+=i
print(sum)
2. **编写程序，计算圆的直径和面积。**
import math
r=float(input('请输入圆的半径：'))
d=2*r
s=math.pi*r**2
print('圆的直径为：',d)
print('圆的面积为：',s)
3. **利用while循环输出100以内偶数。**
i=1
while i<=100:
    if i%2==0:
        print(i)
    i+=1
4. **判断用户输入的数是正数还是负数。**
num=float(input('请输入一个数：'))
if num>0:
    print('这是一个正数')
elif num<0:
    print('这是一个负数')
else:
    print('这是零')
5. **合并两个列表并降序排序。**
list1=[1,3,5,7,9]
list2=[2,4,6,8,10]
list3=list1+list2
list3.sort(reverse=True)
print(list3)
6. **统计字符串中各字母出现次数。**
str1=input('请输入一个字符串：')
str1=str1.lower()
dict1={}
for i in str1:
    if i.isalpha():
        if i in dict1:
            dict1[i]+=1
        else:
            dict1[i]=1
print(dict1)
7. **删除列表中的重复数据。**
list1=[1,2,3,4,5,1,2,3,4,5]
list1=list(set(list1))
print(list1)
8. **输出1~100中偶数之和。**
sum=0
for i in range(1,101):
    if i%2==0:
        sum+=i
print(sum)
9. **判断三个数字是否能作为边长构成三角形。**
a=float(input('请输入边长a：'))
b=float(input('请输入边长b：'))
c=float(input('请输入边长c：'))
if a+b>c and a+c>b and b+c>a:
    print('这三边可以构成三角形')
else:
    print('这三边不能构成三角形')
10. **从文件中读取数字并排序。**
file=open('num.txt','r')
data=file.readlines()
file.close()
num_list=[]
for i in data:
    num_list.append(int(i))
num_list.sort()
print(num_list)
11. **定义一个Circle类，计算周长和面积。**
import math
class Circle:
    def __init__(self,radius):
        self.radius=radius
    def perimeter(self):
        return 2*math.pi*self.radius
    def area(self):
        return math.pi*self.radius**2
12. **编写程序，计算圆的面积，若半径为负值则抛出异常。**
import math
class Circle:
    def __init__(self,radius):
        if radius<0:
            raise ValueError('半径不能为负值')
        self.radius=radius
    def area(self):
        return math.pi*self.radius**2
13. **编写程序，输入三角形三条边判断能否构成三角形，否则抛出异常。**
class Triangle:
    def __init__(self,a,b,c):
        if a+b<=c or a+c<=b or b+c<=a:
            raise ValueError('这三边不能构成三角形')
        self.a=a
        self.b=b
        self.c=c
