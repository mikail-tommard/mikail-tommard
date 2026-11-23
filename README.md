<h1 align="center">mikail-tommard</h1>

<p align="center"><strong>Go-бэкенд · Инструменты для разработчиков · Локальный ИИ</strong></p>

<p align="center">
  <img alt="Go" src="https://img.shields.io/badge/Go-086B80?style=flat-square&amp;logo=go&amp;logoColor=white">
  <img alt="C" src="https://img.shields.io/badge/C-404D82?style=flat-square&amp;logo=c&amp;logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-315A7D?style=flat-square&amp;logo=postgresql&amp;logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-A52A37?style=flat-square&amp;logo=redis&amp;logoColor=white">
  <img alt="Apache Kafka" src="https://img.shields.io/badge/Apache%20Kafka-2B3440?style=flat-square&amp;logo=apachekafka&amp;logoColor=white">
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-A74815?style=flat-square&amp;logo=rabbitmq&amp;logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-205C8C?style=flat-square&amp;logo=docker&amp;logoColor=white">
</p>

<p align="center">
  Пишу HTTP-сервисы на Go и делаю инструменты для работы с Codex.<br>
  В моих проектах есть локальные MCP-серверы, автоматизация рабочего стола и API с PostgreSQL.
</p>

<p align="center">
  <a href="https://github.com/mikail-tommard/task-flow">
    <img src="backend-request.gif" alt="Пример запроса в task-flow. Go API получает GET /task/42, читает задачу из PostgreSQL и возвращает JSON." width="900">
  </a>
</p>

## Инструменты для Codex

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/mikail-tommard/ai-workspace">Forma · AI Workspace</a></h3>
      <p>Локальное рабочее пространство, где Codex может выводить задачи, графики, изображения и документы на интерактивную панель. Go-сервер обслуживает панель и хранит данные в SQLite.</p>
      <sub>Go · SQLite · MCP</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/mikail-tommard/codex-vision">Codex Vision</a></h3>
      <p>Локальный MCP-сервер для работы с приложениями через интерфейс. Агент может делать снимки экрана, находить окна и выполнять разрешённые действия мышью и клавиатурой.</p>
      <sub>Go · MCP · Accessibility · системные API</sub>
    </td>
  </tr>
</table>

## Бэкенд и системные проекты

| Проект | Что внутри |
| --- | --- |
| [task-flow](https://github.com/mikail-tommard/task-flow) | Учебный сервис задач с HTTP API. PostgreSQL хранит данные, RabbitMQ используется для асинхронных уведомлений. |
| [sabr](https://github.com/mikail-tommard/sabr) | Full-stack MVP на Vue и Go. В бэкенде реализованы регистрация, вход и обновление токенов с хранением данных в PostgreSQL. |
| [ecom](https://github.com/mikail-tommard/ecom) | Бэкенд интернет-магазина с регистрацией, авторизацией и миграциями PostgreSQL для товаров и заказов. |
| [link-checker](https://github.com/mikail-tommard/2025-12-10-links) | Go-сервис, который принимает список ссылок, проверяет их доступность и формирует PDF-отчёт. |
| [decimal](https://github.com/mikail-tommard/decimal) | Реализация десятичной арифметики на C. |

## Технические заметки

В [notes](https://github.com/mikail-tommard/notes) собираю примеры и конспекты по Go, Git, Docker, SQL и Nginx.
