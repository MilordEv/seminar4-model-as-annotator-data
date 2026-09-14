# RuSentiment

Семинар использует подвыборку [RuSentiment](https://github.com/strawberrypie/rusentiment)
(Rogers et al., COLING 2018), лицензия [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Полный корпус не кладём в `data/`: для занятия достаточно `dataset.csv`.

Как собрана подвыборка (`prepare_dataset.py`, `random_state=42`):

- `prompt_examples`: 10 постов (по 2 на класс) из `rusentiment_random_posts.csv`, длина 20–280 символов;
- `calibration`: 50 постов (по 10 на класс) из того же random-набора;
- `test`: 200 постов (по 40 на класс) из официального `rusentiment_test.csv`.

Классы: `positive`, `negative`, `neutral`, `speech`, `skip`.
