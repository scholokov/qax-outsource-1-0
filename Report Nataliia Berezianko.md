#Репорт згідно виконаному завданню:
| Назва | Коментар
| -- | ---
| Завдання | [Посилання](https://www.qax-camp.com.ua/courses/qax-outsource-1-0/lessons/out-1-0-reporting/)
| QA | Nataliia Berezianko
| Дата виконання | 07.12.2023-06.01.2024
   
##Висновки

Тестування проєкту “QAX-Outsours 1.0” було проведено для Desktop, Tablet, Mobile Phone на браузері Chrome та операційних системах Android, iOS.
В результаті тестування виявлено 22 невдало пройдених тестів та заведено на них баг-репорти. 
Згідно результатів тестування можна рекомендувати реліз проєкту для Desktop, але після виправлення заведених баг-репортів.
Не рекомаендується реліз для Tablet та Mobile Phone, так як в процесі тестування виявлено, що Веб-сторінка зовсім не адаптується під необхідні розміри та не читабельна для Mobile Phone.

## Баг-репорти, відсортовані за пріоритетом
   |#     | Назва | Посилання | Пріоритет
   | ---- |  ---- | --------- | ------
   | 1 | Outsource 1.0 / The Website page and Content text are not adapted when the page is scaled (Tablet&Mobile) | https://github.com/scholokov/qax-outsource-1-0/issues/71 | high
   | 2 | Outsource 1.0 / The Home Page has HTML errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/39 | medium
   | 3 | Outsource 1.0 / The "About" Page has HTML errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/40 | medium
   | 4 | Outsource 1.0 / The "Who we are" Page has HTML errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/41 | medium
   | 5 | Outsource 1.0 / The "Our services" Page has HTML errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/42 | medium
   | 6 | Outsource 1.0 / The "Cooperation offer" Page has HTML errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/43 | medium
   | 7 | Outsource 1.0 / The "Contacts" Page has HTML errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/44 | medium
   | 8 | Outsource 1.0 / The Home Page has CSS errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/45 | medium
   | 9 | Outsource 1.0 / The "About" Page has CSS errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/46 | medium
   | 10 | Outsource 1.0 / The "Who we are" Page has CSS errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/48 | medium
   | 11 | Outsource 1.0 / The "Our services" Page has CSS errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/49 | medium
   | 12 | Outsource 1.0 / The "Cooperation offer" Page has CSS errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/51 | medium
   | 13 | Outsource 1.0 / The "Contacts" Page has CSS errors when checked by the Validator | https://github.com/scholokov/qax-outsource-1-0/issues/53 | medium
   | 14 | Outsource 1.0 / The "Contacts" Page has Error when checked by the Console | https://github.com/scholokov/qax-outsource-1-0/issues/65 | medium
   | 15 | Outsource 1.0 / On the Navigation menu the text "Cooperation offer" shifts down when the screen size is 150% | https://github.com/scholokov/qax-outsource-1-0/issues/72 | medium
   | 16 | Outsource 1.0 / On the Bottom Bar, the Phone icon linked to the "Contact" Page when clicked on it | https://github.com/scholokov/qax-outsource-1-0/issues/67 | medium
   | 17 | Outsource 1.0 / On the "Contact" Page the Phone icon and the Phone number linked to the "Contact" Page when clicked on it | https://github.com/scholokov/qax-outsource-1-0/issues/68 | medium
   | 18 | Outsource 1.0 / On the "Contacts" Page the text "Cooperation offer" and the link "LinkedIn" shifts | https://github.com/scholokov/qax-outsource-1-0/issues/70 | medium
   | 19 | Outsource 1.0 / On the "Contacts" Page the Arrow cursor does not change to the Hand cursor when hovering over links | https://github.com/scholokov/qax-outsource-1-0/issues/66 | low
   | 20 | Outsource 1.0 / On the “Home” and “Contact” pages, content headings are located in the center, and on other pages - on the left | https://github.com/scholokov/qax-outsource-1-0/issues/69 | low
   | 21 | Outsource 1.0 / On the Bottom Bar the Copyright has a symbol "(c) " | https://github.com/scholokov/qax-outsource-1-0/issues/73 | low
   | 22 | Outsource 1.0 / On the "Home "page, the Content blocks are the active areas when we click anywhere | https://github.com/scholokov/qax-outsource-1-0/issues/74 | low

### Результати тестування:
   
   - [Desktop](https://app.testomat.io/projects/qax-outsource-1-0/runs/ee7c00db),
   - [Tablet](https://app.testomat.io/projects/qax-outsource-1-0/runs/133ac396),
   - [Mobile](https://app.testomat.io/projects/qax-outsource-1-0/runs/3c69b785).
   
