# CH 3.各種資料型態的許多運算
  - 整數的各種運算 [參考範例](https://www.w3schools.com/python/python_numbers.asp)  [Python Operators](https://www.w3schools.com/python/python_operators.asp)
  - 字串str的各種運算 [參考範例](https://www.w3schools.com/python/python_strings.asp)
  - 列表list的各種運算  [參考範例](https://www.w3schools.com/python/python_lists.asp)
  - 字典dict的各種運算 [參考範例](https://www.w3schools.com/python/python_dictionaries.asp)

## 整數的各種運算 [參考範例](https://www.w3schools.com/python/python_numbers.asp)  [Python Operators](https://www.w3schools.com/python/python_operators.asp)

```python
a = "Hello"
print(a)

```

```python
x = 1
y = 35656222554887711
z = -3255522

print(type(x))
print(type(y))
print(type(z))

```

```python
print(10 + 5)

```

```python
x = 35e3
y = 12E4
z = -87.7e100

print(type(x))
print(type(y))
print(type(z))

```

## 字串str的各種運算 [資料來源](https://www.w3schools.com/python/python_strings.asp)
```python
# Multiline Strings
# You can assign a multiline string to a variable by using three quotes:

a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```

```python
a = "Hello, World!"
print(a[0:7])
```

```python
for x in "banana":
  print(x)
```

```python
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)

```

## 列表list的各種運算  [參考範例](https://www.w3schools.com/python/python_lists.asp)

```python
thislist = ["apple", "banana", "cherry"]
print(thislist)

```

```python
thislist = ["apple", "banana", "cherry", "apple", "cherry"]
print(thislist)

```

```python
mylist = ["apple", "banana", "cherry"]

```

```python
list1 = ["apple", "banana", "cherry"]
list2 = [1, 5, 7, 9, 3]
list3 = [True, False, False]

```
```python
list1 = ["abc", 34, True, 40, "male"]

```
## 字典dict的各種運算 [參考範例](https://www.w3schools.com/python/python_dictionaries.asp)

```python
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}

```

```python
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)

```



```python
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict["brand"])

```

```python
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964,
  "year": 2020
}
print(thisdict)

```



```python
thisdict = {
  "brand": "Ford",
  "electric": False,
  "year": 1964,
  "colors": ["red", "white", "blue"]
}


```

```python
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(type(thisdict))


```






