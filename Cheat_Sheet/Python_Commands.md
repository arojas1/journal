## Python Commands


```python
print ("Hello, world!")
```
```python
flowers = ['rose', 'violet', 'buttercup']

print(flowers)

print(flowers[0])

print(flowers[1:3])
```
```python
for flower in flowers:
    print("I like smelling nice things.")
    print("My favorite flower is the " + flower)
```
```python
weather = input('What is the weather today?')

if weather == 'cold':
    print("Wear your wooly muffler")
elif weather == 'rainy':
    print ('Bring your brolly')
else:
    print("I don't know what you should do, I'm just a little program")
```
```python
import random

inspirations = ['You can do it!', 
    'You will not go to GitHELL today!', 
    'Shoot for the moon!']

pick = random.choice(inspirations)

print(pick)
```
```python
import info #file_name
```
```python
type(info) #gives type of file
```
```python
dir(info) #director of the file name given
```
```python
import requests
response = requests.get('URL')
type(response)
dir(response)
text = response.text
type(text)
```

[Back to Cheat Sheet](cheat_sheet.md)