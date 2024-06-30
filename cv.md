# Diana Butiakova

## Contacts
Location: Bishkek, Kyrgyzstan\
E-mail: butyakova01@gmail.com\
[Telegram](https://t.me/imbluedabudie)\
[LinkedIn](https://www.linkedin.com/in/diana-butyakova)\
[Github](https://github.com/djhsgfjk)


## About me 
I started my career as a systems analyst. Currently, I work as a JavaScript developer, actively learning various web technologies. I aspire to grow into a full-fledged front-end developer.

## Skills 
- HTML
- CSS
- JavaScript
- WebPack
- React
- Fetch API / Axios
- Redux
- Git
- Docker
- Figma

## Code Example
```
'use strict';
const Vector = class{
  
  constructor(arr) {
    this.vector = arr;  
  };
  
  toString() {
    return '(' + this.vector.join(',') + ')';
  };
  
  add(val) {
    if (this.vector.length !== val.vector.length)
       throw new Error();
    return new Vector(this.vector.map((x, i) => x + val.vector[i]));
  };
  
  subtract(val) {
    if (this.vector.length !== val.vector.length)
       throw new Error();
    return new Vector(this.vector.map((x, i) => x - val.vector[i]));
  };
  
  dot(val) {
    if (this.vector.length !== val.vector.length)
       throw new Error();
    return this.vector.reduce((preV, curV, i) => preV + curV * val.vector[i], 0);
  };
  
  norm() {
    return Math.sqrt(this.vector.reduce((preV, curV, i) => preV + Math.pow(curV, 2), 0));
  };
  
  equals(val) {
    return this.vector.toString() === val.vector.toString();
  };
}
```

## Experience
Junior Dev может перечислить учебные проекты с указанием использованных навыков и ссылками на исходный код.

## Education
(включая пройденные курсы и тренинги)

## Languages
(уровень английского языка, если была языковая практика, расскажите о ней)