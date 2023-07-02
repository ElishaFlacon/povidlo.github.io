<h1 align="center"> 
    🔥 API 🔥
</h1>



</br>



<h2>
  📁 api_url/file/
</h2>

<h3>
  URL-шаблон указывающий на файл urls.py внутри приложения 'src.convert', который содержит дополнительные URL-шаблоны, для функциональности работы с файлами
</h3>


<br/>
<hr/>


<h3>
    api_url/file/upload/
    
<h4>
    Загрузка файла на сервер и дальнейшая его обработка
</h4>

<br/>

Headers:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Response:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Requset:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```


<br/>
<hr/>


<h3>
    api_url/file/download/int:file_id/
    
<h4>
   Скачивание файла для авторизованных пользователей
</h4>

<br/>

Headers:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Response:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Requset:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```


<br/>
<hr/>


<h3>
    api_url/file/delete/int:pk/
    
<h4>
    Удаление файла для авторизованных пользователей
</h4>

<br/>

Headers:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Response:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Requset:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```


<br/>
<hr/>


</h3>





</br>
</br>
</br>
</br>
</br>





<h2>
  😃 api_url/user/
</h2>

<h3>
  URL-шаблон указывающий на файл urls.py внутри приложения 'src.oauth', который содержит пути к представлениям для регистрации, входа, обновления профиля пользователя и другим функциям, связанным с учетными записями пользователей
</h3>


<br/>
<hr/>


<h3>
    api_url/user/udate/
</h3>
<h4>
    Отвечает за обновление информации о пользователе. При обращении к этому URL пользователь может изменять свои данные или профиль
</h4>

<br/>

Headers:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Response:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Requset:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```


<br/>
<hr/>


<h3>
    api_url/user/register/
</h3>
<h4>
    Обрабатывает процесс регистрации новых пользователей
</h4>

<br/>

Headers:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Response:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Requset:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```


<br/>
<hr/>


<h3>
    api_url/user/login/
</h3>
<h4>
    Отвечает за аутентификацию пользователей. При обращении к этому URL пользователи могут войти в систему, предоставив свои учетные данные (имя пользователя и пароль)
</h4>

<br/>

Headers:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Response:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Requset:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```


<br/>
<hr/>


<h3>
    api_url/user/token/refresh/
</h3>  
<h4>
    Обрабатывает запросы на обновление токена аутентификации. При обращении к этому URL пользователь может запросить обновление токена для продления срока его действия
</h4>

<br/>

Headers:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Response:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Requset:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```


<br/>
<hr/>


<h3>
    api_url/user/password/reset/
</h3>
<h4>
    Обрабатывает запросы на сброс пароля и отправляет соответствующую информацию по электронной почте
</h4>

<br/>

Headers:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Response:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Requset:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```


<br/>
<hr/>


<h3>
    api_url/user/password/reset/confirm///
</h3>
<h4>
    Отвечает за подтверждение сброса пароля после получения уникального идентификатора uidb64 и токена token
</h4>

<br/>

Headers:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Response:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```

<br/>

Requset:
```
{
    file: "пример" | описание | тип,
    id: 123 | это айди файла хз | integer,
}
```


<br/>
<hr/>


</h3>





<br/>
<br/>
<br/>
<br/>
<br/>
<br/>





<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=d179b8&height=64&section=footer"/>
</p>