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
console.log(text.length);  

✅ charAt(index) – гирифтани ҳарф аз индекси муайян:

let str = "JavaScript";
console.log(str.charAt(0));  
console.log(str.charAt(4));  

✅ at(index) – гирифтани ҳарф бо дастгирии индексҳои манфӣ:

let str = "Салом";
console.log(str.at(-1)); 


---

2. Методҳои ҷустуҷӯ дар сатр

✅ indexOf(substring) – ёфтани индекси бори аввал пайдошавии калима:

let str = "Салом ҷаҳон!";
console.log(str.indexOf("ҷаҳон"));  
console.log(str.indexOf("о")); 

✅ lastIndexOf(substring) – ёфтани индекси охирини пайдошавии калима:

let str = "Салом ҷаҳон, ҷаҳон!";
console.log(str.lastIndexOf("ҷаҳон"));  

✅ includes(substring) – санҷидани мавҷудияти як матн дар сатр (бармегардонад true ё false):

let text = "Ман барномасоз ҳастам";
console.log(text.includes("барномасоз"));  // true
console.log(text.includes("JavaScript"));  // false

✅ startsWith(substring) – санҷидани оё сатр бо матни муайян оғоз мешавад:

let str = "Салом, дунё!";
console.log(str.startsWith("Салом")); 
console.log(str.startsWith("дунё")); 

✅ endsWith(substring) – санҷидани оё сатр бо матни муайян анҷом меёбад:

console.log(str.endsWith("дунё!")); 

---

3. Методҳои тағйир додани сатр

✅ toUpperCase() – табдил додани ҳамаи ҳарфҳо ба калон:

let text = "салом";
console.log(text.toUpperCase());

✅ toLowerCase() – табдил додани ҳамаи ҳарфҳо ба хурд:

let text = "САЛОМ";
console.log(text.toLowerCase());

✅ trim() – тоза кардани фосилаҳо аз аввал ва охири сатр:

let text = "  салом  ";
console.log(text.trim());

✅ replace(oldText, newText) – иваз кардани матн дар сатр:

let str = "Салом дунё!";
console.log(str.replace("дунё", "ҷаҳон"));

✅ repeat(n) – такрор кардани сатр n маротиба:

let word = "JavaScript ";
console.log(word.repeat(3));  


4. Методҳои пора кардани сатр

✅ slice(start, end) – буридани қисми муайян аз сатр:

let text = "Барномасозӣ";
console.log(text.slice(0, 6)); "
console.log(text.slice(-4));  

✅ substring(start, end) – монанди slice(), вале индекси манфиро қабул намекунад:

console.log(text.substring(0, 6)); 

✅ split(separator) – тақсим кардани сатр ба массив:

let sentence = "Ман барномасоз ҳастам";
let words = sentence.split(" ");  
console.log(words);  // ["Ман", "барномасоз", "ҳастам"]


---

![Screenshot 2025-02-15 004629](https://github.com/user-attachments/assets/dddcf792-c54f-4ccc-bfde-01a7cc503b2c)


number metod;
math.floor() - baroi baqiyaro giriftan;
math.ceil()-Функсияи Math.ceil() дар JavaScript рақами додашударо ба рақами бутунҳои (интежерҳои) боло гиронда мегирад. Ин маънои онро дорад, ки он рақами додашударо ба наздиктарин рақами бутуни калонтар ё баробар ба он мегирад. 
Функсияи Math.round() дар JavaScript рақами додашударо ба наздиктарин рақами бутуни (интежер) гиронда мегирад. Агар қисми дробии рақам камтар аз 0.5 бошад, рақам ба поён гиронда мешавад. Агар қисми дробии рақам 0.5 ё зиёдтар бошад, рақам ба боло гиронда мешавад. 
Функсияи Math.abs() дар JavaScript арзиши мутлақ (absolute) аз як рақамро баргардонад. Арзиши мутлақ ин рақами додашуда бе аломатҳост, яъне он ҳамеша мусбат аст. 
Функсияи Math.max() дар JavaScript рақамҳои додашударо қабул мекунад ва аз онҳо рақами калонтарро бармегардонад. Шумо метавонед ба ин функсия як ё якчанд рақамро аргумент диҳед, ва он аз байни онҳо рақами калонтарро интихоб мекунад
Функсияи Math.min() дар JavaScript рақамҳои додашударо қабул мекунад ва аз онҳо рақами хурдтарро бармегардонад. Шумо метавонед ба ин функсия як ё якчанд рақамро аргумент диҳед, ва он аз байни онҳо рақами хурдтарро интихоб мекунад.
Функсияи Math.pow() дар JavaScript ду аргументро қабул мекунад: рақами асосӣ ва дараҷа (экспонент). Ин функсия ҳисоб мекунад ва бармегардонад, ки асосӣ ба дараҷаи дода шуда баробар аст  
Функсияи Math.sqrt() дар JavaScript корен квадратнии (square root) рақамро бармегардонад. Ин функсия як аргументро қабул мекунад, ки рақами додашуда барои корен квадратнии он аст
Функсияи Math.random() дар JavaScript рақами тасодуфии дараҷаи ноҳамворро аз 0 (шомил) то 1 (истисно) бармегардонад. Ин функсия бидуни аргументҳо истифода бурда мешавад ва метавонад барои сохтани рақамҳои тасодуфии зиёда аз як диапазон истифода шавад
Функсияи isNaN() дар JavaScript месанҷад, ки оё арзиши дода шуда рақам нест (NaN - Not-a-Number) ва бармегардонад true агар арзиши NaN бошад ва false агар не. Ин функсия метавонад барои санҷидани арзишҳо истифода шавад, то бидонед, ки оё онҳо рақамҳои ҳуқуқӣ мебошанд ё не


![Screenshot 2025-02-15 005020](https://github.com/user-attachments/assets/e765e03f-639c-417e-8515-8d9905710992)




