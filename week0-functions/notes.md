# 9月10日学习

## 学习进度
- lecture0 前一小时

## 一些定义
- Python：interpreter，是将英语或其他语言转译成计算机语言0or1的转译器.
- 编程工具：理论上任何一个文本编辑器都可以，课程中使用的是vs code.
- function：Python中预先准备好的可套用的函数工具（大概）
- argument：实参
- parameter:形参（9.10还不理解有什么区别）
- side effect：副作用
- return value：返回值
- assignment：赋值
- comment：注释（#）
- pseudocode：伪代码
- string：字符串

## 一些tips
- “#”后跟注释，在编程中属于伪代码（pseudocode），作用是提示自己下一步动作、方便回顾、 to-do list.
- 善用 docs.python.org，可以找到有帮助的函数.
- 双引号和单引号在编程中本身没区别，但在编写过程中尽量保持一致，更换单双引号是为了区分.
- 一个问题可以用多种编程方法解决，不同方法涉及代码美观度、可视性以及便于debug的考量，没有正确答案，选择适合自己的、逻辑能够自洽的方法进行编程即可。
- 调用多个函数的方法（类似数学）：1.用“.”衔接 2.用括号区分从内至外的函数 3. 用“=” 来赋值（可以理解为将等号右边的函数要求统一至等号左边）

  # 9月11日学习

  ## 学习进度
  - lecture0 看完
  - lecture1 前40分钟
 
  ## 一些概念
  - nest：嵌套
  - ：：冒号本身，非常重要，Python中不可省略
  -  （）：用于接收和输入参数
  -  scope：作用域，意思是变量只存在于定义的上下文之中

  - ==: 真正的等于
  - >=: 大于等于（其余同理）
  - %： 模运算，用来求相除的余数
 
  ## 实操的几个问题

  ### 数字比大小
  ```python
  x = int( input"What's x?" )
  y = int( input"What's y?" )

  > 法一：
  if x > y, input("x is greater than y.”)
  if x < y, input("x is less than y." )
  if x = y, input("x is equal to y." )

  > 法二（引入elif函数）：
  if x > y, input("x is greater than y.”)
  ----elif x < y, input("x is less than y." )
  ----elif x = y, input("x is equal to y." )

  > 法三（引入else函数）：
  if x > y, input("x is greater than y.”)
  ----elif x < y, input("x is less than y." )
  ----else：
  #具体是不是这样我记不清了orz明天中午再修改
  ```

  ### 给学生排成绩
  ```python
  score(int(input"what's your score?)
  > 法一（引入and函数）：
  if score >= 90 and <= 100:
  ----print("A")
  ----elif score >=80 and <= 90
  ----print("B")
  ----else:
  ----print("F")

  > 法二（合并思想）：
  if 90 <= score <= 100 :
  ----print("A")


  > 法三（引入elif函数）：
   if score >= 90
   ----print("A")
   ----elif score >=80

  > 错误示范：全用if没有设置上下限保证互斥性，就会把abcde全部输出。
  #明天再补。。。
  ```

  ### calculator(整数小数约数加减法）
  ```python
   x = int( input"What's x?" )
   y = int( input"What's y?" )

   > 法一：
  print( round ( x + y ))

   > 法二：
   z = round( x + y )
   print ( z )
   #用字符串表示应该是 print( f"{z}")
   #以及想用comma来分割数字增加可视性，实操如下：print( f"{z:,}")
   #但为什么是在花括号内，z的后面加一个冒号和逗号？这里逗号应该不做函数的分割，应该就是数字分割的意思，但我不太明白冒号的用法，明天查一下（9.11）

   > 指定余几位小数：
   1.print( "{ z:.2}"
   2.print(f"{z:.2f}")
  #明天（9.12）补一下，，，今天困炸了
  ```
  ### 奇偶数判断
  
  ```python
  > 法一：
  if x % 2 == 0 :
  ----print"even"
  else:
  ----print"odd"
  #mingtianjixukan
  ```
  
  
