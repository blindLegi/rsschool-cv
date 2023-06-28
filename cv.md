## Aleksei Skiruha
### Front-end Developer
![It's me](https://avatars.githubusercontent.com/u/90132401?v=4)
### Contact information:
Phone: +375298380900\
Email: alekse.skiruha@gmail.com\
Telegram: @blindLegi\
Discord: Aleksei Skiruha (@blindLegi)\
[GitHub](https://github.com/blindLegi), [LinkedIn](https://www.linkedin.com/in/legi/)

---
### About me: 
Already tried to study on this course, this time the main goal is to make it all the way to stage#3 and finish it. Fast learner, diligent, patient, calm. Ready to work hard on myself, learn new technologies and continue to improve hard and soft skills.

---
### Skills:
* HTML
* CSS
* JavaScript

---
### Code example:
```
area.addEventListener('click', e => {
    if (e.target.className === 'box') {
        move % 2 === 0 ? e.target.innerHTML = xMark : e.target.innerHTML = oMark;
        move++;
        e.target.classList.add('active');
        check();
    }
})

const check = () => {
    const arr = [
        [0,1,2],
        [3,4,5],
        [6,7,8],
        [0,3,6],
        [1,4,7],
        [2,5,8],
        [0,4,8],
        [2,4,6]
    ];
    

    for(i = 0; i < arr.length; i++) {
        if (boxes[arr[i][0]].innerHTML == xMark && boxes[arr[i][1]].innerHTML == xMark && boxes[arr[i][2]].innerHTML == xMark) {
            result = 'Xs';
            prepareResult1(result);
        } else if (boxes[arr[i][0]].innerHTML == oMark && boxes[arr[i][1]].innerHTML == oMark && boxes[arr[i][2]].innerHTML == oMark) {
            result = 'Os';
            prepareResult2(result);
        } 
    }
    if (move == 9 && result === undefined) {
        result = 'Draw';
        prepareResult3(result);
    }
}
```

---
### Experience:
* [Drop-down Cards Plugin](https://jsfiddle.net/blindLegi/z9a0kop2/3/)
* [Drag and Drop](https://jsfiddle.net/blindLegi/g8apswvu/2/)
* [Slider](https://jsfiddle.net/blindLegi/2Lk51csx/1/)
* [Mini-game](https://jsfiddle.net/blindLegi/9ypq40ne/3/)
* [Aim game](https://jsfiddle.net/blindLegi/y8n4hajf/1/)
* [Tic-tac-toe](https://rolling-scopes-school.github.io/blindlegi-JSFEPRESCHOOL/tic-tac-toe/)

---
### Education:
* Belarusion National Technical University. Foundary production of ferrous and non-ferrous metals. Bachelor's degree.
* [Marathon 5 days 5 JavaScript projects.](https://result.school/products/marathon-js)
* [RSSchool JS/FE Pre-School 2022](https://app.rs.school/certificate/3497uctb)

---
### Languages:
* Russian: Native
* Belarusian: Upper-Intermediate
* English: Upper-Intermediate ([C2 according to EF Standart English Test](https://www.efset.org/cert/YzoZFf) but I had little conversational experience)