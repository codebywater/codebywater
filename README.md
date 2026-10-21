<div align="center">

# 🌊 Coder by Water

**Делаю open-source инструменты, которые экономят деньги и время.**\
Личные финансы и налоги, маркетплейсы, ИИ-агенты для Claude Code, железо.

[![Профиль](https://img.shields.io/badge/GitHub-codebywater-181717?logo=github)](https://github.com/codebywater)
[![Проекты](https://img.shields.io/badge/open--source-9_проектов-2f45c8)](https://github.com/codebywater?tab=repositories)
![Лицензия](https://img.shields.io/badge/лицензии-MIT_%7C_GPL--3.0-146c43)

</div>

---

## 🏙 Мой город репозиториев

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/city-dark.svg">
  <img alt="Город репозиториев codebywater: высота дома — число коммитов" src="assets/city-light.svg">
</picture>

<sub>Каждый дом — репозиторий, высота — число коммитов. Город перестраивается каждый день с помощью [GitHub City](https://github.com/codebywater/github-city).</sub>

## 👋 Обо мне

- 🛠 Пишу инструменты, которыми пользуюсь сам: от калькулятора налогов до прошивки для Flipper Zero.
- 🔒 Люблю, когда данные пользователя **не уходят в интернет**. Многие мои веб-версии работают целиком в браузере, и это закреплено политикой безопасности страницы.
- 🤖 Собираю ИИ-агентов и скиллы для **Claude Code**, Codex и Cursor, которые решают реальные бизнес-задачи на русском.
- ✅ В каждом проекте есть тесты и CI, документация на русском и описание на английском.
- 🌱 Сейчас развиваю **nalog-helper**: следующим будет патент и учёт праздничных дней в сроках уплаты.

## 🚀 Проекты

### 💸 Деньги и налоги

**[nalog-helper](https://github.com/codebywater/nalog-helper)** · [▶ Посчитать онлайн](https://codebywater.github.io/nalog-helper/)\
Сколько налогов платить ИП на УСН 6% и 15% и самозанятому, по выписке из банка. Находит доходы и расходы, считает налог и взносы (в том числе для ИП с работниками), сравнивает режимы, предупреждает о лимитах и выгружает календарь платежей в .ics. Есть Claude-скилл.\
`JavaScript` · `без зависимостей` · `Claude Code plugin` · `данные не покидают браузер`

**[subscription-hunter](https://github.com/codebywater/subscription-hunter)** · [▶ Проверить выписку](https://codebywater.github.io/subscription-hunter/)\
Находит забытые подписки и автосписания в банковской выписке, считает, сколько уходит в месяц и в год, и подсказывает, как отменить. Есть веб-версия, CLI и Claude-скилл.\
`Python` · `JavaScript` · `Claude Code plugin`

**[money-wrapped](https://github.com/codebywater/money-wrapped)** · [▶ Посмотреть свой год](https://codebywater.github.io/money-wrapped/)\
«Мой год в деньгах»: итоги года по банковской выписке в стиле Spotify Wrapped. Сторис о вашем годе: на что ушли деньги, любимое место, самый дорогой день, доставка в шавермах и ваш финансовый тип, плюс картинка для соцсетей.\
`JavaScript` · `Canvas` · `данные не покидают браузер`

### 🛒 Маркетплейсы

**[WB-OZON-AI-TEAM](https://github.com/codebywater/WB-OZON-AI-TEAM)**\
ИИ-команда для селлеров Wildberries и Ozon: 15 скиллов, которые считают юнит-экономику, следят за ценами конкурентов, делают карточки и ТЗ на инфографику, отвечают на отзывы и вопросы покупателей.\
`Claude Code` · `Codex` · `Cursor` · `Python`

**[Poizon-parsing](https://github.com/codebywater/Poizon-parsing)**\
Собирает из приложения Dewu (Poizon) цены по каждому размеру, артикулы, варианты доставки и таблицы размеров через автоматизацию интерфейса на настоящем телефоне (логика покрыта тестами, на живом телефоне пока не проверялась). Экспорт в CSV и Excel.\
`Python` · `uiautomator2` · `Appium`

### 💌 Веб-приложения

**[Our-Private-Universe](https://github.com/codebywater/Our-Private-Universe)** · [▶ Демо](https://codebywater.github.io/Our-Private-Universe/)\
Приватный архив воспоминаний для двоих: фото, таймлайн и письма, которые открываются в назначенную дату. Замок по времени работает на уровне базы данных (Postgres RLS), а не только в интерфейсе.\
`Next.js` · `TypeScript` · `Supabase` · `Tailwind`

### 🛠 Для разработчиков

**[vypiska](https://github.com/codebywater/vypiska)** · [▶ Проверить свою выписку](https://codebywater.github.io/vypiska/)\
Библиотека разбора CSV-выписок российских банков (Сбер, Т-Банк, Альфа, ВТБ, выписки 1С) в единый список операций: суммы в рублях счёта, отклонённые операции, кодировки, ничего не теряется молча. На ней работают nalog-helper, money-wrapped и subscription-hunter; есть версия для Python.\
`JavaScript` · `Python` · `без зависимостей`

**[github-city](https://github.com/codebywater/github-city)**\
Изометрический город из репозиториев для README профиля: высота дома — число коммитов, цвет — язык, днём солнце, ночью горят окна. Подключается как GitHub Action; город выше на этой странице нарисован им.\
`JavaScript` · `GitHub Action` · `SVG` · `без зависимостей`

### 🐬 Железо

**[flipper-os](https://github.com/codebywater/flipper-os)**\
Кастомная прошивка Flipper Zero на базе Unleashed: собственное меню Flipper OS Toolkit, анимация на рабочем столе и Patrol, журнал обходов с защитой записей через HMAC. Сборка и релизы через GitHub Actions.\
`C` · `Flipper Zero` · `GitHub Actions`

## 🧰 Стек

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?logo=anthropic&logoColor=white)

## 🤝 Как помочь

- ⭐ Поставьте звезду проекту, который пригодился: так его проще найти другим.
- 🐛 Нашли ошибку или неверную цифру в расчётах? Откройте issue в нужном репозитории.
- 🔧 Pull request'ы приветствуются. В каждом проекте есть инструкция, как запустить тесты.

<div align="center">

*Turning ideas into code, one line at a time.* 🌊

</div>
