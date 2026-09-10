# Python 函数速查表


## 输入输出

| 函数 | 作用 | 示例 |
|------|------|------|
| `input(prompt)` | 接收输入 | `name = input("Name: ")` |
| `print(*obj, sep, end)` | 输出 | `print("hi", end="")` |

## 类型转换

| 函数 | 作用 | 注意 | 单词 |
|------|------|------|------|
| `int(x)` | 转整数 | 非数字会 ValueError | integer |
| `float(x)` | 转小数 | | float |
| `str(x)` | 转字符串 | | string |

## 字符串方法

| 方法 | 作用 | 示例 | 释义 |
|------|------|------|------|
| `.strip()` | 去掉首尾空白 | `" hi ".strip()` → `"hi"` | 剥离 |
| `.split(sep)` | 分割成列表 | `"a,b".split(",")` → `['a','b']` | 分割 |
| `.lower()` | 转小写 | `"AB".lower()` → `"ab"` |
| `.upper()` | 转大写 | |
| `.title()` | 每个词首字母大写 | `"hello world".title()` |
| `.capitalise()` | 整个字符串首字母大写 | | |
| `.replace(a, b)` | 替换 | `"cat".replace("c","b")` |

## 列表方法

| 方法 | 作用 |
|------|------|
| `.append(x)` | 末尾添加 |
| `.insert(i, x)` | 指定位置插入 |
| `.remove(x)` | 删除第一个匹配项 |
| `.pop(i)` | 删除并返回指定位置 |
| `.sort()` | 原地排序 |
| `len(lst)` | 长度 |

## 字典方法

| 方法 | 作用 |
|------|------|
| `.keys()` | 所有键 |
| `.values()` | 所有值 |
| `.items()` | 键值对 |
| `.get(k, default)` | 安全取值 |

## 内置函数

| 函数 | 作用 |
|------|------|
| `len(x)` | 长度 |
| `range(a, b, step)` | 数字序列 |
| `sum(iterable)` | 求和 |
| `max()` / `min()` | 最大/最小 |
| `sorted(iterable)` | 返回排序后的新列表 |
| `enumerate(iterable)` | 带索引遍历 |
| `zip(a, b)` | 并行遍历 |
