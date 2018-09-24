# hello-world
just another repository

<!DOCTYPE html>
<html>
  <head>
    <title>Работа над ошибками</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <h1>Конспект курса</h1>
    <p class="learned-ok">Парные теги.</p>
    <p class="learned-ok">Одиночные теги.</p>
    <p class="learned-ok">Атрибуты тегов.</p>
    <p class="learned-ok">Инлайновые (встроенные) стили.</p>
    <p class="learning-in-progress">Внешние стили.</p>
    <p class="not-learned">Стилизация по классам.</p>
  </body>
</html>


body {
  font-family: "Georgia", serif;
}

p {
  margin: 10px 0;
  padding: 5px 10px;
  border: 1px solid #cccccc;
  border-left-width: 10px;
  color: white;
}

.learned-ok {
  border-color: #27ae60;
  background-color: #2ecc71;
  text-decoration: line-through;
}

.learning-in-progress {
  border-color: #f39c12;
  background-color: #f1c40f;
}

.not-learned {
  border-color: #c0392b;
  background-color: #e74c3c;
}
