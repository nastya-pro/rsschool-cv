1. Anastasia Prokofieva
1. Contacts for communication:
* E-mail address: anast.ars@yandex.ru
* Discort username:Anarsia#3408
1. I want to study and understand JavaScript. My main goal is to find a good interesting job. I have little programming experience. But programmers do very hard work and are like magicians. I always carefully study new topics and tasks and ask clarifying questions if something is not clear. I enjoy learning new things.
1. HTML5, CSS3, JavaScript, C
1. Sample code
```const xMax=1;
const xMin=0;
const n=5;

let stdio = require('stdio');
stdio.ask('Пожалуйста введите x в диапазоне от ' + xMin + ' до ' + xMax)
    .then(x =>
        stdio.ask('Пожалуйста введите значение дисперсии').then(sigma => calculate(x, sigma))
    );

function calculate(x, s) {
    const vertexes = [];
    for (let i = 0; i < n; i++) {
        vertexes[i] = (xMax - xMin) * i / (n - 1)
    }

    const funs = vertexes.map(mu => createGaussian(mu, s));
    const ys = funs.map(f => f(x));
    ys.forEach(y => console.log(y));
}

function createGaussian(mu, sigma) {
    return function(x) {
        return Math.exp(-(Math.pow(x-mu, 2)/(2*(sigma*sigma))));
    }
} 
```
1. The institute performed laboratory work. We solved math problems, made websites, worked with databases.
[Example of work](https://github.com/nastya-pro/WebProgramLab1)
1. Bachelor of Agrotechnological University and student of the Radiotechnological University
1. English level A1
