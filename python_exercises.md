# Python 入门练习册

## 列表、循环、条件判断与基础字符串

这些练习主要使用：变量、输入输出、`if/else`、`for`、`while`、列表和字符串。

除非题目特别说明，请先尝试自己完成，再查看参考答案或基础代码示例。

---

## 第一部分：数字与循环

### 1. 反转三位数

输入一个三位正整数，反转它的数字顺序并输出整数。反转后开头的零不保留。

```text
输入：123
输出：321

输入：900
输出：9

输入：120
输出：21
```

### 2. 计算各位数字之和

输入一个正整数，计算它各位数字的总和。

```text
输入：583
输出：16
```

### 3. 统计数字位数

输入一个正整数，统计它有几位数字。

```text
输入：583
输出：3
```

### 4. 输入数字并求和

持续输入整数，输入 `0` 时停止。输出所有已输入数字的总和；`0` 不参与求和。

```text
输入：5、3、-2、0
输出：6
```

### 5. 输入数字并求平均值

持续输入数字，输入 `-1` 时停止。输出此前输入数字的平均值；`-1` 不参与计算。如果没有输入有效数字，输出提示信息。

---

## 第二部分：列表遍历与查找

以下题目使用这个列表：

```python
numbers = [12, 35, 1, 10, 34, 1]
```

### 6. 找最大值

不使用 `max()`，使用循环找出列表中的最大值。

```text
输出：35
```

### 7. 找最小值

不使用 `min()`，使用循环找出列表中的最小值。

```text
输出：1
```

### 8. 同时找最大值和最小值

只遍历列表一次，同时找出最大值和最小值。

```text
输出：最大值 35，最小值 1
```

### 9. 查找数字是否存在

输入一个数字，使用循环判断它是否在列表中。

```text
查找：10
输出：找到
```

### 10. 顺序查找第一次出现的位置

输入一个数字，找出它第一次出现的索引；如果不存在，输出 `-1`。

```text
查找：1
输出：2
```

### 11. 统计数字出现次数

输入一个数字，统计它在列表中出现了几次。

```text
查找：1
输出：2
```

### 12. 找出第二大的不同数字

找出列表中第二大的**不同**数字。不能把重复的最大值当作第二大值。

```text
输入：[12, 35, 1, 10, 34, 1]
输出：34

输入：[8, 8, 8]
输出：不存在
```

### 13. 找出第 k 大的不同数字

输入正整数 `k`，找出列表中第 `k` 大的不同数字。如果不同数字不足 `k` 个，输出提示信息。

```text
列表：[8, 3, 8, 6, 1]
k：2
输出：6
```

---

## 第三部分：筛选、去重与统计

### 14. 筛选偶数

创建一个新列表，只包含原列表中的偶数。

```text
输入：[3, 8, 5, 2, 10]
输出：[8, 2, 10]
```

### 15. 筛选奇数

创建一个新列表，只包含原列表中的奇数。

```text
输入：[3, 8, 5, 2, 10]
输出：[3, 5]
```

### 16. 分别统计奇数和偶数

统计列表中奇数和偶数各有多少个。

```text
输入：[3, 8, 5, 2, 10]
输出：奇数 2 个，偶数 3 个
```

### 17. 去重并保留原顺序

删除重复值，但保留每个数字第一次出现时的顺序。不使用 `set()`。

```text
输入：[3, 1, 3, 2, 1, 5]
输出：[3, 1, 2, 5]
```

### 18. 分别统计正数、负数和零

```text
输入：[-2, 0, 5, -1, 0, 8]
输出：正数 2 个，负数 2 个，零 2 个
```

### 19. 计算总和与平均值

使用循环计算列表中数字的总和与平均值。列表为空时显示提示，而不是除以零。

```text
输入：[2, 4, 6]
输出：总和 12，平均值 4
```

### 20. 计算偶数之和

只把列表中的偶数相加。

```text
输入：[3, 8, 5, 2, 10]
输出：20
```

---

## 第四部分：列表排序与组合

### 21. 升序排列

不使用 `sort()` 或 `sorted()`，把列表按从小到大排列。

```text
输入：[5, 2, 8, 1]
输出：[1, 2, 5, 8]
```

### 22. 降序排列

不使用 `sort()` 或 `sorted()`，把列表按从大到小排列。

```text
输入：[5, 2, 8, 1]
输出：[8, 5, 2, 1]
```

### 23. 交错合并两个等长列表

```text
输入：[1, 2, 3] 和 ['a', 'b', 'c']
输出：[1, 'a', 2, 'b', 3, 'c']
```

### 24. 合并长度不同的列表

交替合并两个列表。一个列表先用完时，把另一个列表剩余的元素接到末尾。

```text
输入：[1, 2, 3, 4] 和 ['a', 'b']
输出：[1, 'a', 2, 'b', 3, 4]
```

### 25. 合并两个已排序列表

给定两个升序列表，将它们合并为一个仍然升序排列的新列表。

```text
输入：[1, 4, 7] 和 [2, 3, 8]
输出：[1, 2, 3, 4, 7, 8]
```

---

## 第五部分：字符串和列表

### 26. 统计字符串中的元音字母

输入一个英文字符串，统计其中 `a、e、i、o、u` 出现的次数，不区分大小写。

```text
输入："Hello World"
输出：3
```

### 27. 提取字符串中的数字字符

```text
输入："a1b23c"
输出："123"
```

### 28. 单词列表与查找

输入一行由空格分隔的单词，再输入一个要查找的单词。判断这个单词是否存在，并统计它出现的次数。

```text
输入："red blue red green"
查找："red"
输出：找到，出现 2 次
```

---

## 第六部分：综合练习

### 29. 成绩分析

持续输入成绩，输入 `-1` 时结束。结束后输出：

- 成绩人数
- 最高分和最低分
- 平均分
- 及格人数（成绩不低于 60）

如果没有输入任何成绩，显示提示信息。

### 30. 菜单式列表程序

使用列表保存整数，重复显示菜单，直到用户选择退出：

```text
1. 添加数字
2. 显示列表
3. 查找数字及出现次数
4. 显示最大值和最小值
5. 显示第二大的不同数字
6. 退出
```

列表为空时，最大值、最小值和第二大值操作应显示提示，而不能报错。

---

# 基础代码帮助示例

## 1. 输入整数

```python
number = int(input("请输入一个整数："))
print("你输入的是：", number)
```

## 2. 判断奇偶数

```python
number = int(input("请输入一个整数："))

if number % 2 == 0:
    print("偶数")
else:
    print("奇数")
```

## 3. 使用 `for` 遍历列表

```python
numbers = [12, 35, 1, 10]

for number in numbers:
    print(number)
```

## 4. 使用索引遍历列表

```python
numbers = [12, 35, 1, 10]
index = 0

while index < len(numbers):
    print("索引：", index, "数字：", numbers[index])
    index += 1
```

## 5. 累加数字

```python
numbers = [2, 4, 6]
total = 0

for number in numbers:
    total += number

print(total)  # 12
```

## 6. 计算平均值并处理空列表

```python
numbers = [2, 4, 6]

if len(numbers) == 0:
    print("列表为空，无法计算平均值")
else:
    total = 0

    for number in numbers:
        total += number

    average = total / len(numbers)
    print(average)
```

## 7. 用循环找最大值

```python
numbers = [12, 35, 1, 10]
largest = numbers[0]

for number in numbers:
    if number > largest:
        largest = number

print(largest)  # 35
```

## 8. 找第二大不同值

```python
numbers = [12, 35, 1, 10, 34, 1]
largest = numbers[0]

for number in numbers:
    if number > largest:
        largest = number

second_largest = None

for number in numbers:
    if number == largest:
        continue

    if second_largest is None or number > second_largest:
        second_largest = number

if second_largest is None:
    print("不存在第二大的不同数字")
else:
    print(second_largest)  # 34
```

## 9. 筛选偶数

```python
numbers = [3, 8, 5, 2, 10]
evens = []

for number in numbers:
    if number % 2 == 0:
        evens.append(number)

print(evens)  # [8, 2, 10]
```

## 10. 列表去重并保留原顺序

```python
numbers = [3, 1, 3, 2, 1, 5]
unique_numbers = []

for number in numbers:
    if number not in unique_numbers:
        unique_numbers.append(number)

print(unique_numbers)  # [3, 1, 2, 5]
```

## 11. 使用哨兵值结束输入

```python
numbers = []

while True:
    number = int(input("请输入数字（输入 -1 结束）："))

    if number == -1:
        break

    numbers.append(number)

print("输入的数字：", numbers)
```

## 12. 统计数字出现次数

```python
numbers = [12, 35, 1, 10, 34, 1]
target = 1
count = 0

for number in numbers:
    if number == target:
        count += 1

print(count)  # 2
```

## 13. 交错合并等长列表

```python
first = [1, 2, 3]
second = ["a", "b", "c"]
merged = []

for index in range(len(first)):
    merged.append(first[index])
    merged.append(second[index])

print(merged)  # [1, 'a', 2, 'b', 3, 'c']
```

## 14. 反转三位数

```python
number = 123

ones = number % 10
tens = (number // 10) % 10
hundreds = number // 100

reversed_number = ones * 100 + tens * 10 + hundreds

print(reversed_number)  # 321
```

例如 `900` 反转后的各位数可组成整数 `9`，因为反转后得到的字符串为 `009`，转成整数后不保留前导零。
