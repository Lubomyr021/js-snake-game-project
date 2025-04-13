![image](https://github.com/user-attachments/assets/f68dd564-13b7-4949-98fe-6527e3827522)


 🐍 Snake Game

Класична аркадна гра **Snake**, реалізована на чистому JavaScript з використанням HTML5 Canvas. Гравець керує змійкою, яка росте, поїдаючи їжу, та має уникати зіткнень із собою та стінами. Результати зберігаються в таблиці лідерів за допомогою Firebase.

 🔥 Особливості

- Рух змійки через клавіатуру або кнопки на екрані
- Таблиця лідерів з Firebase Firestore
- Збереження найкращого результату локально (LocalStorage)
- Модальні вікна для введення ім'я, перегляду рекорду та кінця гри
- Плавне збільшення швидкості гри при кожних 50 очках

---

 📁 Структура проєкту

```
├— index.html                # Основна HTML-сторінка гри
├— style/
│   └— styles.css           # Стилі гри
├— js/
│   ├— main.js              # Основна логіка запуску гри
│   ├— game.js              # Клас гри (логіка, оновлення, рендеринг)
│   ├— snake.js             # Клас змійки
│   ├— food.js              # Клас їжі
│   ├— user.js              # Клас користувача (збереження результатів)
│   ├— leaderboard.js       # Клас таблиці лідерів (робота з Firebase)
│   └— firebase-config.js   # Конфігурація Firebase

```
