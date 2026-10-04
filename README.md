# Assignment #3. Responsive Web Design

## Информация о студенте
* **Имя:** Адильжан Кайргалиев
* **Группа:** SE-2540

---

## Описание проекта
В этой лабораторной работе я сделал адаптивный сайт интернет-магазина (StrideHouse). Здесь я закрепил работу с медиа-запросами (Media Queries), гибкими контейнерами, своей 12-колоночной сеткой, адаптивным навбаром и блоками портфолио под разные экраны (мобилки, планшеты, ПК).

---

## Задачи и задания

### Часть 1. Медиа-запросы (Media Queries)
* **Задача 0. Адаптивная типографика**
  * *Что сделал:* Сделал так, чтобы заголовки и текст меняли размер шрифта в зависимости от того, с какого устройства открыта страница (телефон, планшет или компьютер).
  * *Скриншот:*
    <img width="959" height="868" alt="image" src="https://github.com/user-attachments/assets/e4ba1e77-fea8-4f7e-bc63-4bd44959fbf5" />
    <img width="533" height="695" alt="image" src="https://github.com/user-attachments/assets/adc942bc-2491-4d07-b57e-95df324c8760" />

* **Задача 1. Адаптивный макет (без Bootstrap)**
  * *Что сделал:* Создал три блока («Free Shipping», «100% Authentic», «Easy Returns»). На компьютере они стоят в один ряд, на планшете — по два в ряд, а на телефоне выстраиваются друг под другом вертикально.
  * *Скриншот:*
    <img width="951" height="233" alt="image" src="https://github.com/user-attachments/assets/ad61c249-d071-4253-a172-0824489f22f5" />
    <img width="695" height="287" alt="image" src="https://github.com/user-attachments/assets/1862f592-576b-4e1f-ad82-0bdd472975e1" />
    <img width="403" height="643" alt="image" src="https://github.com/user-attachments/assets/e45be184-e0bb-4467-979a-4c541c932531" />

### Часть 2. Сеточная система (Grid)
* **Задача 2. Адаптивные колонки**
  * *Что сделал:* Сделал блоки категорий через 12-колоночную сетку. На десктопе они делят ширину на 3 равные части (`col-lg-4`), на планшете первые два идут рядом, а третий падает на второй ряд (`col-md-12`), а на мобилках всё идет в один столбик (`col-12`).
  * *Скриншот:*
    <img width="396" height="537" alt="image" src="https://github.com/user-attachments/assets/b83b78a1-56c1-4170-a933-490cef850dd3" />
    <img width="962" height="451" alt="image" src="https://github.com/user-attachments/assets/b92dc603-45d7-4933-a6db-89a909caa1c3" />
    <img width="984" height="234" alt="image" src="https://github.com/user-attachments/assets/9f7b6f8a-5adf-4d81-aefb-bf8dce4c5700" />

* **Задача 3. Адаптивная навигация (навбар)**
  * *Что сделал:* Сделал шапку сайта с логотипом слева и ссылками справа. На маленьких экранах меню прячется и открывается при клике на иконку-гамбургер (сделал через чекбокс без использования JS).
  * *Скриншот:*
    <img width="968" height="123" alt="image" src="https://github.com/user-attachments/assets/01def1e1-87c8-408c-b054-5d9b3f9f2e91" />
    <img width="958" height="286" alt="image" src="https://github.com/user-attachments/assets/60679290-a063-4fd4-959a-4fed2b4cc919" />
    <img width="423" height="290" alt="image" src="https://github.com/user-attachments/assets/6fc1d641-c674-4631-b81c-b824c1416e3b" />

### Часть 3. Комбинированный проект
* **Задача 4. Страница портфолио / каталога**
  * *Что сделал:* Собрал общую страницу, объединив шапку-навбар, сетку с карточками товаров слева, сайдбар с фильтрами/информацией справа и подвал внизу. Написал медиа-запросы, чтобы на мобилках лишний текст в сайдбаре скрывался и всё выглядело аккуратно.
  * *Скриншот:*
    <img width="1904" height="1035" alt="image" src="https://github.com/user-attachments/assets/c86508d8-e3ca-4391-9946-1f6981f91c3a" />
    <img width="952" height="925" alt="image" src="https://github.com/user-attachments/assets/eb304a98-2e69-4c2c-987d-5737e6dad754" />
    <img width="394" height="915" alt="image" src="https://github.com/user-attachments/assets/2a1de2ab-79ce-4bcd-bcc3-e38879dbd8b6" />

---

## Как я это делал (Ход работы)
1. Создал структуру файлов `index.html` и `style.css`, подключил шрифты и мета-тег viewport.
2. Написал стили с медиа-запросами для текста и блоков (Задачи 0 и 1).
3. Сверстал сеточные блоки для категорий и товаров (Задача 2).
4. Добавил интерактивный навбар с гамбургером (Задача 3).
5. Собрал финальную секцию магазина и проверил через инспектор кода, чтобы на всех экранах ничего не съезжало.

---

## Ссылки
* **Репозиторий на GitHub:** [ссылка]
* **Сайт (GitHub Pages):** [ссылка]
