# Anton Kochetov

## Junior Frontend Developer

## Contact information:

* __City:__ Minsk
* __Phone:__ +375 44 702 02 09
* __Email:__ [ankochetov1996@gmail.com](ankochetov1996@gmail.com)
* __Telegram:__ [an_kochetov](https://t.me/an_kochetov)
* __Github:__ [Anton13602](https://github.com/Anton13602/)
* [__LinkedIn__](https://www.linkedin.com/in/anton-kochetov-by)


## About me
My goal is to become a good front-end developer. For a long time I worked as an engineer and was engaged in server configuration, access control systems and video surveillance. Now I am actively studying development in order to achieve my goal.

## Skills
* HTML5, CCS3
* JavaScript
* Git
* Preprocessor: SCSS
* Figma

## Code examples

### altERnaTIng cAsE <=> ALTerNAtiNG CaSe
Define __String.prototype.toAlternatingCase__ (or a similar function/method such as __to_alternating_case/toAlternatingCase/ToAlternatingCase__ in your selected language; see the initial solution for details) such that each lowercase letter becomes uppercase and each uppercase letter becomes lowercase. 

```JavaScript
String.prototype.toAlternatingCase = function () {
  let arr = this.split('')
  let newArr = []
  for (let i = 0; i < arr.length; i++) {
    if (arr[i].charCodeAt(0) <= 90 && arr[i].charCodeAt(0) >= 65) {
      newArr.push(arr[i].toLowerCase())
    } else {
      newArr.push(arr[i].toUpperCase())
    }
  }
  console.log(newArr.join(''))

  return newArr.join('')
}
```

## Education
* __University__: BSU
* __Faculty__: Radiophysics and computer technologies


## Languages:
* English: A2
* Russian - Native