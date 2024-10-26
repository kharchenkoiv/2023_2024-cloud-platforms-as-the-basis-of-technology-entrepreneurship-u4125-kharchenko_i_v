University: ITMO University \
Faculty: FTMI Course: Cloud platforms as the basis of technology entrepreneurship \
Year: 2024 \
Group: U4125\
Author: Kharchenko Ivan Vasilyevich\
Lab: Lab4 \
Date of create: 20.10.2024 \
Date of finished: --.10.2024

## Шаг 1.
Инфраструктура схемы приложения (пользователь будет взаимодействовать с ним через телеграм бота).

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/35464fa5-3eb9-4804-b266-4746b14ff498)

## Шаг 2.
Поиск оптимального решения исходя из предполагаемых нагрузок. 

**Начальное состояние** (10-50 пользователей):
VM: e2-micro 0.25-2 vCPU 1 GB memory — 7.11$
SQL Cloud: PostgreSQL 1 vCPU 0.6 GB memory — 9.5$

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/07999722-a344-446f-9103-71f563a3ef02)

Итог — 16.61$

Для MVP выбираем самый экономичный набор по характеристикам.

**Тестирование партнёрами** (100 - 150 человек):
VM: e2-small 0.5-2 vCPU 2 GB memory — 13.23$
SQL Cloud: PostgreSQL 1 vCPU 1.7 GB memory — 29$

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/b7f7a576-605d-4067-891e-246f463e78aa)

Итог — 42.21$

Рост числа пользователей увеличивает нагрузку на приложение, поэтому требуется больший объем ресурсов.

**Продовое решение** (300+ пользователей):
VM: t2d-standard-1 (1 vCPU, 4 GB memory) - $31.84 
У данной виртуальки большой запас по следующим шагам нагрузки, для продового решени в 300 пользователей хватит и версии на 4Гб памяти, но при необходимости можно будет увеличить до 60 vCPU, 240 GB memory.

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/46a96d9f-5064-4e3a-8edb-43e661074fc6)

SQL Cloud: PostgreSQL 1 vCPU 3.75 GB memory — 66.5$
Итог — 98.34$

Таким образом цена за облако в начальном состоянии равняется 16$ (а это от 1 до 3 $ за пользователя/мес), и вырастает до 100$/мес на 300 пользователей (что уже равняется 0,3 $ в месяц).

