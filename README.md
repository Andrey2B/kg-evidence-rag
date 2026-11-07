# Формирование доказательного контекста для больших языковых моделей на основе графа знаний Neo4j/Wikidata

Статья для сборника НИТУ «МИСиС» (курс «Научное письмо и публикационная деятельность»).
Оформление: LaTeX-шаблон `sadekovlar/misis-article-latex` (`misisarticle.cls`, LPPL 1.3c, без изменений).

## Структура

| Путь | Назначение |
|---|---|
| `article.tex` | Текст статьи |
| `misisarticle.cls` | Класс оформления|
| `.github/workflows/` | GitHub Actions: сборка PDF |

## Сборка статьи

Компилятор: XeLaTeX или tectonic.

### GitHub Actions
PDF собирается автоматически при push в `main`.
Скачать: вкладка **Actions** - `article.pdf`.

### Локально
```bash
make article        # PDF: build/article.pdf
