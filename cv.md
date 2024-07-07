# Diana Butiakova
### Front-end Developer

## Contacts
Location: Bishkek, Kyrgyzstan\
E-mail: butyakova01@gmail.com\
[Telegram](https://t.me/imbluedabudie)\
[LinkedIn](https://www.linkedin.com/in/diana-butyakova)\
[Github](https://github.com/djhsgfjk)


## About me 
I started my career as a systems analyst. Currently, I work as a JavaScript developer on a low-code platform, actively learning various web technologies. I aspire to grow into a full-fledged front-end developer.

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
### Fullstack task management application
This is a university fullstack project that represents a kanban-board with drag-and-drop lists and cards.

#### Frontend Stack:
- React
- Redux
- Axios
- Docker - for deployment

#### Backend Stack:
- Django
- Python
- Docker - for deployment

#### [Build](http://185.124.109.30:3000)
#### [Source code](github.com/djhsgfjk/task-manager-app)

### 2048 game
Simple 2048 web-game.

#### Stack:
- HTML
- CSS
- JavaScript
- WebPack

#### [Build](djhsgfjk.github.io/2048)
#### [Source code](github.com/djhsgfjk/2048/tree/main)

![2048 game](assets/2048.png)

### Bank calculator
Bank calculator with credit and deposit calculators.

#### Stack:
- HTML
- CSS
- JavaScript
- WebPack

#### [Build](djhsgfjk.github.io/bank-calculator)
#### [Source code](github.com/djhsgfjk/bank-calculator)

![Bank calculator](assets/credit-calculator.png)

## Education
### Bachelor's degree, 2023
__Kazan (Volga region) Federal University__\
Institute of Computational Mathematics and Information Technology,
Fundamental Informatics and Information Technology

## Languages
- English - Upper-intermediate
- Russian - Native