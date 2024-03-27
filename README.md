# Заметки

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Киноафиша</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
  }
  .header {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
  }
  .category {
    margin-bottom: 20px;
  }
  .category h2 {
    margin: 0;
  }
  .movie-card {
    border: 1px solid #ddd;
    margin: 10px;
    padding: 10px;
    border-radius: 5px;
    display: inline-block;
    width: 200px;
    vertical-align: top;
  }
  .movie-card img {
    width: 100%;
    height: auto;
  }
  .main-content {
    padding: 10px;
  }
</style>
</head>
<body>

<div class="header">
  <h1>Киноафиша</h1>
</div>

<div class="main-content">
  <div class="category">
    <h2>Жанры</h2>
    <ul>
      <li>Боевик</li>
      <li>Комедия</li>
      <li>Драма</li>
      <li>Ужасы</li>
    </ul>
  </div>
  <h2>Фильмы</h2>
  <div class="movie-card">
    <img src="poster1.jpg" alt="Постер фильма 1">
    <h3>Название фильма 1</h3>
    <p>Описание фильма 1...</p>
  </div>
  <div class="movie-card">
    <img src="poster2.jpg" alt="Постер фильма 2">
    <h3>Название фильма 2</h3>
    <p>Описание фильма 2...</p>
  </div>
  <!-- Добавьте здесь больше карточек фильмов -->
</div>

</body>
</html>
```
