# SERHII OLSHANSKYI

## CONTACTS

Cities of residence: Lozova Kharkiv region Ukraine\
Phone: 066-222-84-70\
E-Mail: <seven8959@gmail.com>\
[Linkedin](https://www.linkedin.com/in/serhii-olshanskyi-1230801b2/)\
[Facebook](https://www.facebook.com/profile.php?id=100002558855107)\
[GitHub](https://github.com/seven8959)

## ABOUT ME

I found out about such profession as Front end developer in December, 2019
I got interested in this speciality.

I have always been interested in working with computers, but I had never gone into details before 2019.
Some spare time appeared in summer and I started to study. I began with reading the professional literature, trying to make layouts, watching educational videos.
 But I understood that the themes were becoming harder and it was better to take a class.
 
During some time I was looking for appropriate online courses. I considered only online courses as I live in a little town and I don’t have offline IT courses here.
Eventually,  I chose UKRAINIAN IT_SCHOOL. It was awesome. I learned a lot of useful and interesting information and attended lessons with great pleasure.
After Front end courses at UKRAINIAN IT_SCHOOL I decided that I also need to gain knowledge in JavaScript. And immediately enrolled in the course at Hillel school. I got a certificate with a “very good” mark.

It is really fascinating, when you get a great result made of code. I consider it as an art. 
I am not going to stop and I plan to study further, to develop my skills and reach my goals.

## SKILLS

* *Layout*
  * HTML-5
  * CSS-3
  * LESS
  * Responce
  * Bootstrap
* *Prgramming*  
  * JavaScript
  * ES5
  * ES6
  * DOM
  * jQuery
  * TypeScript 
* *Server*
  * Node.js
  * Express.js
  * MongoDB
  * AJAX
* *Other*
  * Git
  * Webpack   

## CODE EXAMPLES

***CSS***

    .baner .scroll_arrow:after {
      content: "";
      position: absolute;
      left: 35%;
      top: 25%;
      width: 13px;
      height: 13px;
      border-top: 2px solid #ffffff;
      border-left: 2px solid #ffffff;
      transform: rotate(225deg);
      transition: border-color 0.6s linear;
      -webkit-animation: arrow 1.5s linear infinite;
      animation: arrow 1.5s linear infinite;
    }
    
***Parallax in `js`***

```
window.addEventListener('scroll', function () {
    let st = window.scrollY;

    let elBaner = document.querySelector('.baner_text');
    let elArrow = document.querySelector('.scroll_arrow');

    elBaner.style.transform = `translateY(${st / 3}%)`;
    elArrow.style.transform = `translateY(${st / 4}%)`;
});
```

