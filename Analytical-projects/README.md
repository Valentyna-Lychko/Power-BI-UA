# Pizza Sales Analysis

---

## Опис дашборду

### Загальний огляд:
Цей дашборд розроблений для аналізу продажів піци з урахуванням інтересів як власників піцерії, так і відвідувачів. Він складається з чотирьох сторінок, кожна з яких надає унікальні інсайти для кращого розуміння ключових аспектів бізнесу. Кожна сторінка має навігаційні кнопки для зручного переходу між вкладками.

### Сторінки дашборду:
- **Overview** - Pizza Business Performance: Trends and Key Metrics
- **Sales** - Revenue, Orders, and Quantity Analysis
- **Price** - Pizza Pricing by Size and m²
- **Leaders** - Top Pizzas by Size, Price, and Popularity

- **відео**
<video width="600" controls>
    <source src="https://raw.githubusercontent.com/Valentyna-Lychko/Power-BI-UA/main/Dashboard_Videos/Pizza_video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>


- **відео2**
<video width="600" controls>
    <source src="https://github.com/Valentyna-Lychko/Power-BI-UA/issues/1" type="video/mp4">
    Your browser does not support the video tag.
</video>


Дані для аналізу взяті з Kaggle, оброблені у Power Query. Було розраховано міри в DAX, додано параметр для покращення інтерактивності дашборду.


![](https://github.com/Valentyna-Lychko/Power-BI-UA/blob/main/Dashboard_Images/Pizza_All.png)


---

## Детальний опис сторінок:

### Overview - Pizza Business Performance: Trends and Key Metrics
Цей розділ містить загальний огляд бізнесу, включаючи ключові показники продажів та основні тенденції. Графіки на сторінці демонструють зміни у доходах, замовленнях та кількості піц за часом.

#### Основні елементи:
- **Картки (cards) з ключовими показниками:**
  - Total Revenue
  - Total Orders
  - Total Quantity
  - Average Check
  - Average Price
  - Number of Pizzas
- **Комбінований графік (Combo Chart) – "Revenue & Orders by Month":**
  - Стовпці (бар-чарт) показують загальний дохід по місяцях.
  - Лінія (лінійний графік) відображає загальну кількість замовлень.
  - Значних сезонних коливань не спостерігається.
- **Стовпчастий графік (бар-чарт) – "Total Quantity by Size & Category":**
  - Відображає розподіл кількості проданих піц за категоріями та розмірами.
  - Найбільший попит на піцу:
    - Класична піца розміру S.
    - Вегетаріанська і куряча піца розміру L.
- **Лінійний графік (area chart) – "Average Orders Per Day Week":**
  - Пік припадає на п’ятницю, найменше замовлень у неділю.
- **Лінійний графік (area chart) – "Average Orders Per Hour Per Day":**
  - Найбільше замовлень припадає на 18:00, найменше – на ранкові години.
    

![](https://github.com/Valentyna-Lychko/Power-BI-UA/blob/main/Dashboard_Images/Pizza_Overview.png)

---

### Sales - Revenue, Orders, and Quantity Analysis
Цей розділ надає детальну інформацію про продажі по категоріях та розмірах піц.

#### Основні елементи:
- **Горизонтальний стовпчастий графік (бар-чарт) – "Orders за категорією pizza_category":**
  - Відображає кількість замовлень у різних категоріях піци.
- **Структурне дерево (санкі-діаграма) – "size → category → name":**
  - Візуалізує розподіл замовлень за розмірами піци.
- **Горизонтальний стовпчастий графік (бар-чарт) – Рейтинг піц за кількістю замовлень.**
- **Кнопки перемикання (Revenue, Orders, Quantity):**
  - Змінюють параметр аналітики на дашборді.
    

![]( https://github.com/Valentyna-Lychko/Power-BI-UA/blob/main/Dashboard_Images/Pizza_Sales.png)

---

### Price - Pizza Pricing by Size and m²
Цей розділ зосереджений на цінах піц за розмірами та на порівнянні вартості піци по площі.

#### Основні елементи:
- **Таблиця – "The price of pizza by size":**
  - Відображає ціни піц різних розмірів.
- **Діаграма-дерево (treemap) – "Median price per m²":**
  - Відображає медіанну ціну піц за квадратний метр.
    

![]( https://github.com/Valentyna-Lychko/Power-BI-UA/blob/main/Dashboard_Images/Pizza_Price.png)

---

### Leaders - Top Pizzas by Size, Price, and Popularity
Цей розділ представляє рейтинг піц, що лідирують за різними критеріями.

#### Основні елементи:
- **Таблиці:**
  - Найпопулярніша піца (Most Popular Pizza).
  - Найдешевша піца (Min Priced Pizza).
  - Найбільша піца (Big Pizza).
- **Діаграма-дерево (treemap) – "Promising pizzas":**
  - Відображає піци, на які слід звернути увагу.
- **Таблиця – "Pizza Sizes":**
  - Дані про розміри та площу піц.
    

![](https://github.com/Valentyna-Lychko/Power-BI-UA/blob/main/Dashboard_Images/Pizza_Leaders.png)

---

## Додаткові особливості:
- На кожній сторінці дашборда розміщені кнопки навігації для швидкого переходу між вкладками.

---

## Файли в проєкті:

- **Power BI файл**
[Pizza_Sales_Analysis.pbix](https://github.com/Valentyna-Lychko/Power-BI-UA/blob/main/Dashboards/Pizza_Sales_Analysis.pbix):  
**Завантажте для детального перегляду інтерактивного дашборду.**

  
- **Відео-демонстрація:** 
Перегляньте відео, щоб побачити інтерактивність та функціонал дашборду:  [Pizza Sales Analysis - відео](https://github.com/Valentyna-Lychko/Power-BI-UA/blob/main/Dashboard_Videos/Pizza_video.mp4)


---

## Висновки і рекомендації:
Цей дашборд дає змогу детально аналізувати ефективність продажів піцерії, виявляти найпопулярніші страви, а також оптимізувати ціноутворення.

### Рекомендації:
- **Оптимізуйте меню:** Використовуйте дані з розділу "Sales" для визначення найбільш популярних видів піц.
- **Цінова стратегія:** Аналізуйте дані з розділу "Price" для коригування вартості піц.
- **Оптимізація персоналу:** Використовуйте графіки з "Overview" для планування роботи персоналу (пік продажів – п’ятниця, 18:00).

Ці рекомендації допоможуть зробити бізнес більш ефективним та покращити продажі за допомогою аналітики Power BI.

