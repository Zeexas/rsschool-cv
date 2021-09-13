# Valeriy Li
---

#### Contacts:

Mobile: +998 99 050-2099
E-mail: lee_hobb@rambler.ru
[LinkedIn](https://www.linkedin.com/in/zeexas)

---

#### Summary:


---

#### Skills:

* HTML5, CSS3
* JavaScript
* Vue.js, jQuery
* Git, Github
* SQL
* VS Code

---

#### Code example

Some numbers have funny properties. For example:
89 --> 8¹ + 9² = 89 * 1
695 --> 6² + 9³ + 5⁴= 1390 = 695 * 2
46288 --> 4³ + 6⁴+ 2⁵ + 8⁶ + 8⁷ = 2360688 = 46288 * 51

Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p
we want to find a positive integer k, if it exists, such as the sum of the digits of n taken to the successive powers of p is equal to k * n.
In other words:
Is there an integer k such as : (a ^ p + b ^ (p+1) + c ^(p+2) + d ^ (p+3) + ...) = n * k
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

---

#### Experience



---

#### Education

Front-end Development Track, Data Analysis Track ([_Udacity_](https://www.udacity.com/))
Responsive Web Design ([_freeCodeCamp_](https://www.freecodecamp.org/))
MBA, Accounting and Finance (_KIMEP University_, Almaty, Kazakhstan)
Bachelor in Economics (_Tashkent State University of Economics_, Tashkent, Uzbekistan)

---

#### English

B2 (according to EPAM training center English test)
