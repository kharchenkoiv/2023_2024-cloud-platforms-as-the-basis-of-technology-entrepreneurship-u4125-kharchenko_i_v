University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FTMI](https://ftmi.itmo.ru/)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)
Year: 2024
Group: U4125
Author: Kharchenko Ivan Vasilyevich
Lab: Lab2
Date of create: 14.10.2024
Date of finished: 10.14.2024

## Шаг 1. 
Создаем клауд ран с минимальной конфигурацией (кнопка create service).
![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/60c45ba6-e008-4c9f-be47-5914e35d893e)

Видим сервис во вкладке revisions.

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/9023f060-4ca6-45e9-88a1-0a6b1cc4a598)

## Шаг 2. 
Переходим по ссылке, видим, что сервис запустился.

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/8c53114c-fc85-4d6b-a9c4-ca9f500055ed)

Переходим по кнопке view in cloud console.

## Шаг 3. 
В консоли смотрим метрики и логи. 

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/79704630-be8a-4c1f-b27a-d4bfdce1af98)

В логах видим GET запросы в браузере, время их отправок. 

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/7f419871-a12e-45fb-b101-591c67b415b8)

В метриках видим информацию о данных, количестве запросов, задержке. Также можно настроить дополнительные графики из шаблонов. 

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/1cbca188-bc49-40f2-a905-d761da87c56d)

## Шаг 4. 
Изменяем Cloud Run, поменяв порт на 8090. Информация об изменении сохранилась в метриках и в логах.

![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/78ffc8b3-72d9-422b-af82-2fa9c9b22285)

Во вкладке revisions видно, что создалась вторая версия, между ними можно переключаться. 
![image](https://github.com/imkonyahin/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-konyahin_i_m/assets/167180041/1175c71e-2678-48e6-9e1a-379eea3cd44d)

Информация о переключении между версии также сохранятеся в логах и метриках.
