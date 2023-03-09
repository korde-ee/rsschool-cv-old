# Elena Korde

![Elena Korde](/ElenaKorde.jpg "Elena Korde")

## Contact information

**e-mail**: ekorde@gmail.com

**Phone**: +381616327922

## About me

I want to be able to work for pleasure in any format of cooperation (remote work is preferable).

## Skills

* HTML, CSS
* C#, Phyton
* php, MySQL
* Git, GitHub
* Visual Studio Code

## Code example

A natural degree k is given.

Randomly generate a list of coefficients (values from -100 to 100)
polynomial and write to the file a polynomial of degree k
k - the maximum degree of the polynomial, the next degree of the next polynomial is 1 less and so on until zero
The coefficients are placed by random, therefore, with a coefficient of 0, we simply skip this iteration of the degree

Example:

k=2 -> 2x² + 4x + 5 = 0 or x² + 5 = 0 or 10x² = 0

```
k = int(input("Введите число: "))

listNew = [random.randint(-100, 100) for i in range(k + 1)]
print(listNew)

myNewList = []

for i in range(k, -1, -1):
    if listNew[i] != 0:
        if i == 0:
            myNewList.append(str(listNew[i]))
        elif i == 1:
            myNewList.append(str(listNew[i]) + "*x")
        else:
            myNewList.append(str(listNew[i]) + "*x" + "^" + str(i))
print(myNewList)

newString = ""
for i in myNewList:
    newString += str(i) + " "

l = len(newString)
removeLast = newString[:l-1]

removeLast = removeLast.replace(' ', ' + ')
removeLast = removeLast.replace('+ -', '- ')

removeLast = ''.join((removeLast, " = 0"))
print(removeLast)
```
## Experience

5 years as a webmaster. Creation of websites, online stores.

## Curses

GeekBrains - Web development

## Languages
English - intermediate B1-B2

![English - intermediate](/english_level_new.png "English level")

Russian - Native
