---
layout: default
title: Мастерство Domain-Driven Design
subtitle: Создавай программное обеспечение, которое приносит реальную пользу бизнесу
---

<style>
  .hero {
    text-align: center;
    padding: 4rem 1rem;
    background: linear-gradient(135deg, #2c3e50 0%, #3498db 100%);
    color: white;
    border-radius: 8px;
    margin-bottom: 2rem;
  }
  
  .hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
  }
  
  .hero p {
    font-size: 1.5rem;
    max-width: 800px;
    margin: 0 auto 2rem;
  }
  
  .features {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    margin: 3rem 0;
  }
  
  .feature {
    flex: 1;
    min-width: 280px;
    padding: 2rem;
    background: white;
    border-radius: var(--border-radius);
    box-shadow: var(--box-shadow);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border-top: 3px solid var(--primary-color);
  }
  
  .feature:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  }
  
  .feature h3 {
    color: var(--primary-color);
    margin-top: 0;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }
  
  .feature h3:before {
    content: '✓';
    color: var(--accent-color);
    font-weight: bold;
  }
  
  .testimonial {
    font-style: italic;
    padding: 2rem;
    background: #f1f8ff;
    border-left: 4px solid #3498db;
    margin: 2rem 0;
  }
  
  .author {
    font-weight: bold;
    margin-top: 1rem;
    color: #2c3e50;
  }
  
  .pricing {
    background: #f8f9fa;
    padding: 3rem 1rem;
    text-align: center;
    border-radius: 8px;
    margin: 3rem 0;
  }
  
  .price {
    font-size: 3rem;
    font-weight: bold;
    color: #2c3e50;
    margin: 1rem 0;
  }
  
  .cta-button {
    display: inline-block;
    background: #3498db;
    color: white;
    padding: 1rem 2rem;
    border-radius: 4px;
    text-decoration: none;
    font-weight: bold;
    margin-top: 1rem;
    transition: background 0.3s;
  }
  
  .cta-button:hover {
    background: #2980b9;
  }
</style>

<div class="hero">
  <div class="logo-container">
    <img src="/assets/images/bearddd.jpg" alt="Логотип курса DDD" class="logo">
  </div>
  <h1>Освой Domain-Driven Design</h1>
  <p>Измени свой подход к разработке ПО и создавай системы, которые действительно решают бизнес-задачи</p>
</div>

## Почему Domain-Driven Design?

В современном сложном бизнес-ландшафте программное обеспечение должно быть чем-то большим, чем просто функциональным — оно должно быть продолжением самого бизнеса. Domain-Driven Design (DDD) предоставляет принципы и практики, чтобы сделать это реальностью.

<div class="features">
  <div class="feature">
    <h3>Единый Язык</h3>
    <p>Преодолейте разрыв между техническими и бизнес-заинтересованными сторонами с помощью общего языка, который развивается вместе с вашей предметной областью.</p>
  </div>
  
  <div class="feature">
    <h3>Стратегический Дизайн</h3>
    <p>Научитесь выявлять основные домены и поддомены, а также эффективно моделировать сложные бизнес-процессы.</p>
  </div>
  
  <div class="feature">
    <h3>Тактические паттерны</h3>
    <p>Освойте сущности, объекты-значения, агрегаты и сервисы домена для создания поддерживаемых моделей.</p>
  </div>
</div>

## Чему Вы Научитесь

- Основные принципы и строительные блоки DDD
- Как выявлять и моделировать сложные бизнес-домены
- Методы разбиения больших систем на ограниченные контексты
- Стратегии управления сложностью домена в корпоративных приложениях
- Паттерны интеграции нескольких ограниченных контекстов
- Event Storming и другие методы совместного моделирования
- Внедрение DDD в различных архитектурных стилях
- Реальные кейсы и практические примеры

<div class="testimonial">
  "Этот курс полностью изменил наш подход к проектированию ПО. Принципы DDD помогли нам как никогда раньше согласовать техническую реализацию с бизнес-целями."
  <div class="author">— Алексей Петров, Ведущий архитектор</div>
</div>

## Структура Курса

### Модуль 1: Основы DDD
- Понимание ключевых концепций
- Важность Единого Языка
- Стратегический и тактический дизайн

### Модуль 2: Стратегический Дизайн
- Ограниченные контексты и их отображение
- Выделение основного домена
- Управление несколькими моделями

### Модуль 3: Тактический Дизайн
- Строительные блоки: Сущности, Объекты-Значения, Агрегаты
- Сервисы домена и Доменные События
- Репозитории и Фабрики

### Модуль 4: Шаблоны Внедрения
- Гексагональная Архитектура
- CQRS и Event Sourcing
- Тестирование доменных моделей

Для Кого Этот Курс?

- Архитекторы ПО и старшие разработчики
- Технические лидеры и руководители инженерных команд
- Владельцы продуктов и бизнес-аналитики
- Все, кто участвует в сложных программных проектах

<div class="pricing">
  <h2>Готовы изменить свой подход к проектированию ПО?</h2>
  <div class="price">Скоро запуск</div>
  
</div>

<footer style="text-align: center; margin-top: 4rem; color: #666; font-size: 0.9rem;">
  <p>© 2025 DDDevotion</p>
</footer>
