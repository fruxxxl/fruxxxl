<p align="center">
  <a href="#english">English</a> · <a href="#русский">Русский</a>
</p>

<h1 align="center" id="english">TypeScript / Node.js Engineer</h1>

<p align="center">
  Backend-focused senior engineer · 10+ years in software · Microservices, infrastructure, developer tooling, and AI-assisted engineering
</p>

<p align="center">
  <a href="https://github.com/fruxxxl?tab=repositories&sort=stargazers">
    <img alt="GitHub stars" title="GitHub stars" src="https://custom-icon-badges.demolab.com/github/stars/fruxxxl?color=55960c&style=for-the-badge&labelColor=488207&logo=star"/>
  </a>
  <a href="https://github.com/fruxxxl?tab=followers">
    <img alt="GitHub followers" title="GitHub followers" src="https://custom-icon-badges.demolab.com/github/followers/fruxxxl?color=236ad3&style=for-the-badge&labelColor=1155ba&logo=people"/>
  </a>
  <img alt="Profile views" title="Profile views" src="https://komarev.com/ghpvc/?username=fruxxxl&style=for-the-badge"/>
</p>

<p align="center">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img alt="AI tooling" src="https://img.shields.io/badge/AI_tooling-111827?style=flat-square"/>
</p>

---

### What I Do

I work best in systems where engineering is not limited to shipping isolated features: diagnosing instability, improving observability, simplifying team workflows, and automating repeated operational work.

My main area is TypeScript backend development with NestJS, MongoDB, Redis, Docker-based environments, CI/CD, observability, and internal developer tools. I also work with AI-assisted engineering practices: reusable agent instructions, MCP integrations, LLM proxies, and AI-friendly technical documentation.

---

### Selected Projects

<table>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/mongo-collection-cherry-picker">Mongo Collection Cherry Picker</a></h3>
      <p>
        <code>TypeScript</code> · <code>CLI</code> · <code>MongoDB</code>
      </p>
    </td>
    <td>
      CLI and interactive tool for selective MongoDB backup and restore through SSH tunnels. Built for practical environment-to-environment data transfer: collection selection, presets, export strategies, and E2E tests with testcontainers.
    </td>
  </tr>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/git-flow-captain">GitFlow Captain</a></h3>
      <p>
        <code>TypeScript</code> · <code>GitLab</code> · <code>Azure DevOps</code>
      </p>
    </td>
    <td>
      CLI for automating git-flow in multi-repository projects with submodules. Supports pull request creation in GitLab and Azure DevOps. The project came from a real workflow problem: regularly managing hundreds of submodule update merge requests across repositories.
    </td>
  </tr>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/class-changes-tracker">Class Changes Tracker</a></h3>
      <p>
        <code>TypeScript</code> · <code>NPM</code> · <code>WeakRef</code>
      </p>
    </td>
    <td>
      Lightweight TypeScript library for tracking object changes through snapshots and <code>WeakRef</code>. Published on NPM and covered with tests.
    </td>
  </tr>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/deadlinesheet">Deadliner</a></h3>
      <p>
        <code>private</code> · <code>Swift</code> · <code>iOS</code> <a target="_blank" href="https://apps.apple.com/us/app/дедлайнер/id6760419265#information">AppStore</a> 
      </p>
    </td>
    <td>
      iOS app for tracking household supply expiry dates. Built with SwiftUI, SwiftData, WidgetKit, StoreKit 2, and AI-assisted voice input parsing.
    </td>
  </tr>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/ton-futures-bot">TON Futures Bot</a></h3>
      <p>
        <code>private</code> · <code>TypeScript</code> · <code>TON</code>
      </p>
    </td>
    <td>
      Algorithmic trading bot for TON / Storm Trade. Includes risk management, trailing stops, multi-asset support, AI-assisted analysis, and monitoring-oriented architecture.
    </td>
  </tr>
</table>

---

### Enterprise Experience

<p>
  10+ years in software development. Over the last 2+ years I have worked in a TypeScript / NestJS microservice system with 7 services, 20 repositories, and git submodules. During that period I merged 1,800+ merge requests and gradually focused more on system-level improvements than isolated feature work.
</p>

<table>
  <tr>
    <td width="32%"><strong>Event-driven data consistency</strong></td>
    <td>
      Designed synchronization for services that shared MongoDB data and needed near real-time consistency. The solution used MongoDB oplog tracking, ordered event processing, and distributed locks. It replaced unreliable polling and reduced the risk of data drift between services.
    </td>
  </tr>
  <tr>
    <td width="32%"><strong>Observability</strong></td>
    <td>
      Added metrics for connection pools, worker health, event processing lag, and cross-service traces. Worked with Prometheus, Grafana, and Jaeger to make production issues easier to detect, investigate, and explain.
    </td>
  </tr>
  <tr>
    <td width="32%"><strong>Local development and onboarding</strong></td>
    <td>
      Dockerized 7 services and added a reverse proxy, environment templates, and a CLI orchestrator for cloning, linking, and backup workflows. This reduced local setup for new developers from a multi-day process to a single documented flow.
    </td>
  </tr>
  <tr>
    <td width="32%"><strong>Service reliability</strong></td>
    <td>
      Worked on failure modes around large payloads, stream disconnects, and external service instability. Added request size limits, reconnect state machines, retry with backoff, and adaptive timeout strategies based on payload size.
    </td>
  </tr>
  <tr>
    <td width="32%"><strong>Test infrastructure</strong></td>
    <td>
      Migrated the project from mocha to jest, unified coverage reporting across mixed test frameworks, and standardized Zod validation with centralized error handling.
    </td>
  </tr>
</table>

---

### AI-Assisted Engineering

I actively use LLM tools in development: Cursor, Claude Code, Codex CLI, OpenCode, and local models through Ollama. My focus is not just faster code generation, but reliable engineering workflows around AI: review loops, task context, documentation, reusable instructions, and MCP integrations.

At work I helped develop team practices around AI-assisted development: team-authored skills, MCP integrations, YouTrack integration for agents, an internal LLM proxy with PII filtering, and architecture documentation written to be useful for both engineers and AI agents.

---

### Stack

```text
Backend:       TypeScript · Node.js · NestJS · MongoDB · Redis
Frontend:      React · MobX · SwiftUI
DevOps:        Docker · GitLab CI · GitHub Actions · Traefik
Observability: Prometheus · Grafana · Jaeger
AI:            LLM integration · MCP servers · LiteLLM · Ollama · PII guardrails
Blockchain:    TON · Storm Trade SDK
```

<p align="left">
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="36" height="36" alt="TypeScript" />
  </a>
  <a href="https://nodejs.org/en/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="36" height="36" alt="Node.js" />
  </a>
  <a href="https://nestjs.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nestjs-colored.svg" width="36" height="36" alt="NestJS" />
  </a>
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mongodb-colored.svg" width="36" height="36" alt="MongoDB" />
  </a>
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" />
  </a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" width="36" height="36" alt="Docker" />
  </a>
</p>

---

### Contact

<p>
  <a href="https://t.me/fruxxxl">
    <img src="https://img.shields.io/badge/Telegram-@fruxxxl-blue?style=flat-square&logo=telegram" alt="Telegram @fruxxxl" />
  </a>
</p>

---
---

<h1 align="center" id="русский">TypeScript / Node.js инженер</h1>

<p align="center">
  Senior backend-focused инженер · 10+ лет в разработке · Микросервисы, инфраструктура, developer tooling и AI-assisted engineering
</p>

<p align="center">
  <a href="https://github.com/fruxxxl?tab=repositories&sort=stargazers">
    <img alt="GitHub stars" title="GitHub stars" src="https://custom-icon-badges.demolab.com/github/stars/fruxxxl?color=55960c&style=for-the-badge&labelColor=488207&logo=star"/>
  </a>
  <a href="https://github.com/fruxxxl?tab=followers">
    <img alt="GitHub followers" title="GitHub followers" src="https://custom-icon-badges.demolab.com/github/followers/fruxxxl?color=236ad3&style=for-the-badge&labelColor=1155ba&logo=people"/>
  </a>
  <img alt="Profile views" title="Profile views" src="https://komarev.com/ghpvc/?username=fruxxxl&style=for-the-badge"/>
</p>

<p align="center">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img alt="AI tooling" src="https://img.shields.io/badge/AI_tooling-111827?style=flat-square"/>
</p>

---

### Что я делаю

Больше всего полезен в системах, где работа не ограничивается отдельными фичами: найти источник нестабильности, добавить наблюдаемость, упростить рабочий процесс команды или автоматизировать повторяющуюся операционную боль.

Основная зона: TypeScript backend development с NestJS, MongoDB, Redis, Docker-based окружениями, CI/CD, observability и внутренними developer tools. Также работаю с практиками AI-assisted engineering: reusable agent instructions, MCP-интеграции, LLM proxy и техническая документация, удобная для людей и AI-агентов.

---

### Избранные проекты

<table>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/mongo-collection-cherry-picker">Mongo Collection Cherry Picker</a></h3>
      <p>
        <code>TypeScript</code> · <code>CLI</code> · <code>MongoDB</code>
      </p>
    </td>
    <td>
      CLI и интерактивный инструмент для выборочного backup / restore MongoDB-коллекций через SSH-туннели. Сделан для практичных сценариев переноса данных между окружениями: выбор коллекций, пресеты, стратегии экспорта и E2E-тесты на testcontainers.
    </td>
  </tr>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/git-flow-captain">GitFlow Captain</a></h3>
      <p>
        <code>TypeScript</code> · <code>GitLab</code> · <code>Azure DevOps</code>
      </p>
    </td>
    <td>
      CLI для автоматизации git-flow в multi-repo проектах с submodules. Поддерживает создание pull requests в GitLab и Azure DevOps. Проект вырос из реальной рабочей задачи: регулярного управления сотнями merge requests на обновление submodule-ссылок между репозиториями.
    </td>
  </tr>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/class-changes-tracker">Class Changes Tracker</a></h3>
      <p>
        <code>TypeScript</code> · <code>NPM</code> · <code>WeakRef</code>
      </p>
    </td>
    <td>
      Небольшая TypeScript-библиотека для отслеживания изменений объектов через snapshots и <code>WeakRef</code>. Опубликована на NPM и покрыта тестами.
    </td>
  </tr>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/deadlinesheet">Дедлайнер</a></h3>
      <p>
        <code>private</code> · <code>Swift</code> · <code>iOS</code> <a target="_blank" href="https://apps.apple.com/us/app/дедлайнер/id6760419265#information">AppStore</a> 
      </p>
    </td>
    <td>
      iOS-приложение для учета сроков годности домашних запасов. SwiftUI, SwiftData, WidgetKit, StoreKit 2 и AI-assisted парсинг голосового ввода.
    </td>
  </tr>
  <tr>
    <td width="32%">
      <h3><a href="https://github.com/fruxxxl/ton-futures-bot">TON Futures Bot</a></h3>
      <p>
        <code>private</code> · <code>TypeScript</code> · <code>TON</code>
      </p>
    </td>
    <td>
      TypeScript-бот для алгоритмической торговли на TON / Storm Trade. В проекте есть risk management, trailing stops, multi-asset support, AI-assisted analysis и архитектура с фокусом на наблюдаемость.
    </td>
  </tr>
</table>

---

### Корпоративный опыт

<p>
  10+ лет в разработке. Последние 2+ года работал в TypeScript / NestJS микросервисной системе: 7 сервисов, 20 репозиториев и git submodules. За это время смержил 1,800+ merge requests и постепенно сместил фокус с отдельных фич на системные улучшения.
</p>

<table>
  <tr>
    <td width="32%"><strong>Согласованность данных через события</strong></td>
    <td>
      Спроектировал механизм синхронизации для сервисов, которые работали с общими данными в MongoDB и нуждались в near real-time consistency. Решение использовало MongoDB oplog, упорядоченную обработку событий и distributed locks. Оно заменило ненадежный polling и снизило риск рассинхронизации данных между сервисами.
    </td>
  </tr>
  <tr>
    <td width="32%"><strong>Наблюдаемость</strong></td>
    <td>
      Добавлял метрики connection pools, worker health, event processing lag и cross-service tracing. Работал с Prometheus, Grafana и Jaeger, чтобы производственные проблемы было проще обнаруживать, расследовать и объяснять.
    </td>
  </tr>
  <tr>
    <td width="32%"><strong>Локальная разработка и onboarding</strong></td>
    <td>
      Докеризовал 7 сервисов, добавил reverse proxy, env templates и CLI-оркестратор для клонирования, линковки и backup-сценариев. Это сократило запуск локального окружения для новых разработчиков с нескольких дней до одного документированного сценария.
    </td>
  </tr>
  <tr>
    <td width="32%"><strong>Надежность сервисов</strong></td>
    <td>
      Работал с проблемами больших payloads, обрывами stream-соединений и нестабильностью внешних сервисов. Добавлял request size limits, reconnect state machines, retry с backoff и адаптивные timeout-стратегии по размеру payload.
    </td>
  </tr>
  <tr>
    <td width="32%"><strong>Тестовая инфраструктура</strong></td>
    <td>
      Мигрировал проект с mocha на jest, унифицировал coverage reporting между разными тестовыми фреймворками и стандартизировал Zod-валидацию с централизованной обработкой ошибок.
    </td>
  </tr>
</table>

---

### AI-Assisted Engineering

Активно использую LLM-инструменты в разработке: Cursor, Claude Code, Codex CLI, OpenCode и локальные модели через Ollama. Основной интерес - не просто ускорить генерацию кода, а встроить AI в инженерный процесс надежно и воспроизводимо: review loops, task context, документация, reusable instructions и MCP-интеграции.

На работе участвовал в развитии командных практик AI-assisted разработки: team-authored skills, MCP-интеграции, YouTrack-интеграция для агентов, внутренний LLM proxy с PII-фильтрацией и архитектурная документация, полезная и инженерам, и AI-агентам.

---

### Стек

```text
Backend:       TypeScript · Node.js · NestJS · MongoDB · Redis
Frontend:      React · MobX · SwiftUI
DevOps:        Docker · GitLab CI · GitHub Actions · Traefik
Observability: Prometheus · Grafana · Jaeger
AI:            LLM integration · MCP servers · LiteLLM · Ollama · PII guardrails
Blockchain:    TON · Storm Trade SDK
```

<p align="left">
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="36" height="36" alt="TypeScript" />
  </a>
  <a href="https://nodejs.org/en/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="36" height="36" alt="Node.js" />
  </a>
  <a href="https://nestjs.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nestjs-colored.svg" width="36" height="36" alt="NestJS" />
  </a>
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mongodb-colored.svg" width="36" height="36" alt="MongoDB" />
  </a>
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" />
  </a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" width="36" height="36" alt="Docker" />
  </a>
</p>

---

### Контакты

<p>
  <a href="https://t.me/fruxxxl">
    <img src="https://img.shields.io/badge/Telegram-@fruxxxl-blue?style=flat-square&logo=telegram" alt="Telegram @fruxxxl" />
  </a>
</p>
