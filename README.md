# Js-lesson-2
Js lesson 2
____
```node
let str = "String 1"   // undefined
str                    // "String 1"
str.length             //  8
"Hello js!".length     //  9
str[0]                 // "S"
str[str.length - 1]    // "1"
str.slice(1)           // "tring 1"
str.slice(1,3)         // "tr"
str.toLowerCase()      // "string 1"
console.log(str)       // "String 1" !!!
str.toUpperCase()      // "STRING 1"
console.log(str)       // "String 1" !!!
```
____

```node
let text = "   hElLO jS!    "
text.length                      // 16
text.trim()                      // "hELLO jS!"
                                            
let str1 = text.toLowerCase().trim()          // "hello js!"
str1  = str1[0].toUpperCase() + str1.slice(1)

console.log(str1)                // "Hello js!"
```



                              



