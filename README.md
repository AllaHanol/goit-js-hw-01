# goit-js-hw-01
JS Homework 1
task-2
Оголоси функцію getShippingMessage, яка очікує три параметри, значення яких будуть задаватися під час її виклику: 
• country — перший параметр, рядок, що містить країну доставки 
• price — другий параметр, число, що містить загальну вартість товару 
• deliveryFee — третій параметр, число, що містить вартість доставки товару

Доповни код функції так, щоб вона повертала рядок з повідомленням про доставку товару в країну користувача: 
"Shipping to <country> will cost <totalPrice> credits"
, де: • <country> — це країни доставки • <totalPrice> — це загальна вартість замовлення, що включає вартість товару і його доставки

Візьми код нижче і встав після оголошення своєї функції для перевірки коректності її роботи. У консоль будуть виведені результати її роботи.

console.log(getShippingMessage("Australia", 120, 50)); // "Shipping to Australia will cost 170 credits"
console.log(getShippingMessage("Germany", 80, 20)); // "Shipping to Germany will cost 100 credits"
console.log(getShippingMessage("Sweden", 100, 20)); // "Shipping to Sweden will cost 120 credits"
Залиш цей код для перевірки ментором.

На що буде звертати увагу ментор при перевірці:
Оголошена функція getShippingMessage(country, price, deliveryFee)
Виклик getShippingMessage("Australia", 120, 50) повертає "Shipping to Australia will cost 170 credits"
Виклик getShippingMessage("Germany", 80, 20) повертає "Shipping to Germany will cost 100 credits"
Виклик getShippingMessage("Sweden", 100, 20) повертає "Shipping to Sweden will cost 120 credits"
Виклик getShippingMessage з будь якими-валідними аргументами повертає правильне значення


task-3
Оголоси функцію getElementWidth, яка очікує три параметри, значення яких будуть задаватися під час її виклику: • content— перший параметр, ширина контенту • padding — другий параметр, значення горизонтального падінгу для кожної зі сторін • border — третій параметр, значення товщини бордера для кожної зі сторін Значення всіх параметрів будуть рядками формату Npx де N — це довільне число, ціле або дробове.

Доповни код функції так, щоб вона повертала число —загальну ширину елемента. При розрахунку загальної ширини орієнтуйся на те, що значення box-sizing дорівнює border-box.

Візьми код нижче і встав після оголошення своєї функції для перевірки коректності її роботи. У консоль будуть виведені результати її роботи.

console.log(getElementWidth("50px", "8px", "4px")); // 74
console.log(getElementWidth("60px", "12px", "8.5px")); // 101
console.log(getElementWidth("200px", "0px", "0px")); // 200

Залиш цей код для перевірки ментором.
На що буде звертати увагу ментор при перевірці:
Оголошена функція getElementWidth(content, padding, border)
Виклик getElementWidth("50px", "8px", "4px") повертає число 74
Виклик getElementWidth("60px", "12px", "8.5px") повертає число 101
Виклик getElementWidth("200px", "0px", "0px") повертає число 200
Виклик getElementWidth з будь якими-валідними аргументами повертає правильне значення