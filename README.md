<!DOCTYPE html>
<html>
<head>
<title>Таблица с фамилиями и оценками</title>
<style>
  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px; /* Добавляет отступ снизу таблицы */
  }

  th, td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
  }

  th {
    background-color: #f2f2f2;
    font-weight: bold;
  }

  tr:nth-child(even) { /* Чередующиеся цвета строк */
    background-color: #f9f9f9;
  }

  /* Дополнительные стили для красоты */
  h2 {
      margin-top: 30px;
      margin-bottom: 15px;
  }
</style>
</head>
<body>

<h2>Фамилии и оценки</h2>

<table>
  <thead>
    <tr>
      <th>Фамилия</th>
      <th>Оценка</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Иванов</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Петров</td>
      <td>4</td>
    </tr>
    <tr>
      <td>Сидоров</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Кузнецов</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Смирнов</td>
      <td>4</td>
    </tr>
  </tbody>
</table>

</body>
</html>
