# Valeriy Li
---

#### Contacts:
---
Mobile: +998 99 050-2099
E-mail: lee_hobb@rambler.ru
[LinkedIn](https://www.linkedin.com/in/zeexas)


#### Summary:
---
For more than 11 years in Finance I gained invaluable experience improving not only hard skills, but also soft skills working in teams and individually. At previous company I worked my way up from a financial manager to a head of Financial Department, but my love of using Excel functions led me here.
Hope my experience will help me in creating user-friendly products.

#### Skills:
---
* HTML5, CSS3
* JavaScript
* Vue.js, jQuery
* Git, Github
* SQL
* VS Code


#### Code example:
---
**Codewars Kata**
Some numbers have funny properties. For example:
89 --> 8¹ + 9² = 89 * 1
695 --> 6² + 9³ + 5⁴= 1390 = 695 * 2
46288 --> 4³ + 6⁴+ 2⁵ + 8⁶ + 8⁷ = 2360688 = 46288 * 51

Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p we want to find a positive integer k, if it exists, such as the sum of the digits of n taken to the successive powers of p is equal to k * n.
_In other words:_
Is there an integer k such as : (a ^ p + b ^ (p+1) + c ^(p+2) + d ^ (p+3) + ...) = n * k.
If it is the case we will return k, if not return -1.

Note: n and p will always be given as strictly positive integers.

```
function digPow(n, p){
  let powSum = 0;
  for (let i = 0; i < n.toString().length; i++) {
    powSum += (+n.toString()[i])**(p+i)
  }
  if (powSum % n === 0) {
    return powSum / n;
  } else {
    return -1;
  }
}
```


#### My projects
---
* [L'Occitane in Uzbekistan](https://zeexas.github.io/Loccitane_uz/Loccitane_Uz.html) (Vue.js, jQuery, https://github.com/Zeexas/Loccitane_uz)
* [Bank Calculator](https://zeexas.github.io/Bank_Calculator/Calculator.html) (Vanilla.js, https://github.com/Zeexas/Bank_Calculator)
* [15 Puzzle](https://zeexas.github.io/15_puzzle/index.html) (Vue.js, https://github.com/Zeexas/15_puzzle)
* [Bulls and Cows](https://zeexas.github.io/Bulls_Cows/index.html) (Vue.js, https://github.com/Zeexas/Bulls_Cows)


#### Education
---
Front-end Development Track, Data Analysis Track (_[Udacity](https://www.udacity.com/)_)
Responsive Web Design (_[freeCodeCamp](https://www.freecodecamp.org/)_)
MBA, Accounting and Finance (_KIMEP University_, Almaty, Kazakhstan)
Bachelor in Economics (_Tashkent State University of Economics_, Tashkent, Uzbekistan)


#### English
---
B2 (according to EPAM training center English test)
