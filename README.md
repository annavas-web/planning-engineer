<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Портфолио Анны</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #4a90e2;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 2rem;
      color: #4a90e2;
    }
    .projects, .reports {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .card img {
      max-width: 100%;
      border-radius: 8px;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Привет, я Анна 👋</h1>
    <p>Специалист по аналитике и планированию | Разработка отчетов | Управление проектами</p>
    <nav>
      <a href="#about">Обо мне</a>
      <a href="#projects">Проекты</a>
      <a href="#reports">Отчёты</a>
      <a href="#contacts">Контакты</a>
    </nav>
  </header>

  <section id="about">
    <h2>Обо мне</h2>
    <p>Здесь можно кратко рассказать о своём опыте: где работала, какие ключевые навыки у тебя есть и чем отличаешься от других специалистов.</p>
  </section>

  <section id="projects">
    <h2>Проекты</h2>
    <div class="projects">
      <div class="card">
        <img src="https://via.placeholder.com/400x200" alt="project screenshot">
        <h3>Проект 1</h3>
        <p>Краткое описание проекта: цель, результат и твоя роль.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x200" alt="project screenshot">
        <h3>Проект 2</h3>
        <p>Описание следующего проекта.</p>
      </div>
    </div>
  </section>
