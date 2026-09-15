# Семинар 4. Модель как исполнитель разметки

Практический ноутбук и материалы для занятия DLCOURSE-65.

Датасет — подвыборка [RuSentiment](https://github.com/strawberrypie/rusentiment). Лицензия данных: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) — см. `data/SOURCE.md`.

## Содержимое

| Файл / папка | Что внутри |
|---|---|
| `seminar.ipynb` | ноутбук занятия |
| `.env.example` | шаблон секретов (скопировать в `.env`) |
| `data/` | `dataset.csv`, инструкция для людей, иллюстрации и схемы |
| `artifacts/` | сплиты, ответы людей, предсказания моделей, журнал вызовов |

## Как запустить

**Локально или в Colab с полным клоном:**

```bash
git clone https://github.com/MilordEv/seminar4-model-as-annotator-data.git
cd seminar4-model-as-annotator-data
```

Откройте `seminar.ipynb` — `data/` и `artifacts/` уже рядом.

**Только ноутбук в Colab:** при первом запуске ноутбук сам скачает `data/` и `artifacts/` из этого репозитория.
