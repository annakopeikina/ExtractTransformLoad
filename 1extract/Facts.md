#

1. Факты, связанные с транзакциями __(Transaction facts)__ основаны на
отдельных событиях. Типичный пример — телефонный звонок или снятие
денег со счета с помощью банкомата.

2. Факты, связанные с «моментальными снимками» __(Snapshot facts)__ основаны
на состоянии объекта (например, банковского счета) в определенный момент,
например на конец дня или месяца. Типичный пример — дневная выручка.

3. Факты, связанные с элементами документа __(Line-item facts)__ основаны на
документе (например, счете за товар или услуги) и содержат подробную
информацию о его элементах: например, о количестве, цене, проценте
скидки.
4. Факты, связанные с событиями или состоянием объекта __(Event or state facts)__
представляют возникшие события без подробностей о них: например, просто
факт продажи или факт ее отсутствия без дополнительных объяснений.

Таблица фактов содержит объединенный __ключ, который является объединенным первичным ключом всех таблиц измерений__ . Объединенный ключ должен
однозначно идентифицировать строку в таблице фактов
