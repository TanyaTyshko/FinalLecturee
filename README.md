# План автоматизации
## 	Перечень автоматизируемых сценариев 
### 1	cценарий
**Название:** ввод валидных значений в поля "Имя", "Телефон", навигация через кнопку "Каталог курсов"

**Шаги:**
1. Нажать кнопку "Каталог курсов"
2. Выбрать в направлении обучения "Программирование"
3. Выбрать курс "Тестировщик ПО"
4. Ввести валидные данные в поле "Имя" на кириллице/латинице не короче 2 символов, состоящие только из букв (Татьяна)
5. Ввести данные в поле "Телефон" в формате +9 (999) 999-99-99
6. Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1. Отображаются направления обучения на выбор
2. Открывается список с курсами по программированию
3. Отображается окно с полями ввода персональных данных для получения консультации по обучению
4. Поле принимает данные
5. Поле принимает данные
6. Отображается окно "Ваша заявка успешно отправлена!"

### 2	сценарий
**Название:** ввод невалидных значений в поле "Имя", навигация через кнопку "Каталог курсов"

**Шаги:**
1. Нажать кнопку "Каталог курсов"
2. Выбрать в направлении обучения "Программирование"
3. Выбрать курс "Тестировщик ПО"
4. Ввести данные в поле "Имя" на кириллице 1 символ
5. Ввести данные в поле "Телефон" в формате +9 (999) 999-99-99
6. Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1. Отображаются направления обучения на выбор
2. Открывается список с курсами по программированию 
3. Отображается окно с полями ввода персональных данных для получения консультации по обучению
4. Выводится ошибка "Должно быть не короче 2 символов"
5. Поле принимает данные
6. Кнопка не отвечает

### 3	сценарий
**Название:** ввод невалидных значений в поле "Имя", навигация через кнопку "Каталог курсов"

**Шаги:**
1. Нажать кнопку "Каталог курсов"
2. Выбрать в направлении обучения "Программирование"
3. Выбрать курс "Тестировщик ПО"
4. Ввести данные в поле "Имя" цифрами
5. Ввести данные в поле "Телефон" в формате +9 (999) 999-99-99
6. Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1. Отображаются направления обучения на выбор
2. Открывается список с курсами по программированию 
3. Отображается окно с полями ввода персональных данных для получения консультации по обучению
4. Выводится ошибка "Должно состоять из букв"
5. Поле принимает данные
6. Кнопка не отвечает

### 4	сценарий
**Название:** ввод невалидных значений в поле "Телефон", навигация с главной страницы сайта через раздел "направления обучения"

**Шаги:**
1.	Нажать кнопку "Программирование" в разделе "Направления обучения"
2.	Выбрать курс "Тестировщик ПО"
3.	 Ввести валидные данные в поле "Имя" на кириллице/латинице не короче 2 символов, состояющие только из букв (Татьяна)
4.	Ввести данные в поле "Телефон" 6 цифр
5.	Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1.	Открывается список с курсами по программированию
2.	Отображается окно с полями ввода персональных данных для получения консультации по обучению
3.	Поле принимает данные
4.	Выводится ошибка "Номер в формате +9 (999) 999-99-99"
5.	Кнопка не отвечает

### 5	сценарий
**Название:** ввод валидных значений в поля "Имя", "Телефон", навигация с главной страницы сайта через раздел "направления обучения"

**Шаги:**
1.	Нажать кнопку "Программирование" в разделе "Направления обучения"
2.	Выбрать курс "Тестировщик ПО
3.	Ввести валидные данные в поле "Имя" на кириллице/латинице не короче 2 символов, состояющие только из букв (Татьяна)
4.	Ввести данные в поле "Телефон" в формате +9 (999) 999-99-99
5.	Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1. Открывается список с курсами по программированию 
2. Отображается окно с полями ввода персональных данных для получения консультации по обучению 
3. Поле принимает данные 
4. Поле принимает данные 
5. Отображается окно "Ваша заявка успешно отправлена!"

### 6 cценарий
**Название:** ввод невалидных значений в поле "Имя", навигация с главной страницы сайта через раздел "направления обучения"

**Шаги:**
1.	Нажать кнопку "Программирование" в разделе "Направления обучения"
2.	Выбрать курс "Тестировщик ПО
3.	Ввести данные в поле "Имя" спецсимволами\
4.	Ввести данные в поле "Телефон" в формате +9 (999) 999-99-99
5.	Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1.	Открывается список с курсами по программированию
2.	Отображается окно с полями ввода персональных данных для получения консультации по обучению
3.	Выводится ошибка "Должно состоять из букв"
4.	Поле принимает данные
5.	Кнопка не отвечает

### 7	cценарий
**Название:** ввод валидных значений в поля "Имя", "Телефон", навигация через футер сайта

**Шаги:**
1. Пролистать до нижней части главной страницы сайта (до футера сайта), в столбце "Обучение" нажать кнопку "Программирование"
2. Выбрать курс "Тестировщик ПО"
3. Ввести валидные данные в поле "Имя" на кириллице/латинице не короче 2 символов, состоящие только из букв (Татьяна)
4. Ввести данные в поле "Телефон" в формате +9 (999) 999-99-99
5. Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1. Открывается список с курсами по программированию
2. Отображается окно с полями ввода персональных данных для получения консультации по обучению
3. Поле принимает данные
4. Поле принимает данные
5. Отображается окно "Ваша заявка успешно отправлена!"

### 8	cценарий
**Название:** оставить поле ввода "Имя" пустым, навигация через футер сайта

**Шаги:**
1. Пролистать до нижней части главной страницы сайта (до футера сайта), в столбце "Обучение" нажать кнопку "Программирование"
2. Выбрать курс "Тестировщик ПО"
3. Оставить поле ввода "Имя" пустым
4. Ввести данные в поле "Телефон" в формате +9 (999) 999-99-99
5. Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1. Открывается список с курсами по программированию
2. Отображается окно с полями ввода персональных данных для получения консультации по обучению
3. Выводится ошибка "Обязательное поле"
4. Поле принимает данные
5. Кнопка не отвечает

### 9	cценарий
**Название:** оставить поле ввода "Телефон" пустым, навигация через кнопку "Каталог курсов"

**Шаги:**
1. Нажать кнопку "Каталог курсов"
2. Выбрать в направлении обучения "Программирование"
3. Выбрать курс "Тестировщик ПО
4. Ввести валидные данные в поле "Имя" на кириллице/латинице не короче 2 символов, состояющие только из букв (Татьяна)
5. Оставить поле ввода "Телефон" пустым
6. Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1. Отображаются направления обучения на выбор
2. Открывается список с курсами по программированию 
3. Отображается окно с полями ввода персональных данных для получения консультации по обучению
4. Поле принимает данные
5. Выводится ошибка "Обязательное поле"
6. Кнопка не отвечает

### 10	cценарий
**Название:** ввод невалидных значений в поле "Телефон", навигация через кнопку "Каталог курсов"

**Шаги:**
1. Нажать кнопку "Каталог курсов"
2. Выбрать в направлении обучения "Программирование"
3. Выбрать курс "Тестировщик ПО
4. Ввести валидные данные в поле "Имя" на кириллице/латинице не короче 2 символов, состояющие только из букв (Татьяна)
5. Ввести данные в поле "Телефон" буквами
6. Нажать кнопку "Получить консультацию"

**Ожидаемый результат:**
1. Отображаются направления обучения на выбор
2. Открывается список с курсами по программированию 
3. Отображается окно с полями ввода персональных данных для получения консультации по обучению
4. Поле принимает данные
5. Выводится ошибка "Номер в формате +9 (999) 999-99-99"
6. Кнопка не отвечает

## Перечень используемых инструментов
- DevTools — это набор инструментов, позволяющий создавать, тестировать и отлаживать (debug) программное обеспечение.
- Postman - позволяет создавать и отправлять различные типы HTTP-запросов к API (GET, POST, PUT, DELETE и другие), чтобы тестировать и документировать работу бэкенда сайта.
- Selenide - это фреймворк для автоматизированного тестирования веб-приложений на основе Selenium WebDriver, используется для написания программных кодов, которая помогает создавать и отправлять HTTP-запросы на Server.
- Faker- библиотека для генерации фальшивых данных для автоматического тестирования.
- IntelliJ IDEA – это интегрированная среда разработки (комплекс программных средств, который используется для написания, исполнения, отладки и оптимизации кода) для Java, JavaScript, Python и других языков программирования.
- Allure – это фреймворк, предназначенный для создания визуально наглядной картины выполнения тестов. Allure создает удобные отчёты, которые классифицируют дефекты, относящиеся к продукту и автотестам. 
- DBeaver-приложение, предназначенное для управления базами данных.
- Docker- это программная платформа для разработки, доставки и запуска контейнерных приложений. Он позволяет создавать контейнеры, автоматизировать их запуск и развертывание, управляет жизненным циклом. С помощью Docker можно запускать множество контейнеров на одной хост-машине.
- Lombok – это библиотека, которая упрощает написание программ на java.
- Junit 5 - позволяет создавать автоматизированные тесты на java.

## Перечень необходимых разрешений, данных и доступов
Тестировщику необходимы требования, данные для заполнения формы. Также тестировщик может попросить доступ к базе данных.

## Перечень и описание возможных рисков при автоматизации
- Неверный подбор инструментов
- Недостаточный опыт у тестировщика в работе с инструментарием
- Нет документации к тестируемому приложению
- Технические проблемы
- Отсутствие тестовых меток, незнание структуры страницы
- Организация автоматизации тестирования там, где она не нужна (лишняя трата денег)
- Дефицит времени
- Недостача ресурсов
- Изменения в рабочих процессах

## Перечень необходимых специалистов для автоматизации
Для написания авто тестов необходим тестировщик автоматизатор.

## Интервальная оценка с учётом рисков в часах
Без рисков до 40 часов, с рисками до 60 часов.
