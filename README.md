# FOP Accounting Helper

Простий локальний помічник для обліку доходів ФОП і розрахунку податків по кварталах та за рік.

Simple local helper for tracking FOP income and estimating quarterly and yearly taxes.

---

## 🇺🇦 Українська

### Що це

FOP Accounting Helper — невеликий вебзастосунок для простого обліку доходів ФОП протягом 2026 року.

Він допомагає:

- додавати надходження вручну;
- переводити валютні доходи у гривню за курсом НБУ;
- бачити дохід по кварталах і за весь рік;
- автоматично групувати операції по місяцях;
- рахувати 5% єдиного податку;
- рахувати 1% військового збору;
- за потреби враховувати ЄСВ;
- додавати повернення коштів;
- створювати та відновлювати локальні backup-файли;
- працювати українською або англійською мовою.

### Як користуватись

1. Відкрийте виписку вашого ФОП-рахунку за потрібний місяць або квартал.
2. Знайдіть фактичні надходження доходу від клієнтів.
3. Додайте кожне надходження окремо: дата, валюта та сума.
4. Для іноземної валюти натисніть **«Отримати курс»**, щоб отримати курс НБУ на дату надходження.
5. Перевірте розрахунок податків за квартал або за весь рік.

Не потрібно повторно додавати як дохід:

- обмін валюти;
- перекази між власними рахунками;
- виведення коштів на власну картку.

### Приватність

Застосунок не використовує акаунти або серверну базу даних.

Ваші операції зберігаються локально у `localStorage` вашого браузера.

Інші користувачі, які відкривають той самий сайт, не бачать ваших даних.

Для збереження копії даних можна використовувати **Download Backup / Завантажити копію** у налаштуваннях.

### Важливо

Цей застосунок створений як зручний допоміжний інструмент і не замінює професійного бухгалтера або офіційну податкову консультацію.

Перед сплатою податків або поданням звітності перевіряйте актуальні ставки, правила та суми.

Розробник не несе відповідальності за втрату локальних даних, помилки у введених даних або фінансові чи податкові рішення, прийняті на основі розрахунків застосунку.

---

## 🇬🇧 English

### What is it?

FOP Accounting Helper is a small local-first web app for tracking Ukrainian FOP income during 2026.

It can help you:

- manually record income;
- convert foreign-currency income to UAH using the NBU exchange rate;
- view quarterly and yearly totals;
- group transactions by month;
- estimate the 5% single tax;
- estimate the 1% military levy;
- optionally include USC;
- record refunds;
- download and restore local backups;
- switch between Ukrainian and English.

### How to use

1. Open your FOP bank statement for the required month or quarter.
2. Find the actual income payments received from clients.
3. Add each payment separately with its date, currency and amount.
4. For foreign-currency income, use **Get rate** to retrieve the NBU exchange rate for that date.
5. Review your estimated quarterly or yearly taxes.

Do not enter the following again as new income:

- currency exchange transactions;
- transfers between your own accounts;
- withdrawals to your personal account or card.

### Privacy

The app does not require an account or server-side database.

Your accounting data is stored locally in your browser using `localStorage`.

Other people opening the same website cannot see your records.

You can create a portable backup from **Settings → Download Backup**.

### Disclaimer

This application is intended as a simple accounting assistant and does not replace a professional accountant or official tax advice.

Always verify current tax rules, rates and important amounts before filing reports or making tax payments.

The developer is not responsible for lost local data, incorrect information entered by the user, or financial or tax decisions made based on the application's calculations.

---

## Technology

- HTML
- CSS
- Vanilla JavaScript
- Browser `localStorage`
- NBU exchange rate API
- No backend
- No database
- No analytics or tracking

## Deployment

The app is fully static.

It can be hosted using services such as:

- GitHub Pages
- Cloudflare Pages
- Netlify
- any standard static web hosting

Upload the contents of the deploy package to the same website directory and serve `index.html`.

---

© 2026 Yaroslav Patrin
