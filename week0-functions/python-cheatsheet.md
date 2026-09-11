# Python 函数速查表


## 输入输出

| 函数 | 作用 | 示例 |
|------|------|------|
| `input(prompt)` | 接收输入 | `name = input("Name: ")` |
| `print(*object, sep, end)` | 输出 | `print("hi", end="")` |

## 类型转换

| 函数 | 作用 | 注意 | 单词 |
|------|------|------|------|
| `int(x)` | 转整数 | 非数字会 ValueError | integer |
| `float(x)` | 转小数 | 既可以输入整数也可以输入小数 | float |
| `str(x)` | 转字符串 | | string |
| `round`  | 四舍五入，舍入到指定位数 | eg: round(nubmber[,ndigits]) | |

## 字符串方法

| 方法 | 作用 | 示例 | 释义 |
|------|------|------|------|
| `.strip()` | 去掉首尾空白 | `" hi ".strip()` → `"hi"` | 剥离 |
| `.split(sep)` | 分割成列表 | `"a,b".split(",")` → `['a','b']` | 分割 |
| `.lstrip`| 去掉左侧空白 | | |
| `.rsrtip`| 去掉右侧空白 | | |
| `.title()` | 每个词首字母大写 | `"hello world".title()` |
| `.capitalise()` | 整个字符串首字母大写 | | |

## 其他
| 函数 | 全拼 | 作用 | 示例|
|------|------|------|------|
| def | define | 定义自定义函数 | |
| pow | | 求数字幂| pow(n,2) |
| if | | 用于条件 | if score >=90: |
| elif | else if | 类似于if的必要假言判断，意思大概是“否则” | |
| and | | 同时满足多个条件要求 | if score >=90 and <= 100 |
| else | | 如果都不是那最终就是 | | |
| or | | 一次性问多个问题，减少if函数调用 | |
