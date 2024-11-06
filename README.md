# function
3 вида функции
1. Обычные функции (Function Declarations)
 // Функция без параметров, которая возвращает строку
function greet() {
    return "Привет, мир!";
}

console.log(greet());  // Вывод: Привет, мир!

2.Функции-выражения (Function Expressions)
2.1// Анонимная функция, присвоенная переменной
const sum = function(a, b) {
    return a + b;
};

console.log(sum(3, 4));  // Вывод: 7
2.2
Стрелочные функции (Arrow Functions)
// Стрелочная функция для сложения двух чисел
const multiply = (a, b) => a * b;

console.log(multiply(2, 5));  // Вывод: 10

3.function IIFE
(function(a, b) {
    const sum = a + b;
    console.log("Сумма:", sum);  // Вывод: Сумма: 15
})(7, 8);



