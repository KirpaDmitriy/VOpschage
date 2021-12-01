# Проектирование способов взаимодействия с приложением


<div align="center">
&#128293; &#128293; &#128293; &#128293; &#128293; &#128293;
</div>
<h2>Список элементов управления</h2>
<ul>
    <li>
        <h3><b>Неавторизованный пользователь</b></h3>
        <ul>
            <li><i>Начальная страница</i></li>
            <li><i>Авторизация</i></li>
            <li><i>Регистрация</i></li>
        </ul>
    </li>
    <li><a name="authorised_user"></a>
        <h3><b>Авторизованный пользователь (АП)</b></h3>
        <ul>
            <li><i>Главная страница = Список страниц комнат общежития</i></li>
            <li><i>Просмотр выбранной страницы комнаты</i></li>
            <li><i>Написание сообщения на страницу выбранной комнаты</i></li>
            <li><i>Написание сообщений от имени своей комнаты</i></li>
            <li><i>Создание отзыва о комнате</i></li>
            <li><i>Редактирование информации о своей комнате</i></li>
            <li><i>Редактирование информации своего профиля</i></li>
            <li><i>Просмотр информации об общежитии</i></li>
            <li><i>Просмотр уведомлений от администрации</i></li>
        </ul>
    </li>
    <li><a name="admin"></a>
        <h3><b>Админ</b></h3>
        <ul>
            <li><i><b><a href="#authorised_user">Элементы, доступные АП</a></b></i></li>
            <li><i>Редактирование рейтинга АП</i></li>
        </ul>
    </li>
    <li>
        <h3><b>Суперадмин</b></h3>
        <ul>
            <li><i><b><a href="#admin">Элементы, доступные админу</a></b></i></li>
            <li><i>Изменение роли пользователя</i></li>
            <li><i>Редактирование информации об общежитии</i></li>
            <li><i>Отправка сообщений от имени администрации</i></li>
        </ul>
    </li>
</ul>

<div align="center">
&#128293; &#128293; &#128293; &#128293; &#128293; &#128293;
</div>
<h2>Эскизы основных групп элементов управления</h2>
<ul>
    <li>
        <h3><b>Неавторизованный пользователь</b></h3>
        <table>
            <tr>
                <th>Главная</th>
                <th>Регистрация</th>
                <th>Авторизация</th>
            </tr>
            <tr>
                <td><img src="https://user-images.githubusercontent.com/80625335/144157689-f667c13f-df52-416b-807f-71d083b7dcfc.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144157851-e0381547-478e-47b5-8161-782e09c855e4.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158038-dc8e3494-3453-4db9-93a0-ee95cee120e3.png"></td>
            </tr>
        </table>
    </li>
    <li>
        <h3><b>Авторизованный пользователь (АП)</b></h3>
        <table>
            <tr>
                <th>Список комнат</th>
                <th>Страница чужой комнаты</th>
                <th>Сообщение в комнату</th>
            </tr>
            <tr>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158113-de567b09-257c-4356-a84a-05292d517045.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158150-ee1b3fb9-b249-463b-b6c5-90e7629e0a29.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158178-dc548286-3115-4008-a9e3-ade19c4a7fcd.png"></td>
            </tr>
        </table>
        <table>
            <tr>
                <th>Сообщение от комнаты</th>
                <th>Отзыв на комнату</th>
                <th>Редактирование страницы комнаты пользователя</th>
            </tr>
            <tr>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158184-542cc699-5374-476b-8ac2-bf8e84391ba2.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158226-3ce4cd98-b889-428f-811a-db1e6cd78fb2.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158275-6fd57883-95b6-4804-a117-b527f84a5160.png"></td>
            </tr>
        </table>
        <table>
            <tr>
                <th>Редактирование профиля</th>
                <th>Страница общежития</th>
                <th>Уведомления</th>
            </tr>
            <tr>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158303-536fdb14-f30a-44ef-bdee-222f593ef19a.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158337-511cde56-3163-4797-88ce-3dd40b025281.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158377-682c89a7-2e9a-4c3f-98e4-99d9852499a5.png"></td>
            </tr>
        </table>
    </li>
    <li>
        <h3><b>Админ</b></h3>
        <table>
            <tr>
                <th>Изменение рейтинга</th>
            </tr>
            <tr><img src="https://user-images.githubusercontent.com/80625335/144158406-e2ea4666-6856-4de3-bd21-d22cefe8b26c.png"></tr>
        </table>
    </li>
    <li>
        <h3><b>Суперадмин</b></h3>
        <table>
            <tr>
                <th>Изменение роли</th>
                <th>Редактирование страницы общежития</th>
                <th>Написание уведомления</th>
            </tr>
            <tr>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158439-cd030148-757d-48d7-90a9-6b9832677af4.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158454-807a4086-2739-46f5-b092-e3ab78cabae9.png"></td>
                <td><img src="https://user-images.githubusercontent.com/80625335/144158466-b8beb0cd-b13c-4f1a-a6f9-3ff31aa3a74c.png"></td>
            </tr>
        </table>
    </li>
</ul>


<div align="center">
&#128293; &#128293; &#128293; &#128293; &#128293; &#128293;
<h2>Диаграмма пользовательских сценариев</h2>
</div>
<ul>
    <li>
        <h3><b>Неавторизованный пользователь</b></h3>
        <img src="https://user-images.githubusercontent.com/80625335/144158495-6b185265-d7d7-4c85-8377-ec34f90844cb.png">
    </li>
    <li>
        <h3><b>Авторизованный пользователь (АП)</b></h3>
        <img src="https://user-images.githubusercontent.com/80625335/144158503-e104345e-bce3-4db7-a9d3-2bec07756b3a.png">
    </li>
    <li>
        <h3><b>Админы</b></h3>
        <img src="https://user-images.githubusercontent.com/80625335/144158529-5ea5c80f-3b05-42ad-8507-cb9f6fdbaac5.png">
    </li>
</ul>
