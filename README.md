# Team Project

**Привіт. Це груповий проект для практики HTML + CSS**

[Посилання на макет у Figma](<https://www.figma.com/file/67mnimnDXNldtaekTSsLwh/World.net(2.0)?type=design&mode=design&t=TQtCli48Uzq4xXGI-0>)

> [!IMPORTANT] Якщо ви клонували цей макет, то зможете знайти його через меню
> Figma

<details>
    <summary>РОЗГОРНУТИ</summary>

![Зображення](https://i.imgur.com/nHenvLL.png)

</details>

## Задачі для виконання

- [x] Скелет сайту
  - [x] Головна сторінка
    - [x] Додати Header
    - [x] Додати секцію Hero
    - [x] Додати секцію Why us
    - [x] Додати секцію About
    - [x] Додати секцію Feedback
    - [x] Додати секцію Tariffs
    - [x] Додати секцію з формою
    - [x] Додати Футер
  - [x] Сторінка Тарифи
    - [x] Додати Header
    - [x] Додати Футер
  - [x] Додати модальне вікно
- [ ] Стилі сайту
  - [x] Додати стилі для текстових елементів
  - [ ] Додати стилі для основних елементів
  - [ ] Додати стилі для декоративних елементів

> [!TIP]
>
> ## Для швидкого написання коду за допомогою вбудованного плагіна Emmet розпишу інструкцію.

<details>
    <summary>РОЗГОРНУТИ</summary>

### Обгортання тексту, елементу або одразу всього

<details>
    <summary>РОЗГОРНУТИ</summary>

Порядок виконання:

1. виділити елемент для обгортання
2. натиснути F1 (виклик функції VSCode)
3. з’явиться поле для вводу
4. викликати необхідну функцію написавши "Emmet: Wrap with Abbreviation"

![Зображення](https://i.imgur.com/ovetkiR.png)

5. з’явиться нове поле для вводу
6. написати назву тегу, або будь чого, чим ви хочете обгорнути (wrap - англ.)
   виділений елемент

![Зображення](https://i.imgur.com/dshuydS.png)

7. Натиснути клавішу Enter! (без цього команда не виконається)

> [!NOTE] Цю процедуру доведеться повторювати багато разів з різними елементами,
> тож, щоб не повторювати пункт 2-4 кожного разу виконання команди можна
> присвоїти комбінації клавіш.

Як це зробити:

1. Відкрити налаштування File - Preferences - Keyboard Shortcuts або натиснути
   Шестерню зліва - Keyboard Shortcuts

   ![Зображення](https://i.imgur.com/poHuoEH.png)

2. В поле пошуку вказати назву команди для виконання "Emmet: Wrap with
   Abbreviation" (писати повністю не обов’язково, достатньо побачити в списку
   необхідну команду)

   ![Зображення](https://i.imgur.com/reNI6hG.png)

3. Натиснути на назву два рази лівою кнопкую миші
4. З’явиться поле для реєстрації сполучення клавіш

   ![Зображення](https://i.imgur.com/szVhpgB.png)

5. Натиснути необхідну комбінацію, наприклад Shift+Alt+W
6. Закрити вкладку налаштувань

</details>

### Для швидкого переміщення елементу або виділення між рядками

<details>
    <summary>РОЗГОРНУТИ</summary>

1. Поставте курсор в той рядок, або виділіть блок який хочете перемістити в інше
   місце

   ![Зображення](https://i.imgur.com/EcGmBbi.png)

2. Затисність Atl + стрілка вверх, або низ

   ![Зображення](https://i.imgur.com/UoKDXf3.png)

</details>

### Для швидкого копіювання (дублювання) елементу або виділення

<details>
    <summary>РОЗГОРНУТИ</summary>

1. Поставте курсор в той рядок, або виділіть блок який хочете дублювати

   ![Зображення](https://i.imgur.com/mUwupLo.png)

2. Затисність Shift + Atl + стрілка вверх

   ![Зображення](https://i.imgur.com/HcDBwqr.png)

</details>

</details>

> [!TIP]
>
> ## Шпаргалка для роботи з GIT та GITHUB.

<details>
    <summary>РОЗГОРНУТИ</summary>

### Основний потік команд для початку роботи

<details>
    <summary>РОЗГОРНУТИ</summary>

</details>

### Скорочення постійних команд

<details>
    <summary>РОЗГОРНУТИ</summary>

Скорочення:

git config --global alias.ac "!git add -A && git commit -m "

> Це об’єдная послідодве використання команд

git add . git commit -m "text"

> Тепер достатньо виконати команду

git ac "якийсь текст"

Скорочення:

git config --global alias.cmp '!f() { git add -A && git commit -m "$@" && git
push; }; f'

> Це об’єдная послідодве використання команд

git add . git commit -m "text" git push

> Тепер достатньо виконати команду

git cmp "якийсь текст"

</details>

</details>

### Плагін для браузера, який дозволяє порівнювати сайт із зображенням

**PerfectPixel by WellDoneCode (pixel perfect)**

https://chromewebstore.google.com/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi?pli=1
