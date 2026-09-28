
<div align="center">
  
![AQA Banner](./banner.png)
# Дарья Гембар

**QA Engineer · Manual + Automation · Playwright · TypeScript**

[Portfolio](https://github.com/DaryaGembar) · [PomidorQA](https://github.com/DaryaGembar/PomidorQA-tests) · [Resume RU](HH_LINK) · [Telegram](https://t.me/TELEGRAM_HANDLE) · [Email](mailto:daragembar@gmail.com)

</div>

<div align="center">

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge)
![CI](https://img.shields.io/badge/CI-2088FF?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge)
![Charles](https://img.shields.io/badge/Charles-000000?style=for-the-badge)
![DevTools](https://img.shields.io/badge/DevTools-4285F4?style=for-the-badge)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge)
![TestRail](https://img.shields.io/badge/TestRail-65C179?style=for-the-badge)
![Allure](https://img.shields.io/badge/Allure-FF6A88?style=for-the-badge)
![Agile](https://img.shields.io/badge/Agile-009FDA?style=for-the-badge)

</div>

---

Тестирую **веб-приложения и REST API вручную и автоматизирую ключевые сценарии** так, чтобы результат
можно было **доказать, воспроизвести и быстро диагностировать**.

Основной стек: **Playwright + TypeScript**, REST API, Postman, Chrome DevTools, SQL, Git и GitHub Actions.

**Санкт-Петербург** · удалённый / гибридный / офисный формат

<div align="center">

</div>

---

## Избранные QA-проекты

### [PomidorQA — Automation QA](https://github.com/DaryaGembar/PomidorQA-tests)
![Coverage](https://img.shields.io/badge/coverage-84%25-brightgreen)

Основной automation-проект на **Playwright + TypeScript** с Unit, API и E2E-проверками,
cross-browser regression и traceability от требований до тестов.

- **50 / 50 требований** прошли аудит;
- **42 / 50 requirements automated = 84%** (4 partial, 1 known defect, 2 out of scope, 1 not covered);
- **80+ automated checks**: Unit + API + E2E на живом стенде;
- **E2E в Chromium**, реальные browser contexts для многосессионных сценариев;
- **Page Object Model**, семантические локаторы (`getByRole`, `getByLabel`, `getByTestId`);
- **API-based Arrange** и каскадный cleanup через `finally`;
- **CI: 5 параллельных кубов** (lint / unit / api / e2e / allure-report);
- **Allure-отчёт** на GitHub Pages с историей;
- **Telegram-уведомления** о статусе и артефактах падений;
- **AI-reviewer** для PR через Claude Opus 5 (Polza.ai) с защитой от prompt injection.

📊 [Allure-отчёт последнего прогона](https://daryagembar.github.io/PomidorQA-tests/)

---

## Что я делаю в QA

| Слой | Чем занимаюсь |
| --- | --- |
| **Test design** | Test Plans (scope, entry/exit, риски), Test Cases в стандартном формате: smoke, boundary, negative, exploratory, cross-cutting (a11y, mobile) |
| **Bug reports** | Severity/Priority, шаги воспроизведения, expected vs actual, evidence, root cause, suggested fix |
| **Test automation** | POM, семантические локаторы, без `waitForTimeout`, auto-waiting через `expect().toPass()` и `expect.poll` |
| **Test pyramid** | E2E для сквозных сценариев, API для бизнес-правил, Unit для чистых функций |
| **CI / observability** | GitHub Actions с параллельными кубами, Allure с историей, артефакты падений |
| **Process** | Traceability требований, ревью PR, документирование known defects вместо `test.skip()` |
| **Manual** | Exploratory testing, чек-листы регресса, smoke после изменения стенда |

---

## Артефакты в репозитории PomidorQA

- 📋 [`docs/test-plan.md`](https://github.com/DaryaGembar/PomidorQA-tests/blob/main/docs/test-plan.md) — Test Plan с целями, стратегией, рисками, расписанием
- 📝 [`docs/test-cases.md`](https://github.com/DaryaGembar/PomidorQA-tests/blob/main/docs/test-cases.md) — примеры Test Cases (smoke / boundary / negative / exploratory / a11y)
- 🐛 [`docs/bug-reports/`](https://github.com/DaryaGembar/PomidorQA-tests/tree/main/docs/bug-reports) — шаблон + KD-1 (known defect) + BR-001, BR-002
- 📊 [`docs/coverage-matrix.md`](https://github.com/DaryaGembar/PomidorQA-tests/blob/main/docs/coverage-matrix.md) — трассировка 50 требований ↔ тесты
- 📖 [`docs/ci-walkthrough.md`](https://github.com/DaryaGembar/PomidorQA-tests/blob/main/docs/ci-walkthrough.md) — построчный разбор CI для подготовки к собеседованиям
- 🤖 [`scripts/ai-review.mjs`](https://github.com/DaryaGembar/PomidorQA-tests/blob/main/scripts/ai-review.mjs) — AI-reviewer с двухпроходной проверкой

---

## Контакты

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/daryagembar)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daragembar@gmail.com)
[![HH](https://img.shields.io/badge/HH.ru-red?style=for-the-badge&logo=hh&logoColor=white)](https://spb.hh.ru/resume/08d4f43eff10e3565c0039ed1f697539696551)

</div>

---

<sub>📍 Санкт-Петербург · GMT+3 · Этот README обновляется по мере роста портфолио.</sub>

---
