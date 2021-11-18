# Проектирование БД


   <h2> :fire: Список сущностей и свойств </h2>
    <table>
      <tr>
        <th>Сущность</th>
        <th>Свойство</th>
        <th>Пояснение</th>
      </tr>
      
      
    </table>

   <h2> :fire: Список связей</h2>
    <table>
      <tr>
        <th>Название связи</th>
        <th>Что связывает</th>
        <th>Суть</th>
      </tr>
      
      <tr>
        <td rowspan="2"><b>UserDorm</b></td>
        <td><i>Пользователь</i></td>
        <td rowspan="2">Показывает, в каком общежитии живёт пользователь</td>
      </tr>
      <tr>
        <td><i>Общежитие</i></td>
      </tr>
      
      <tr>
        <td rowspan="2"><b>UserRoom</b></td>
        <td><i>Пользователь</i></td>
        <td rowspan="2">Показывает, в какой комнате живёт пользователь</td>
      </tr>
      <tr>
        <td><i>Комната</i></td>
      </tr>
      
      <tr>
        <td rowspan="2"><b>RoomDorm</b></td>
        <td><i>Комната</i></td>
        <td rowspan="2">Показывает, в каком общежитии расположена комната</td>
      </tr>
      <tr>
        <td><i>Общежитие</i></td>
      </tr>
      
      <tr>
        <td rowspan="2"><b>UserOffers</b></td>
        <td><i>Пользователь</i></td>
        <td rowspan="2">Показывает, какие товары готов обменять пользователь</td>
      </tr>
      <tr>
        <td><i>Товары (любое кол-во сущностей)</i></td>
      </tr>
      
      <tr>
        <td rowspan="2"><b>Bargains</b></td>
        <td><i>Сделка</i></td>
        <td rowspan="2">Фиксирует сделки, показывает какие товары были обменяны друг на друга</td>
      </tr>
      <tr>
        <td><i>Товары (2 штуки: от одной и от другой стороны)</i></td>
      </tr>
    </table>
  

    <h2> :fire: Модель "сущность - связь"</h2>
    ![bd](https://user-images.githubusercontent.com/80625335/142430903-121120dd-8c73-485d-ba1e-5166827508fe.png)


  

    <h2> :fire: Логическая модель</h2>
    ![dbr](https://user-images.githubusercontent.com/80625335/142435659-afac2460-f4db-4026-8cdb-c7002f776c5c.png)




   
