# «Website For The Visually Impaired» — Hyperskill course review.

## 🔍 Ревью курса [«Website for the visually impaired»](https://hyperskill.org/projects/368)

### **Шаг 0: Продуктовые вопросы**

Прежде чем давать рекомендации по улучшению курса, важно лучше понять целевую аудиторию и цели курса. Несколько ключевых вопросов:

1. **Кто целевая аудитория?**
    - Это разработчики, тестировщики, дизайнеры, или специалисты по доступности? Для кого именно создается курс? От этого зависят уровень и глубина представления материала. Если это новички, важно сфокусироваться на базовых понятиях. Для более опытных специалистов стоит включить практические кейсы и более сложные задачи. Кроме того, в зависимости от предполагаемого бэкграунда можно добавлять в курс дополнительные темы (например, про инклюзивный дизайн).
2. **Насколько углубленным должен быть курс?**
    - Должен ли он покрывать много тем на базовом уровне или углубляться в ключевые аспекты? Например, стоит ли подробно разбирать работу со screen reader, работу с ARIA атрибутами, создание сложных доступных компонентов или сосредоточиться на семантике и типографике?
3. **Какой есть фидбек на курс?**
    - Что говорят пользователи? Какие темы кажутся полезными, а какие вызывают затруднения? Особенно интересны комментарии об общем восприятии структуры и о практических заданиях.

Дополнительно я изучила несколько курсов по веб-доступности, чтобы увидеть, как эту тему раскрывают другие платформы. Это помогло выделить ключевые аспекты, которые могут быть полезны для улучшения этого курса.

---

### **Шаг 1: Общее впечатление**

### **Плюсы курса**

- **Структура материала:**
Курс поделён на небольшие шаги, и теория подаётся порционно, что помогает удерживать фокус. Для пользователей с ограниченной концентрацией внимания (например, СДВГ) такой подход особенно удобен.
- **Интерактивность:**
Здорово, что помимо работы с проектом есть промежуточные задания разного типа — выбрать ответ в тесте, найти совпадения, написать маленький кусочек кода — это отличный способ удерживать внимание и проверять усвоение материала. Также большой плюс, что можно решать задачи как в онлайн-редакторе, так и в IDE, и даже с помощью AI — сейчас это часть повседневности, здорово уметь составлять промты и валидировать их результат.
- **Полезные фичи:**
    - **Explain code:** Очень удобный инструмент для новичков.
    - **Блоки Best Practices:** Практические советы и рекомендации сразу дают понимание, как применять теорию.
    - Code snippets from theory — отличная идея делать краткую выжимку из теории в виде просто маленьких блоков кода, которые рассматривались в теории. Очень полезно — удобно обращаться к ним в процессе работы.

### **Недостатки и рекомендации**

1. **Слишком широкий охват нерелевантных тем:**
    
    Многие темы, включенные в курс, не имеют прямого отношения к веб-доступности. Например, базовые операции с массивами, Event Loop  или функции JavaScript сбивают с толку.
    
    Может быть неочевидно, что если кастомизировать свой Study Plan, то множество тем, включенных в курс, уже не будут актуальны. При этом эти темы все еще остаются включенными в курс, просто теперь они отмечены, как пройденные — однако это всё еще озадачивает, если пользователь не знаком с темой доступности, может быть неясно, действительно ли нужны эти темы.
    
    Это все еще и усложняет онбординг и не дает предствления о реальном объеме курса.
    
    **Рекомендация:** Сконцентрироваться только на темах, связанных с доступностью, и пересмотреть структуру курса.
    
2. **Проблемы с мотивацией:**
    
    В начале курса не объясняется, зачем изучать доступность и как это влияет на пользователей. Отсутствует вовлекающее введение.
    
    **Рекомендация:** Добавить вводный модуль с кейсами, статистикой, примерами плохой и хорошей доступности. Дать студентам возможность ощутить этот опыт на себе — например, предложить попользоваться скринридером или браузерными расширениями, чтобы понять, как именно слабовидящие или незрячие люди пользуются сайтом с помощью скринридера.
    
3. **Слабое освещение ключевых тем:**
    - Почти нет информации о типографике, относительных единицах шрифта (`em`, `rem`, `clamp()`), межстрочном интервале, широте строки, .
    - Практически не затронуты темы работы с таблицами, формами, графиками, видео и аудио.
    - Нет упоминаний об инструментах тестирования доступности (Lighthouse, axe).
    
    **Рекомендация:** Расширить теоретическую часть, добавив эти темы.
    
4. **Проблема с концепцией "a11y mode":**
    
    Предложение добавить "режим доступности" вызывает вопросы. Современные сайты стараются быть гибкими и отзывчивыми, чтобы пользователи сами могли регулировать размер шрифта, контрастность и масштаб. Для этого используются отзывчивые сетки, относительные единицы измерения в шрифтах и т.д.
    
    **Рекомендация:** Переформулировать задачу, сосредоточившись на интеграции гибких настроек в сам интерфейс.
    
5. **Отсутствие дальнейших шагов:**
    
    После завершения курса непонятно, как продолжать изучение темы.
    
    **Рекомендация:** Добавить ссылки на ресурсы (WCAG, WAI-ARIA), статьи, чаты и инструменты для работы с доступностью.
    

---

## 🚀 **Шаг 2: Project improvement**

### **Актуальность и формулировка проблемы**

Курс недостаточно четко формулирует проблему доступности. Он поверхностно освещает тему, не объясняя её значимость. Например:

- В начале курса отсутствует мотивация: что такое доступность, для кого она важна, как её отсутствие влияет на пользователей.
- Основные принципы веб-доступности представлены лишь частично (семантика, контрастность, альт-тексты).

**Рекомендации:**

1. Добавить вводный модуль с кейсами, примерами и статистикой.
2. Расширить список тем, включая:
    - Типографику и относительные единицы.
    - Формы и таблицы.
    - Контент мультимедиа (видео, аудио).
    - Инструменты тестирования доступности.

---

## 👩‍🎓 **Шаг 3: Theoretical section (project prerequisites)**

### 1️⃣ **Этап 1: Введение в веб-доступность**

### Основные темы:

1. **Что такое веб-доступность и почему это важно?**
    - Кто пользуется доступными сайтами? (Подсказка: не только люди с ограниченными возможностями!)
    - Быстрая статистика: более 1 миллиарда человек по всему миру живут с какой-либо формой инвалидности. Многие из них используют вспомогательные технологии для доступа к сайтам.
    - Почему инклюзивность улучшает пользовательский опыт для всех?
2. **Основные принципы доступности: POUR**
    - **Perceivable (Воспринимаемость):** делайте информацию понятной и доступной.
    - **Operable (Управляемость):** обеспечьте удобную навигацию с клавиатуры или вспомогательных устройств.
    - **Understandable (Понятность):** создавайте понятный и последовательный контент.
    - **Robust (Надежность):** совместимость с текущими и будущими вспомогательными инструментами.

### Практические задания:

- Попробовать пройти какой-то сценарий в интерфейсе с помощью какого-то скринридера или расширения в браузере, озвучивающего интерфейс (VoiceOver). Показать скрины с симуляторов — как видят интерфейс люди с астигматизмом, дальтонизмом, другими нарушениями зрения, и в том числе дислексией — это нейроотличие, а не проблема зрения, но сильно влияет на восприятие визуального контента, особенно текста.
- Исследуйте популярный сайт (например, новостной портал) и выявите барьеры доступности.

---

### 2️⃣ **Этап 2: Семантическая HTML-разметка и структура**

### Основные темы:

1. **Семантические теги HTML:**
    - Почему важны `<header>`, `<main>`, `<footer>`, `<section>` для работы скринридеров.
    - Правильная структура заголовков (`<h1>`–`<h6>`): зачем важна логика заголовков, даже без визуального оформления.
    - Значение `<nav>` для создания доступной навигации.
    - Как можно прятать элементы в интерфейсе — обзор разных методов, достпуных и недоступных (`display: none`, `visibility: hidden`, подход с классом `.visually-hidden`  и т.д.)
2. **Основы ARIA:**
    - Когда использовать атрибуты ARIA (`aria-label`, `aria-labelledby`, `aria-hidden`).
    - Как избегать «злоупотребления ARIA», если достаточно стандартных HTML-тегов.

### Практические задания:

- Создайте простую веб-страницу с использованием семантических HTML-тегов (заголовок, основное содержимое, подвал). Проверьте её с помощью скринридера (например, NVDA или VoiceOver).
- Добавьте атрибуты ARIA для улучшения навигации.

---

### 3️⃣ **Этап 3: Типографика и дизайн контента**

### Основные темы:

1. **Основы типографики:**
    - Почему относительные единицы (`em`, `rem`) лучше для масштабируемого и адаптивного дизайна.
    - CSS `clamp()` для динамического масштабирования текста.
    - Выбор доступных шрифтов: баланс между читаемостью и эстетикой.
2. **Контрастность и читаемость:**
    - Стандарты контрастности WCAG: минимальное соотношение 4.5:1 для обычного текста и 3:1 для крупного текста.
    - Использование инструментов, таких как Contrast Checker.
3. **Alt-текст для изображений:**
    - Как писать содержательные описания изображений: «Опишите, но будьте краткими».
    - Когда атрибут alt может быть пустым (для декоративных изображений).

### Практические задания:

- Используйте `clamp()` для создания адаптивной типографики.
- Проверьте выбранную цветовую палитру с помощью Contrast Checker и исправьте ошибки.
- Напишите alt-тексты для пяти изображений, включая контентные и декоративные примеры.

---

### 4️⃣ **Этап 4: Формы, таблицы и мультимедиа**

### Основные темы:

1. **Доступные формы:**
    - Маркировка полей ввода с помощью `<label>` или `aria-label`.
    - Понятные сообщения об ошибках с использованием `aria-live` и визуальных стилей.
2. **Доступные таблицы:**
    - Роль `<th>` и атрибута `scope` для скринридеров.
    - Добавление заголовков и описаний таблиц.
3. **Мультимедиа:**
    - Добавление субтитров или транскриптов для видео и аудио.
    - Рекомендации для встраивания YouTube-видео с включёнными субтитрами.

### Практические задания:

- Создайте форму с пометками полей и сообщениями об ошибках.
- Постройте таблицу с заголовками и описаниями.
- Добавьте субтитры к короткому видео и встроите его на страницу.

---

### 5️⃣ **Этап 5: Интерактивные элементы и тестирование**

### Основные темы:

1. **Клавиатурная доступность:**
    - Обеспечение работы всех функций (меню, модальные окна) без использования мыши.
    - Грамотное использование `tabindex`, чтобы избежать «хаоса вкладок».
2. **Тестирование доступности:**
    - Автоматизированные инструменты:
        - Lighthouse (встроен в Chrome).
        - axe DevTools.
    - Ручное тестирование:
        - Использование скринридеров.
        - Проверка навигации только с клавиатурой.
    - Симуляторы дальтонизма и проверка контрастности.

### Практические задания:

- Добавьте клавиатурную навигацию в выпадающее меню.
- Используйте Lighthouse и axe для анализа веб-страницы и исправьте две найденные проблемы.
- Симулируйте дальтонизм и скорректируйте дизайн для улучшения видимости.

---

### 6️⃣ **Этап 6: Расширенные темы (опционально)**

### Основные темы:

1. **ARIA для сложных приложений:**
    - Использование атрибутов `role` для поддержки вспомогательных технологий в веб-приложениях.
2. **Доступные анимации:**
    - Использование `@media (prefers-reduced-motion)` для настройки плавности.
3. **Прогрессивное улучшение:**
    - Создание функций, работающих даже без JavaScript.
4. Резиновые сетки

### Практические задания:

- Добавьте атрибуты ARIA в JavaScript-компонент (например, карусель).
- Настройте анимации с учётом пользователей, чувствительных к движению.

---

### 🏁 **Финальный этап: Сбор проекта воедино**

### Основные темы:

- Тестирование финального проекта.
- Создание чек-листа для будущих проектов:
    - Семантическая структура.
    - Удобные формы и таблицы.
    - Совместимость с клавиатурой и скринридерами.

### Практические задания:

- Улучшите проект "Website For The Visually Impaired" с использованием полученных знаний.
- Подготовьте небольшой отчёт по доступности заготовленного проекта с описанием находок и исправлений.

---

## ⭐ **Заключение**

Этот курс имеет хороший фундамент, но нуждается в доработке, чтобы стать действительно полезным и современным инструментом для изучения веб-доступности. Важно сосредоточиться на практических аспектах, мотивации и ключевых темах, которые помогут студентам создавать доступные сайты.

### Рекомендуемые ресурсы:

- [Руководство по веб-контенту (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [Практики WAI-ARIA](https://www.w3.org/WAI/ARIA/apg/)
- [Документация ARIA](https://www.w3.org/WAI/ARIA/)
- [Веблайнд](https://weblind.ru/) — Рекомендации по разработке сайтов для людей с нарушениями зрения
- [Веб-стандарты — Под­бор­ка ссы­лок для зна­ком­ства с до­ступ­ной раз­ра­бот­кой](https://web-standards.ru/articles/a11y-links/)
- [Web accessibility course — best practices](https://bati-itao.github.io/learning/esdc-self-paced-web-accessibility-course/best-practice/all-best-practice.html)
- [Accessibility Resources 📚 ](https://github.com/tbilisi-js/accessibility-library)
