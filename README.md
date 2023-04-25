# Explore With Me

Explore With Me это микросервисное приложение - афиша. В нём можно предложить любое событие от концерта до похода в музей и собрать компанию для участия в нём.

Свободное время - это ценность. Это приложение помогает сократить время на поиск интеренсных событий, учитывая все возможные мероприятия и расписание друзей. 
Теперь будет легко выбрать интересное событие, место встречи и пригласить всех желающих.

<img width="1440" alt="ewm" src="https://user-images.githubusercontent.com/105507007/234380691-c8ccda45-2478-48df-8a8f-ae8f44746654.png">

Приложение строится на двух сервисах:
- Main сервис содержит всё необходимое для работы продукта;
- Сервис статистики хранит количество просмотров и позволяет делать различные выборки для анализа работы приложения.

API основного сервиса в свою очередь делится на три части:
- публичная доступна без регистрации любому пользователю сети;
- закрытая доступна только авторизованным пользователям;
- административная — для администраторов сервиса.
- 
![ewmds](https://user-images.githubusercontent.com/105507007/234381805-44470f19-045d-4d8b-a03a-21d4f171baee.png)

Применяемы технологии:
- Java 11
- Spring Boot
- Docker
- Hibernate
- PostgreSQL
- Maven
- Lombok
- Junit5
- Postman
- REST

#### Схема базы данных:

![ewmSch](https://user-images.githubusercontent.com/105507007/234383186-14ea6986-613c-4ad0-b88a-6af4a76fbcd1.png)
