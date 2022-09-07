# Kirill Prakhov

## Junior Frontend Developer
--------------------------------------------------

## Contacts: 

* *+79603588375*
* *kirya_prahov@mail.ru*
* *tg: mantikora0*
-------------------------------------

## About me: 
### *Currenlty im living in Russia, Balakovo. Not so long ago I studied to be a lawyer,*
### *but now I passed, because it's not for me. Now i trying my best in programming.*

------------------------------------------------

## Hard Skills: 
* **HTML**
* **CSS**
* **JavaScript**
* **SAAS**
* **React**
* **BEM**
* **Git**

-------------------------------------------------
## My English:
### *Its not so good how it can be, but im trying. Now its around A2-B1 i think. I have no speaking practice, so my speech is bad*

----------------------------------------------------

## Code example:

```
var uniqueInOrder = function (iterable) {
    let arr = iterable
    arr = typeof (iterable) === "object" ? arr.join("").split("").map(function (item) {
        let number = parseInt(item);
        return isNaN(number) ? item : number;
    }) : arr.split("");
    console.log(arr)
    let newarr = []
    for (let i in arr) {
        if (arr[i] != arr[i - 1]) {
            newarr.push(arr[i])
        }
    }
    return newarr

}
```

