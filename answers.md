1. What is the difference between a function and a procedure in PostgreSQL?
   Функція завжди щось повертає, а процедура може нічого не повертати, це лише послідовність дій. 
2. Can a trigger be executed manually? Why or why not?
   Ні, тому що тригер спрацьовує автоматично, його не можливо і не потрібно додатково викликати. Він спрацьовує після або перед чітко вказаних команд.
4. What are the advantages and disadvantages of storing business logic inside the database?
   переваги:
Все зберігається в одному місці, і це може пришвидшити роботу, якщо потрібно робити дуже багато запитів,
У великих додатках складніше керувати всіма правами доступу, перенесення логіки в субд зробить програму більш безпечною
  недоліки:
більше навантаження на базу даних, що робить масштабування складнішим,
на sql складніше писати на високому рівні абстракції,
залежність від  діалекту database,
складність роботи в команді,

для 3 запитання використовувала такі ресурси:
https://softwareengineering.stackexchange.com/questions/158534/pros-and-cons-of-holding-all-the-business-logic-in-stored-procedures-in-web-appl,
https://dev.to/zenstack/business-logic-inside-database-how-evil-is-it-1f1f
