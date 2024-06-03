## 1. Write short notes on string methods with code examples
### *toLowerCase()
### *toUpperCase()
 ### *substring()
  ### *replace()
### *trim()
### *split()
### *slice()
### ans.1.toLowerCase() :coverts a string to lower case letter with toLowerCase() 
```js
Eg:let str="javaScript"
console.log(str.toLowerCase())
```
### 2.toUpperCase() ::coverts a string to upper case letter with toUpperCase() 
```js
Eg:let str="javaScript"
console.log(str.toUpperCase())
```
### 3.substring():substring() method extract characters between two position from a string and return the substring
```js
eg: let str="javaScript is my language"
console.log(str.subString(0,11))
```
### 4.replace():method replaces a specified value with another value in a string
```js
eg:let str="javaScript is my language"
console.log(str.replace("javaScript","js"))
```
### 5.trim():method removes whitespace from both sides of a string
```js
eg:let str="javaScript is my language"
console.log(str.trim())
```
### 6.split(): A string can be converted to an array with the split() method
```js
eg:let str="javaScript "
console.log(str.split())
```
### slice(): extreat a part of a string and returns the extracted part in a new string
```js
eg:let str="javaScript "
console.log(str.slic(0,3))
```

## 2. create a simple app that takes the users name and greets him/her after capitalizing the first letter of the users name and changing the rest of the letters into lowercase(toUpperCase().toLowerCase(),slic(),length property,string concatenation)
```js
  let username=prompt("Enter the name")
 let firstLetter=userName.slice(0,1).toUpperCase()
 let restOfTheLetters=userName.slice(1,userName.length).toLowerCase()
 let nameToDisplay=FirstLetter+restOfTheLetters alert( welcome ,${nameToDisplay})
 ```
