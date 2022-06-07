# **Khomich Sergei**

---

## \* **Contacts**:

- Discord: Сергей(@KhomichSergei)
- E-mail: s.khomich1986@gmail.com
- Tel: +375447596067
- GitHub: khomichsergei

---

## **Summary**:

Very responsible and executive. I like to be creative and create something new. I want to become a great WEB developer.

---

## **Skills**:

- HTML
- CSS/SCSS
- JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript, ES6+, DOM, JSON, AJAX)

---

## **Code example**:

```
let enterStr = prompt("Введите строку");
console.log (enterStr);
function searchVowels(str) {
  let vowelsList='аеёиоуыэюя'.split('');
  let count = 0;
  str.toLowerCase().split('').forEach(function(e){
  if(vowelsList.indexOf(e) !== -1){
   count++;
  }
  });
return count;
}
function searchVowels2(str) {
  let vowelsList='аеёиоуыэюя'.split('');

  let count = str.toLowerCase().split('').filter( element => vowelsList.includes(element)).length;
    return count;

}
function searchVowels3(str) {
   let strArr=str.toLowerCase().split('');
   let vowelsList="аеёиоуыэюя";

   let n = strArr.reduce( (summa, value) => {
      if (vowelsList.indexOf (value) !==-1) {
         summa++;
      }
      return summa;
   }, 0); // Запускаем reduce с нулевой суммой
   return n;

}
console.log (searchVowels(enterStr));
console.log (searchVowels2(enterStr));
console.log (searchVowels3(enterStr));
```

---

## \* **Education:**

- Gomel State University

* accounting, analysis and audit in banks

- IT Academy, Minsk

* HTML&CSS
* Java Script

---

## \* **Experience:**

- Belgosstrakh Insurance Company

* department of analysis and planning
* department of business risk insurance

- Sberbank

* department of crediting legal entities

- Technobank

* ## collateral analysis department

## \* **Languages:**

- English A2
- Russian native
