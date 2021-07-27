1)
Fix the code to get the largest of three.

Ans)
aa = (f, s, t) => {
  if (f > s && f > t) {
    console.log(f);
  } else if (s > f && s > t) {
    console.log(s);
  } else {
    console.log(t);
  }
};
aa(1, 5, 3);

2)let n = [1, 2, 3];
console.log(add(n));
function add(n) {
  let sum = 0;
  for (var i = 0; i < n.length; i++) {
    sum += n[i];
  }
  return sum;

3)
let n = [1, 2, 3];

(function add(n) {
  let sum = 0;
  for (var i = 0; i < n.length; i++) {
    sum += n[i];
  }
  console.log(sum);
})(n);


4)
 let str = " i am a string";

var titleCaps = function (str) {
  str = str.toLowerCase().split(" ");
  for (var i = 0; i < str.length; i++) {
    str[i] = str[i].charAt(0).toUpperCase() + str[i].slice(1);
  }
  return str.join(" ");
};
console.log(titleCaps(str));

5)
var val = [2, 3, 4, 5];
var primeNum = function (num) {
  num.map((number) => {
    for (let i = 2; i < number; i++) {
      if (number % i === 0) {
        let index = num.indexOf(number);
        return num.splice(index, 1);
      }
    }
  });

  return num;
};
console.log(primeNum(val));

6)

