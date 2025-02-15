# Методы работы со строками в JavaScript

---

## _Основные методы_

### 1️⃣ _charAt_: возвращает символ по указанному индексу.
let text = "Привет, мир!";
console.log(text.charAt(0)); // "П"


### 2️⃣ _concat_: объединяет две или более строк и возвращает новую строку.
let greeting = "Привет";
let name = "Мир";
let message = greeting.concat(", ", name, "!");
console.log(message); // "Привет, Мир!"


### 3️⃣ _includes_: проверяет, содержится ли подстрока в строке, возвращая true или false
let text = "Я люблю JavaScript";
console.log(text.includes("люблю")); // true


###  4️⃣ _indexOf_: возвращает индекс первого вхождения подстроки или -1, если подстрока не найдена.
let text = "Я люблю JavaScript";
console.log(text.indexOf("люблю")); // 2


###  5️⃣ _replace_: заменяет первое вхождение подстроки на новую строку.
let text = "Я люблю JavaScript";
let newText = text.replace("люблю", "обожаю");
console.log(newText); // "Я обожаю JavaScript"



###  6️⃣ _slice_: извлекает часть строки от start до end (не включая end).
let text = "Привет, мир!";
let substring = text.slice(0, 6);
console.log(substring); // "Привет"


###  7️⃣ _split_: разбивает строку на массив подстрок, используя разделитель.
let text = "яблоко,банан,вишня";
let fruits = text.split(",");
console.log(fruits); // ["яблоко", "банан", "вишня"]

###  8️⃣ _toLowerCase()_: преобразует все символы строки в нижний регистр.
let text = "ПрИвЕт, МиР!";
let lowerText = text.toLowerCase();
console.log(lowerText); // "привет, мир!"

###  9️⃣ _toUpperCase()_: преобразует все символы строки в верхний регистр.
let text = "ПрИвЕт, МиР!";
let upperText = text.toUpperCase();
console.log(upperText); // "ПРИВЕТ, МИР!"

###  🔟 _trim()_: удаляет пробелы с начала и конца строки.
let text = "  Привет, мир!  ";
let trimmedText = text.trim();
console.log(trimmedText); // "Привет, мир!"
