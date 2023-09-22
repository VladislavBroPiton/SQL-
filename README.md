# SQL
**Язык структурированных запросов (SQL)** – это язык программирования для хранения и обработки информации в реляционной базе данных. Реляционная база данных хранит информацию в табличной форме со строками и столбцами, представляющими различные атрибуты данных и различные связи между значениями данных. Инструкции SQL можно использовать для хранения, обновления, удаления, поиска и извлечения информации из базы данных. Можно также использовать SQL для поддержания и оптимизации производительности базы данных.
**Язык структурированных запросов (SQL)** – популярный язык запросов, который часто используется во всех типах приложений. Аналитики данных и разработчики изучают и используют SQL, потому что это решение хорошо интегрируется с различными языками программирования. Например, они могут внедрять SQL-запросы с языком программирования Java для создания высокопроизводительных приложений обработки данных с основными системами баз данных SQL, такими как Oracle или MS SQL Server. Решение SQL также довольно просто в освоении, так как в его утверждениях используются общепринятые английские ключевые слова.
### История SQL 
Решение **SQL** было изобретено в 1970-х годах на основе реляционной модели данных. Изначально оно было известен как структурированный английский язык запросов (SEQUEL). Позднее этот термин был сокращен до SQL. Компания Oracle, ранее – Relational Software, стала первым поставщиком, предложившим коммерческую систему управления реляционными базами данных SQL.
### Таблица SQL
**Таблица SQL** – это базовый элемент реляционной базы данных. Таблица базы данных SQL состоит из строк и столбцов. Инженеры баз данных создают связи между несколькими таблицами базы данных, чтобы оптимизировать пространство для хранения данных.
Например, инженер баз данных создает таблицу SQL для продуктов в магазине: 
0001 | Матрас | Цвет 1 
:--|:-------:|-----------------:
0002 | Подушка | Цвет 2

Затем инженер базы данных связывает таблицу продуктов с таблицей цветов с *идентификатором цвета*:
### Идентификатор цвета Название цвета 
Цвет 1 | Голубой 
:--|-----------------:
Цвет 2 | Красный

### Популярные системы управления базами данных   
**Системы управления базами данных (СУБД)** — это инструменты, с помощью которых пользователь обращается к данным, изменяет их или создаёт. СУБД функционируют как менеджеры по работе с базами данных, которые «говорят» на их языке программирования. В российских и зарубежных компаниях используют шесть популярных СУБД:
### 1. Oracle
Объектно-**реляционная** СУБД, созданная одноимённой компанией-лидером на рынке. Преимущества Oracle: быстрая установка и настройка, возможность расширять функционал, практичность и надёжность. Но лицензия стоит дорого, поэтому Oracle обычно используют крупные корпорации.
### 2. MySQL  
**Реляционная СУБД** с открытым исходным кодом, то есть доступна для просмотра, исправления ошибок и создания новых версий программ. MySQL — бесплатная, быстрая и гибкая система, подходящая для таблиц разных типов.  
### 3. Microsoft SQL Server  
Оптимальная СУБД для операционных систем Windows, но совместима и с Linux. Легко интегрируется с другими продуктами Microsoft, удобна в использовании, но потребляет много ресурсов, а лицензия стоит дорого.   
### 4. PostgreSQL   
Объектно-**реляционная** СУБД, которую используют для сайтов, сервисов и платформ. Бесплатный доступ и поддержка многих языков программирования делают эту СУБД одной из самых популярных. По её лицензии создано немало расширенных версий, в том числе для коммерческого использования.   
### 5. Apache Cassandra   
В отличие от вышеназванных, Cassandra — **нереляционная** СУБД. Она разработана на языке Java и принадлежит фонду Apache Software Foundation. Система хранит данные по модели семейства столбцов и «ключ-значение», распределяет данные в несколько дата-центров и легко масштабируется при увеличении объёма информации.   
