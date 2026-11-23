# Иосиф Правец

**Руководитель отдела разработки, 1С.** Делаю инструменты вокруг платформы 1С:Предприятие:
сборка и CI/CD, статический анализ кода, MCP-серверы, которые дают агентам доступ к
метаданным конфигураций. Пишу на том, что решает задачу — Go, Python, Java, Shell, OneScript.

## Чем занимаюсь

- **Сборка и CI для 1С** — docker-образы платформы и OneScript; пайплайн описывается кодом, а не YAML
- **Анализ кода** — валидатор конфигураций (метаданные и формы), диагностики для BSL Language Server
- **MCP и агенты** — конвертация метаданных в markdown, Docker Compose для MCP-сервисов, 1С-контекст для EDT
- **Знание как код** — OpenAPI-спецификации систем маркировки с примерами на 1С, личная вики на Obsidian под git

## Проекты

| Проект | Что решает | Стек |
|---|---|---|
| [onec-images](https://github.com/pravets/onec-images) | Docker-образы 1С:Предприятие для сборки и CI | Shell |
| [onec-cfg2md](https://github.com/pravets/onec-cfg2md) | Метаданные конфигурации (CFG и EDT) → markdown для MCP | Go |
| [compose4mcp](https://github.com/pravets/compose4mcp) | Готовые Docker Compose для MCP-серверов вокруг 1С | YAML |
| [oscript-images](https://github.com/pravets/oscript-images) | Образы движка OneScript и утилит на нём | Shell |
| [crpt-openapi](https://github.com/pravets/crpt-openapi) | OpenAPI «Честного знака»: True API и ЭДО Лайт | YAML |
| [dsh-edt-projects](https://github.com/pravets/dsh-edt-projects) | 1С-контекст для агентов через EDT | JavaScript |
| [checkushka](https://github.com/pravets/checkushka) | Валидатор конфигураций: метаданные, формы | Java |
| [ai-wiki-template](https://github.com/pravets/ai-wiki-template) | Каркас личной вики под LLM-агентов | Python |

## Вклад в чужие проекты

- [1c-syntax/bsl-language-server](https://github.com/1c-syntax/bsl-language-server) — диагностики BSL
- [1c-syntax/mdclasses](https://github.com/1c-syntax/mdclasses) — чтение вариантов отчёта в схемах компоновки данных
- [BlizD/Tasks](https://github.com/BlizD/Tasks) — предпросмотр markdown в карточке задачи, юнит-тесты
- [autumn-library/pipeliner](https://github.com/autumn-library/pipeliner) — генерация GitLab CI: артефакты, правила, параллельность, окружения, релизы

## Где пишу

- Telegram — [@pravets_IT](https://t.me/+GKGRmAwghxllYzIy)
- Инфостарт — [статьи](https://infostart.ru/1c/articles/2740983/)
- Почта — [i@pravets.ru](mailto:i@pravets.ru)

## Статистика

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://github-readme-stats.vercel.app/api?username=pravets&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&show=prs_merged&theme=github_dark&locale=ru">
  <img alt="Статистика GitHub" height="165"
    src="https://github-readme-stats.vercel.app/api?username=pravets&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&show=prs_merged&locale=ru">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://github-readme-stats.vercel.app/api/top-langs?username=pravets&layout=compact&langs_count=10&hide_border=true&theme=github_dark&locale=ru">
  <img alt="Языки" height="165"
    src="https://github-readme-stats.vercel.app/api/top-langs?username=pravets&layout=compact&langs_count=10&hide_border=true&locale=ru">
</picture>
