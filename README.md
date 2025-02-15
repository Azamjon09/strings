# string![Screenshot 2025-02-15 004133](https://github.com/user-attachments/assets/fd092b6d-9723-466f-be3b-d7cb9819fbd9)
1. Сохтани сатрҳо

Метавонед сатрҳоро бо истифода аз нохунакҳо ("", '', ё ` `) эҷод кунед:


2. Хосиятҳои асосии String

length – дарозии сатрро бармегардонад:



3. Методҳои муфид барои кор бо сатрҳо

| Метод | Т
![Screenshot 2025-02-15 004433](https://github.com/user-attachments/assets/0ad5ae8f-8b36-40b6-9552-cbe5c66f745e)

1. Методҳои дастрасӣ ба сатр

✅ length – дарозии сатрро бармегардонад:

let text = "Салом";
console.log(text.length);  // 5

✅ charAt(index) – гирифтани ҳарф аз индекси муайян:

let str = "JavaScript";
console.log(str.charAt(0));  // "J"
console.log(str.charAt(4));  // "S"

✅ at(index) – гирифтани ҳарф бо дастгирии индексҳои манфӣ:

let str = "Салом";
console.log(str.at(-1));  // "м"


---

2. Методҳои ҷустуҷӯ дар сатр

✅ indexOf(substring) – ёфтани индекси бори аввал пайдошавии калима:

let str = "Салом ҷаҳон!";
console.log(str.indexOf("ҷаҳон"));  // 6
console.log(str.indexOf("о"));  // 2

✅ lastIndexOf(substring) – ёфтани индекси охирини пайдошавии калима:

let str = "Салом ҷаҳон, ҷаҳон!";
console.log(str.lastIndexOf("ҷаҳон"));  // 13

✅ includes(substring) – санҷидани мавҷудияти як матн дар сатр (бармегардонад true ё false):

let text = "Ман барномасоз ҳастам";
console.log(text.includes("барномасоз"));  // true
console.log(text.includes("JavaScript"));  // false

✅ startsWith(substring) – санҷидани оё сатр бо матни муайян оғоз мешавад:

let str = "Салом, дунё!";
console.log(str.startsWith("Салом"));  // true
console.log(str.startsWith("дунё"));  // false

✅ endsWith(substring) – санҷидани оё сатр бо матни муайян анҷом меёбад:

console.log(str.endsWith("дунё!"));  // true


---

3. Методҳои тағйир додани сатр

✅ toUpperCase() – табдил додани ҳамаи ҳарфҳо ба калон:

let text = "салом";
console.log(text.toUpperCase());  // "САЛОМ"

✅ toLowerCase() – табдил додани ҳамаи ҳарфҳо ба хурд:

let text = "САЛОМ";
console.log(text.toLowerCase());  // "салом"

✅ trim() – тоза кардани фосилаҳо аз аввал ва охири сатр:

let text = "  салом  ";
console.log(text.trim());  // "салом"

✅ replace(oldText, newText) – иваз кардани матн дар сатр:

let str = "Салом дунё!";
console.log(str.replace("дунё", "ҷаҳон"));  // "Салом ҷаҳон!"

✅ repeat(n) – такрор кардани сатр n маротиба:

let word = "JavaScript ";
console.log(word.repeat(3));  
// "JavaScript JavaScript JavaScript "


---

4. Методҳои пора кардани сатр

✅ slice(start, end) – буридани қисми муайян аз сатр:

let text = "Барномасозӣ";
console.log(text.slice(0, 6));  // "Барнома"
console.log(text.slice(-4));  // "созӣ"

✅ substring(start, end) – монанди slice(), вале индекси манфиро қабул намекунад:

console.log(text.substring(0, 6));  // "Барнома"

✅ split(separator) – тақсим кардани сатр ба массив:

let sentence = "Ман барномасоз ҳастам";
let words = sentence.split(" ");  
console.log(words);  // ["Ман", "барномасоз", "ҳастам"]


---

![Screenshot 2025-02-15 004629](https://github.com/user-attachments/assets/dddcf792-c54f-4ccc-bfde-01a7cc503b2c)

![Screenshot 2025-02-15 005020](https://github.com/user-attachments/assets/e765e03f-639c-417e-8515-8d9905710992)



