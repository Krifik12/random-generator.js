# easy-generator.js
- npm install easy-generator.js
- Документація для пакета easy-generator.js
- Розробник Krifik
- Діскорд Krifik#4967
- Телеграм @Krifik6

# Приклад номер 1 
```javascript
const RandomBuilder = require("easy-generator.js")

const rg = new RandomBuilder()

const masiv = ["easy-database.js", "easy-generator.js"] //Створюємо масив з двума елементами 

console.log(rg.generate(masiv)) //Отримаємо easy-databse.js чи easy-generator.js
```

# Приклад номер 2
```javascript
const RandomBuilder = require("easy-generator.js")

const rg = new RandomBuilder() 

console.log(rg.generate(["easy-database.js", "easy-generator.js"])) //Отримаємо easy-databse.js чи easy-generator.js
```

# Приклад номер 3
```javascript
const RandomBuilder = require("easy-generator.js")

const rg = new RandomBuilder()

const masiv = ["easy-database.js", "easy-generator.js"] //Створюємо масив з двума елементами
const result = rg.generate(masiv)

console.log(result) //Отримаємо easy-databse.js чи easy-generator.js
```

# Функції
```javascript
generate() - вибрати рандомне значення з масиву
```

