**Задание 1**.  CRUD (create, read, update, delete).
У вас есть всего 1 табличка User
 
**isAdmin** – в приложении это Boolean переменная.
Необходимо реализовать стандартное crud приложение, которое отображаем список всех юзеров в базе (с пейджингом). С возможностью их удаления, редактирования, добавления новых. И поиска по уже существующим.
По какому полю искать – каждый решает для себя сам. Можно ограничиться полем name, можно реализовать фильтр для любого поля. 
[[https://github.com/andreichernov/CrudAppTry/blob/master/readme_img/db_table_example.png|alt=octocat]]

Требуемые технологии: 
•	Maven (для сборки проекта)
•	Spring
•	Hibernate (для маппинга сущностей приложения на БД, и работы с БД)
•	Tomcat 7,8 (для тестирования своего приложения)
•	Mysql (база данных). Для упрощения тестирования называйте все свою базу test, с логином и паролем root (нам  не нужно будет для тестирования создавать кучу лишних и ненужных баз)
•	Frontend: angular.js or Vaadin (можно и GWT, но будут сложности) or ZK framework or Spring MVC
Версии можно смело брать самые последние. Конфликтов быть не должно.
Приложение должно быть в виде проекта, который собирается с помощью maven. Обязательно должен присутствовать скрипт для создания и наполнения тестовыми данными вашей базы данных. Если для старта приложения после успешного деплоя нужны какие-то дополнительные махинации или танцы с бубном – просьба все это описать в каком-нибудь readme в корне проекта.
Визуальную часть проектов не рисую, т.к. хочу увидеть, как каждый сам реализует и посчитает нормальной свою реализацию задачи.
Огромная просьба: тестируйте свое приложение. Бывало много случаев, когда присылали полностью нерабочее приложение, или с огромным количеством багов.
