## 1. Specify on python have negative

reverse text example 'hello' -> olleh

### Code
```python
text = "Hello Baby""
reverseText = ""
for index in range (1,len(text)+1):
    reverseText += text[index]
    print(reverseText)
```
Output: ybaB olleH
## 2. Simple Reverse string 
reverse text example 'hello' -> olleh 

### Code
```python
text == "Hello Baby"'

lastIndex = len(text) - 1
reverseText = ""

for index in range(len(text)):
    reverseText += text[lestIndex - index]
print(reverseText)
```
Output: ybaB olleH
## 3. find index Odd number of the list

Find Odd index exaple arr=[1,2,3,4] -> newArr=[0,2]
### Code
```python
arr = [5,7,8,4,3]

indexOfOdd = []
for i in range(len(arr)):
    if arr[i] % 2 == 1:
        indexOfOdd.append(i)
print(indexOfOdd)
```
Output: indexOfOdd=[0, 1, 4]
## 4. find average of number in list

### Code
```python
arr = [5,7,8,4,3]
average = 0
sum=0
for value in arr:
    sum += value
average = sum / len(arr)

print(average)
```

## 5. Find Name of array dictionary
Find name of Dictionary exaple arr =[
     {'name':'king', 'age':20}
     {'name':'Phat', 'age':19}
     ] -> ['king','Phat']
### Code
```python

arr = [
    {'name': 'bopha', 'age':18},
    {'name': 'thida', 'age':12},
    {'name': 'kanha', 'age':16},
] 
for dics in arr:
    print(dics['name'])
```
Output: bopha thida kanha
## 6. Sum number in list
```python
arr = [5,7,8,4,3]
sum = 0
for value in arr:
    sum += value
print(sum)
```
## 7. Find even number in list
```python
arr = [5,7,8,4,3]

for value in arr:
    if value % 2 == 0:
        print(value)
```
## 8. Find minimum in the list
```python
arr = [10,40,20,4,3]

min = arr[0]
for value in arr:
    if value < min:
        min = value
print(min)
```
## 9. Move one step to right
```Python
arr = [0,0,1,0,0]
isFound = Flase
for i in range(len(arr)-1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i+1]=1
        isFound = True
print(arr)
```
## 10. Move one step to left
```Python

arr = [0,0,1,0,0]
isFound = Flase
for i in range(len(arr)-1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i-1]=1
        isFound = True
print(arr)
```
## 11. Find Maximam number
```Python

arr = [10,40,20,4,3]
max = arr[0]
for value in arr:
    if value > max:
        max = value
print(max)
```
## 12. Sum value row in Array 2D
```Python 
arr2D = [
    [1,2,3],
    [4,5,6],
    [7,8,9],
]
sum = 0
arr = []
for row in range(len(arr2D)):
    for col in range(len(arr2D[row])):
        sum += arr2D[row][col]
    arr.append(sum)
    sum = 0
print(arr)
```

