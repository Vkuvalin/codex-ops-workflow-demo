# Границы раскрытия информации

Этот документ объясняет, что намеренно включено и что намеренно исключено из `codex-ops-workflow-demo`.

Репозиторий является публичной, очищенной архитектурной demo-версией. Он показывает контролируемую операционную модель AI-assisted development с Codex без раскрытия деталей приватного проекта, реальной истории implementation, приватных правил или чувствительного бизнес-контекста.

---

## 1. Назначение этой публичной demo-версии

Назначение этого репозитория — продемонстрировать инженерный workflow для безопасного и осознанного использования Codex.

Он показывает, как структурировать:

- постановку задачи;
- границы scope;
- проектные guardrails;
- route hints;
- переиспользуемые skills;
- read-only audits;
- reports;
- ExecPlans;
- validation gates;
- stop conditions;
- human-in-the-loop review.

Репозиторий предназначен для демонстрации операционной модели, а не для публикации дампа конфигурации приватного проекта.

---

## 2. Что включено

Эта публичная demo-версия может включать:

```text
README
документацию операционной модели
объяснение route levels
границу audit vs implementation
жизненный цикл ExecPlan
Mermaid-диаграммы
очищенные концептуальные примеры
```

Включённые материалы фокусируются на:

- архитектуре взаимодействия;
- границах ответственности;
- управлении процессом;
- управлении рисками;
- reviewability;
- recoverability;
- context management.

---

## 3. Что намеренно исключено

Этот публичный репозиторий намеренно не включает:

- исходный код приватного продукта;
- приватные project-specific правила `AGENTS.md`;
- реальную историю задач;
- реальные implementation diffs;
- приватные audit reports;
- приватные ExecPlans;
- secrets или credentials;
- чувствительный бизнес-контекст;
- детали коммерческого продукта;
- приватные prompts;
- customer/user data;
- внутренние пути репозитория, раскрывающие чувствительную структуру.

Эти исключения намеренные и являются частью дизайна репозитория.

---

## 4. Приватная система vs публичная demo-версия

| Область | Приватная система | Публичная demo-версия |
|---|---|---|
| Реальные project guardrails | Приватные | Описаны на уровне паттерна |
| Реальные task prompts | Приватные | Исключены или очищены |
| Реальные audit reports | Приватные | Исключены |
| Реальные ExecPlans | Приватные | Исключены или заменены концептуальными примерами |
| Реальные implementation diffs | Приватные | Исключены |
| Business/product context | Приватный | Обобщён |
| Operating model | Реализуется / развивается | Задокументирована |
| Route levels | Реализуются / развиваются | Задокументированы |
| Audit vs implementation boundary | Реализуется / развивается | Задокументирована |
| ExecPlan lifecycle | Реализуется / развивается | Задокументирован |

Публичная версия должна быть понятна без раскрытия приватного проекта.

---

## 5. Почему репозиторий docs-first

Формат docs-first выбран намеренно.

Главный артефакт здесь — архитектура:

```text
как формулируются задачи
как Codex получает scope
как выбираются routes
как audits остаются read-only
как reports сохраняют анализ
как ExecPlans делают долгую работу recoverable
как validation gates замыкают цикл
```

Публикация реальных приватных инструкций, reports, prompts и истории implementation создала бы ненужное раскрытие и снизила бы переносимость.

Цель — показать переносимый инженерный паттерн.

---

## 6. Что можно обсуждать на интервью

Эта demo-версия поддерживает обсуждение следующих тем:

- AI-assisted development workflows;
- task routing для Codex;
- context management;
- guardrails и project invariants;
- route levels L0-L5;
- разделение audit vs implementation;
- границы reports;
- жизненный цикл ExecPlan;
- validation gates;
- stop conditions;
- human-in-the-loop approval;
- риски ad-hoc prompting.

Публичный репозиторий даёт достаточно контекста для архитектурного review без раскрытия приватных операционных деталей.

---

## 7. Что не следует выводить из этой demo-версии

Эту публичную demo-версию не следует трактовать как заявление о наличии:

- полностью автономной coding-agent system;
- замены человеческому code review;
- production security certification;
- полной автоматизации software development;
- публичного релиза приватной Codex configuration;
- публичной доступности реальных project prompts, reports или plans;
- разрешения для Codex принимать архитектурные решения без human approval.

Заявление здесь более узкое и практическое:

```text
Это контролируемая operating model для scoped, reviewable
и recoverable Codex-assisted development.
```

---

## 8. Безопасные будущие дополнения

Позже репозиторий может включать очищенные примеры, например:

- sample task prompt;
- sample route selection note;
- sample audit report с fake project context;
- sample ExecPlan для toy task;
- sample validation summary;
- sample diff review checklist.

Любые будущие примеры должны оставаться:

- synthetic;
- non-sensitive;
- generalized;
- clearly marked as illustrative;
- не скопированными из приватной production work без явного approval.

---

## 9. Границы security и privacy

Репозиторий следует таким границам:

```text
No secrets.
No credentials.
No private task history.
No private product source code.
No real implementation diffs.
No sensitive AGENTS.md rules.
No private reports or ExecPlans.
No business-sensitive context.
```

Если деталь полезна для объяснения workflow, но в исходной форме является приватной, перед публикацией её следует обобщить.

---

## 10. Summary

Этот репозиторий является публичной архитектурной demo-версией операционной модели Codex.

Он предназначен для того, чтобы показать:

```text
как структурировать AI-assisted development work
а не приватный проект, где этот workflow изначально применялся
```

Принцип раскрытия:

```text
Показывать operating model, boundaries и engineering decisions.
Не раскрывать private rules, real task history, secrets или business context.
```
