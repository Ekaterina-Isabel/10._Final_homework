# План автоматизации тестирования сценария перехода к форме записи на обучение профессии "Тестировщик ПО", заполнения этой формы

### 1. Перечень автоматизируемых сценариев:

<details>
   <summary>1. Переход на страницу профессии "Тестировщик ПО" с главной страницы сайта Нетология</summary>

##### 1.1. Переход на страницу профессии "Тестировщик ПО" по кнопке "Каталог курсов"
1. открыть страницу сайта ["Нетология"](https://netology.ru/)
2. нажать на кнопку "Каталог курсов"
3. в выпадающем списке навести мышкой на курс "Программирование"
4. нажать в появившемся списке на кнопку "Тестировщик ПО"

Ожидаемый результат: переход на страницу профессии "Тестировщик"

##### 1.2. Переход на страницу профессии "Тестировщик ПО" по кнопке "Полный каталог"
1. открыть страницу сайта ["Нетология"](https://netology.ru/)
2. нажать на кнопку "Каталог курсов"
3. в выпадающем списке нажать на кнопку "Полный каталог"
4. пролистать до кнопки-блока "Тестировщик ПО", нажать на нее

Ожидаемый результат: переход на страницу профессии "Тестировщик"

##### 1.3. Переход на страницу профессии "Тестировщик ПО" по кнопке-блоку "Программирование"
1. открыть страницу сайта ["Нетология"](https://netology.ru/)
2. под заголовком "Направления обучения" нажать на кнопку-блок "Программирование"
3. пролистать до кнопки-блока "Тестировщик ПО", нажать на нее

Ожидаемый результат: переход на страницу профессии "Тестировщик"

##### 1.4. Переход на страницу профессии "Тестировщик ПО" по кнопке "Выбрать курс"
1. открыть страницу сайта ["Нетология"](https://netology.ru/)
2. пролистать страницу до блока с заголовком "Раскройте свои сильные стороны", "Выберете вектор развития"
3. под заголовком нажать на кнопку "Выбрать курс"
4. пролистать до кнопки-блока "Тестировщик ПО", нажать на нее

Ожидаемый результат: переход на страницу профессии "Тестировщик"

##### 1.5. Переход на страницу профессии "Тестировщик ПО" по кнопке "Каталог курсов" внизу страницы ("Footer")
1. открыть страницу сайта ["Нетология"](https://netology.ru/)
2. пролистать страницу до конца
3. в черном блоке внизу ("Footer") нажать на кнопку "Каталог курсов"
4. пролистать до кнопки-блока "Тестировщик ПО", нажать на нее

Ожидаемый результат: переход на страницу профессии "Тестировщик"

##### 1.6. Переход на страницу профессии "Тестировщик ПО" по кнопке "Популярные курсы" внизу страницы ("Footer")
1. открыть страницу сайта ["Нетология"](https://netology.ru/)
2. пролистать страницу до конца
3. в черном блоке внизу ("Footer") нажать на кнопку "Популярные курсы"
4. пролистать до кнопки-блока "Тестировщик ПО", нажать на нее

Ожидаемый результат: переход на страницу профессии "Тестировщик"

##### 1.7. Переход на страницу профессии "Тестировщик ПО" по кнопке "Программирование" внизу страницы ("Footer")
1. открыть страницу сайта ["Нетология"](https://netology.ru/)
2. пролистать страницу до конца
3. в черном блоке внизу ("Footer") нажать на кнопку "Программирование"
4. пролистать до кнопки-блока "Тестировщик ПО", нажать на нее

Ожидаемый результат: переход на страницу профессии "Тестировщик"

</details>
<details>
   <summary>2. Переход и заполнение формы записи на обучение профессии "Тестировщик ПО"</summary>

#### 2.1. Заполнение формы записи по кнопке "Записаться" после заголовка профессии
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. нажать на кнопку "Записаться" после заголовка-названия профессии "Тестировщик" (после блока "src-shared-landing")
3. ввести в поля ввода "Имя", "Телефон", "Электронная почта" валидные данные
4. Нажать на кнопку "Записаться"

Ожидаемый результат: появляется сообщение "Поздравляем! Вы успешно записались на курс"

#### 2.2. Заполнение формы записи по появляющейся кнопке "Записаться" вверху страницы
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать страницу до первого блока информации о скидке ("components-SaleInfo")
3. в появившемся блоке вверху ("Header--top") нажать справа на кнопку "Записаться"
4. ввести в поля ввода "Имя", "Телефон", "Электронная почта" валидные данные
5. Нажать на кнопку "Записаться"

Ожидаемый результат: появляется сообщение "Поздравляем! Вы успешно записались на курс"

#### 2.3. Заполнение формы записи внизу страницы профессии
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя", "Телефон", "Электронная почта" валидные данные
4. Нажать на кнопку "Записаться"

Ожидаемый результат: появляется сообщение "Поздравляем! Вы успешно записались на курс"

</details>

<details>
   <summary>3. Тестирование формы записи на обучение профессии "Тестировщик ПО"</summary>

#### 3.1. Отправка пустой формы записи
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. не вводить никакие данные в поля ввода
4. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поля ввода выделяются красным цветом, под ними появляются сообщения "Обязательное поле"

<details>
   <summary>- поле ввода "Имя"</summary>

#### 3.1.1. Заполнение формы записи валидными данными, имя на кириллице
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Екатерина-Мария"
4. ввести в поля ввода "Телефон" валидные данные (+ и 11 цифр), например, "+79122225222"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи отправляется, появляется сообщение "Поздравляем! Вы успешно записались на курс"

#### 3.1.2. Заполнение формы записи валидными данными, имя на латинице
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Smirnov Evgeniy"
4. ввести в поля ввода "Телефон" валидные данные, например, "+79111225222"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи отправляется, появляется сообщение "Поздравляем! Вы успешно записались на курс"

#### 3.1.3. Заполнение формы записи, пустой ввода поля "Имя"
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. в поле "Имя" не вводить никакие данные
4. ввести в поля ввода "Телефон" валидные данные (+ и 11 цифр), например, "+79122225111"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Имя" выделяется красным цветом, под ним появляется сообщение "Обязательное поле"

#### 3.1.4. Заполнение формы записи не валидными данными, имя включает в себя символы
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" не валидные данные, например, "Катя___123;"%"
4. ввести в поля ввода "Телефон" валидные данные, например, "+79111225222"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Имя" выделяется красным цветом, под ним появляется сообщение "Должно состоять из букв"

</details>

<details>
   <summary>- поле ввода "Телефон"</summary>

#### 3.2.1. Заполнение формы записи валидными данными, формат телефона через 8
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Мария Викторовна"
4. ввести в поля ввода "Телефон" валидные данные (11 цифр начиная с 8), например, "89122225222"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи отправляется, появляется сообщение "Поздравляем! Вы успешно записались на курс"

#### 3.2.2. Заполнение формы записи, пустой ввода поля "Телефон"
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Смирнов Евгений Борисович"
4. в поле "Телефон" не вводить никакие данные 
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Телефон" выделяется красным цветом, под ним появляется сообщение "Обязательное поле"

#### 3.2.3. Заполнение формы записи не валидными данными, короткий номер телефона (10 цифр)
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" не валидные данные (+ и 10 цифр), например, "+9 (999) 999-99-9"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: зависит от спецификации, от требований к форме данных; предполагаю, что форма записи не отправляется, поле ввода "Телефон" выделяется красным цветом, под ним появляется сообщение "Номер в формате +9 (999) 999-99-99"

#### 3.2.4. Заполнение формы записи не валидными данными, короткий номер телефона (8 цифр)
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" не валидные данные (+ и 8 цифр), например, "+9 (999) 999-9"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Телефон" выделяется красным цветом, под ним появляется сообщение "Номер в формате +9 (999) 999-99-99"

#### 3.2.5. Заполнение формы записи не валидными данными, телефон включает в себя символы
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" не валидные данные, например, "8-912_00%0!?"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Телефон" выделяется красным цветом, под ним появляется сообщение "Номер в формате +9 (999) 999-99-99"

#### 3.2.6. Заполнение формы записи не валидными данными, телефон состоит из 0
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр-Петр"
4. ввести в поля ввода "Телефон" не валидные данные, например, "00000000000"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Телефон" выделяется красным цветом, под ним появляется сообщение "Номер в формате +9 (999) 999-99-99"

#### 3.2.7. Заполнение формы записи не валидными данными, длинный номер телефона (12 цифр)
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" не валидные данные (12 цифр), например, "891200000000"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Телефон" выделяется красным цветом, под ним появляется сообщение "Номер в формате +9 (999) 999-99-99"

#### 3.2.8. Заполнение формы записи не валидными данными, длинный номер телефона (15 цифр)
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" не валидные данные (15 цифр), например, "891200000000111"
5. ввести в поля ввода "Электронная почта" валидные данные, например, "test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Телефон" выделяется красным цветом, под ним появляется сообщение "Номер в формате +9 (999) 999-99-99"

</details>

<details>
   <summary>- поле ввода "Электронная почта"</summary>

#### 3.3.1. Заполнение формы записи не валидными данными, в поле "Электронная почта" отсутствует символ @
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" валидные данные (11 цифр), например, "89120000000"
5. ввести в поля ввода "Электронная почта" не валидные данные, например, "testgmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Электронная почта" выделяется красным цветом, под ним появляется сообщение "Неверный email"

#### 3.3.2. Заполнение формы записи не валидными данными, в поле "Электронная почта" отсутствует домен
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" валидные данные (11 цифр), например, "89120000000"
5. ввести в поля ввода "Электронная почта" не валидные данные, например, "test@gmail"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Электронная почта" выделяется красным цветом, под ним появляется сообщение "Неверный email"


#### 3.3.3. Заполнение формы записи не валидными данными, в поле "Электронная почта" отсутствует точка перед доменом
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" валидные данные (11 цифр), например, "89120000000"
5. ввести в поля ввода "Электронная почта" не валидные данные, например, "test@gmailcom"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Электронная почта" выделяется красным цветом, под ним появляется сообщение "Неверный email"

#### 3.3.4. Заполнение формы записи не валидными данными, в поле "Электронная почта" почта начинается с пробела
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" валидные данные (11 цифр), например, "89120000000"
5. ввести в поля ввода "Электронная почта" не валидные данные, например, " test@gmail.com"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Электронная почта" выделяется красным цветом, под ним появляется сообщение "Неверный email"

#### 3.3.5. Заполнение формы записи не валидными данными, в поле "Электронная почта" почта заканчивается пробелом
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" валидные данные (11 цифр), например, "89120000000"
5. ввести в поля ввода "Электронная почта" не валидные данные, например, "test@gmail.com "
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Электронная почта" выделяется красным цветом, под ним появляется сообщение "Неверный email"

#### 3.3.6. Заполнение формы записи не валидными данными, пустое поле "Электронная почта"
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" валидные данные (11 цифр), например, "89120000000"
5. не вводить в поле "Электронная почта" никаких данных
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Электронная почта" выделяется красным цветом, под ним появляется сообщение "Обязательное поле"

#### 3.3.7. Заполнение формы записи не валидными данными, поле ввода "Электронная почта" состоит из символов
1. открыть страницу профессии ["Тестировщик ПО"](https://netology.ru/programs/qa)
2. пролистать всю страницу профессии до формы записи
3. ввести в поля ввода "Имя" валидные данные, например, "Александр"
4. ввести в поля ввода "Телефон" валидные данные (11 цифр), например, "89120000000"
5. ввести в поля ввода "Электронная почта" не валидные данные, например, "!%8%_)"
6. нажать на кнопку "Записаться"

Ожидаемый результат: форма записи не отправляется, поле ввода "Электронная почта" выделяется красным цветом, под ним появляется сообщение "Неверный email"

   </details>
   </details>
   
### 2. Перечень используемых инструментов с обоснованием выбора

- **Git** - система контроля версий (самая популярная)
- **GitHub** - веб-сервис для хостинга IT-проектов основанный на сестеме контроля версий Git (крупнейший, самый
  популярный)
- **JUnit5** - фреймворк для тестирования ПО на языке Java (наиболее удобный)
- **Java 11** - язык программирования (на ней разрабатываются большинство проектов)
- **Gradle** - система автоматической сборки, инструмент управления проектами (более гибкая и современная система сборки
  в сравнении в другими)
- **Selenide** - фреймворк для автоматизированного тестирования веб-приложений для поиска веб-элементов на странице (в
  отличие от Selenium не требует настройки окружения, установки специального драйвера)
- **JaCoCo** - плагин, использующий метрику, которая показывает насколько % код был покрыт автотестами (популярный)
- **Lombok** - библиотека для генерации кода (популярный инструмент, упрощает написание кода)
- **Faker** - библиотека, генератор данных (тестирование в широком диапазоне тестовых данных)
- **Appveyor** - веб-сервис непрерывной интеграции, предназначенный для сборки и тестирования программного обеспечения расположенного на GitHub (прост в настройке)
- **Allure** — фреймворк, предназначенный для создания визуально наглядной картины отчета о выполнении тестов. (наиболее распространен)

### 3. Перечень необходимых разрешений/данных/доступов
- разрешение на тестирование
- доступ к API сайта "Нетология"
- доступ к базе данных "Нетологии"

### 4. Перечень и описание возможных рисков при автоматизации

- отсутствие спецификации на работу приложения
- необходимость поддержки кода автотестов
- отсутствие тестов для проверки UA, кросплатформенного тестирования
- отсутствие нагрузочного тестирования, тестирования безопасности
- изменение верстки повлекут за собой неработоспособность автотестов

### 5. Перечень необходимых специалистов для автоматизации
- тестировщик ПО со знаниями языка программирования для написания автотестов
- системный администратор для обезличивания и предоставления базы данных "Нетологии"

### 6. Интервальная оценка с учётом рисков (в часах)

40 часов
