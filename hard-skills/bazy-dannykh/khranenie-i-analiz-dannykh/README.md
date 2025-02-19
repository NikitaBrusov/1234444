# 📎 Хранение и анализ данных

<figure><img src="../../../.gitbook/assets/osi (13).jpg" alt=""><figcaption><p>Храненение и анализ данных</p></figcaption></figure>

## Архитектура хранилища данных

Довольно часто традиционная архитектура хранилища данных имеет трехуровневую структуру, состоящую из следующих ступеней:

### **Нижний уровень (Bottom Tier)**

Этот уровень содержит сервер базы данных, используемый для извлечения данных из множества различных источников, например, из транзакционных баз данных, используемых для интерфейсных приложений.

Основные компоненты этого уровня:

* **Источники данных**

Источниками данных могут являться например: реляционные базы данных, сведения с веб-сайта, из биллинговой системы, CRM- и ERP-систем и других баз данных.

* **ETL обработка**

ETL (Extract, Transform, Load) — извлечение, преобразование и загрузка. То есть процесс, с помощью которого данные из нескольких систем объединяют в единое хранилище данных (DWH).

* **DWH**

Data Warehouse (DWH) — хранилище, предназначенное для сбора и аналитической обработки исторических данных организации. Анализ помогает руководителям видеть цельную картину бизнеса и принимать решения, как развивать отдельные направления или бизнес в целом.

### **Средний уровень (Middle Tier)**

Средний уровень содержит сервер OLAP, который преобразует данные в структуру, лучше подходящую для анализа и сложных запросов. Сервер OLAP может работать двумя способами: либо в качестве расширенной системы управления реляционными базами данных, которая отображает операции над многомерными данными в стандартные реляционные операции (ROLAP), либо с использованием многомерной модели (MOLAP), которая непосредственно реализует многомерные данные и операции.

### **Верхний уровень (Top Tier)**&#x20;

Верхний уровень — это уровень клиента. Этот уровень содержит BI-инструменты, используемые для высокоуровневого анализа данных, создания отчетов и анализа данных.

Актуальные инструменты бизнес-аналитики (BI) вкупе с возможностями DWH позволяют принимать управленческие решения с гарантированным результатом. Благодаря эффективному анализу больших массивов данных менеджмент компании также может выдвигать гипотезы, построенные на реальных бизнес-показателях, и тестировать их.







Источники:

* [https://habr.com/ru/articles/441538/](https://habr.com/ru/articles/441538/)
* [https://selectel.ru/blog/data-warehouse/](https://selectel.ru/blog/data-warehouse/)
* [https://cloud.mts.ru/cloud-thinking/blog/data-warehouse/](https://cloud.mts.ru/cloud-thinking/blog/data-warehouse/)
