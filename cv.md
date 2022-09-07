[#rsschool-cv](https://andtey99399.github.io/rsschool-cv/cv)

#Andrey Begashev
###Frontend Developer

#Contacts
*__Phone__: +7-(982)-307-36-77
*__E-Mail__: apururu@mail.ru
*__Telegram__: @andtey99399
*__GitHub__: [andtey99399](https://github.com/andtey99399)

#About Me
I want to dive into frontend development and become a real professional. At the moment there are several works in the portfolio, which can be found on the GitHub page. I am goal-oriented, I have good communication skills, I have a great desire to gain new experience.

#Skills
*HTML5/Pug
*CSS3/SASS
*JavaScript(ES6+, DOM, JSON)
*Gulp/Webpack
*Git
*OOP

#Code Example
###Task
Write a function, which takes a non-negative integer (seconds) as input and returns the time in a human-readable format (HH:MM:SS)

HH = hours, padded to 2 digits, range: 00 - 99
MM = minutes, padded to 2 digits, range: 00 - 59
SS = seconds, padded to 2 digits, range: 00 - 59
The maximum time never exceeds 359999 (99:59:59)

You can find some examples in the test fixtures.
###Solution
```
function humanReadable(seconds) {
  let arr = [0, 0, seconds];
  for (let i = arr.length-1; i > 0; i--) while (arr[i] > 59) { arr[i-1]++; arr[i] -= 60; }
  for (let i = 0; i < arr.length; i++) if (arr[i] < 10) arr[i] = 0 + String(arr[i]);
  return (arr[0] + ':' + arr[1] + ':' + arr[2]);
}
```

#Education
*Chelyabink State University (CSU)
    *Applied Mathematics and Computer Science
*Codewars
![Stats](https://www.codewars.com/users/andtey99399/badges/large)

#Languages
*Russian (Native)
#English (Intermediate/B1)