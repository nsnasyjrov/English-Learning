# English Learning

Этот репозиторий предназначен для системного изучения английского языка. В нем хранятся конспекты тем, дорожная карта, учебные материалы, задания, словарь, диагностические тесты, письменные работы, reading/listening practice и материалы для повторения.

Главная цель репозитория - не пассивное накопление ссылок, а активное обучение: грамматика, построение предложений, регулярная практика, исправление ошибок, отслеживание прогресса и долгосрочная подготовка к IELTS.

## Последнее обновление — 16.08.2026

За период с 6 по 16 августа хранилище заметно расширилось:

- добавлены дневные занятия за `06.08`, `10.08`, `12.08` и `15.08` с практикой Past Simple и Sentence Building;
- добавлены listening-занятия за `05.08` и `11.08`, включая задания British Council, точечное распознавание фраз и пересказ;
- Reading перенесён в `Tests/Any practice/Reading`, добавлены занятия за `07.08` и `13.08`;
- добавлена speaking-практика за `08.08` с рассказом о рабочем дне и произношением окончания `-ed`;
- добавлены письменные checkpoints за `04.08` и `16.08`;
- создан `Verb Patterns.md` для моделей `verb + to-infinitive`, `verb + V-ing`, `verb + preposition + object` и `verb + object`;
- обновлены `Words.md`, `Time Managment.md` и рабочее пространство Obsidian;
- изображения дорожной карты и заданий перенесены внутрь `1) Sentence Core/Изображения`, добавлены новые иллюстрации;
- в репозиторий включены тема Minimal, CSS-сниппет `english-hub` и переносимые файлы плагинов Obsidian.

## Быстрый вход

[[Dashboard|Dashboard]] · [[ROADMAP.MD|Roadmap]] · [[0 - Sentence Core|Sentence Core]] · [[0 - Time System|Time System]] · [[0 - Practice|Practice]] · [[Ссылки|Карта хранилища]]

## Repository Structure

Актуальная структура репозитория:

```text
.
|-- .obsidian/
|   |-- app.json
|   |-- appearance.json
|   |-- community-plugins.json
|   |-- core-plugins.json
|   |-- graph.json
|   |-- hotkeys.json
|   |-- plugins/
|   |-- snippets/
|   |   `-- english-hub.css
|   |-- workspace.json
|   `-- themes/
|       |-- Minimal/
|       `-- Wikipedia/
|-- English Roadmap Tree/
|   |-- ROADMAP.MD.md
|   |-- Verb Patterns.md
|   |-- 1) Sentence Core/
|   |   |-- 0 - Sentence Core.md
|   |   |-- Cases - Падежи в английском.md
|   |   |-- Introduction.md
|   |   |-- Word order.md
|   |   |-- Подлежащее.md
|   |   `-- Изображения/
|   |-- 2) Time System/
|   |   |-- 0 - Time System.md
|   |   |-- 1 - Present Simple/
|   |   |   `-- Present Simple.md
|   |   `-- 2 - Past Simple/
|   |       |-- Past Simple.md
|   |       `-- Таблица неправильных глаголов.md
|   `-- Tests/
|       |-- 0 - Practice.md
|       |-- Any practice/
|       |   |-- 0 - Grammar Practice.md
|       |   |-- Control Sentence Core TEST.md
|       |   |-- Question review.md
|       |   |-- Reading/
|       |   |   |-- 0 - Reading.md
|       |   |   |-- 23.07.2026.md
|       |   |   |-- 02.08.2026.md
|       |   |   |-- 07.08.2026.md
|       |   |   `-- 13.08.2026.md
|       |   `-- Практика по дням/
|       |       |-- 0 - README.md
|       |       |-- Июль/31.07.2026.md
|       |       `-- Август/
|       |           |-- 06.08.2026.md
|       |           |-- 10.08.2026.md
|       |           |-- 12.08.2026.md
|       |           `-- 15.08.2026.md
|       |-- Listening/
|       |   |-- 0 - Listening.md
|       |   |-- 22.07.2026 British council A2.md
|       |   |-- 30.07.2026 Who's who in the office.md
|       |   |-- 05.08.2026.md
|       |   `-- 11.08.2026.md
|       |-- Speaking/
|       |   `-- 08.08.2026.md
|       `-- Writing/
|           |-- 0 - Writing.md
|           |-- Essay about me.md
|           |-- Writing 04.08.2026.md
|           `-- Writing 16.08.2026.md
|-- Dashboard.md
|-- README.md
|-- Time Managment.md
|-- Words.md
`-- Ссылки.md
```

## Folder And File Roles

### `English Roadmap Tree/`

Основная папка дорожной карты обучения. Сейчас здесь есть roadmap, первый этап `1) Sentence Core`, второй этап `2) Time System` и папка `Tests` для практики по навыкам.

### `English Roadmap Tree/ROADMAP.MD.md`

Точка входа в roadmap. Файл ссылается на изображение дорожной карты, которое хранится в `English Roadmap Tree/1) Sentence Core/Изображения/ROADMAP.png`.

Также есть Figma-версия roadmap: [English Roadmap - Skills Tree](https://www.figma.com/board/J5SSogE1d4UpsQo5KCkN5v/English-Roadmap-%E2%80%94-Skills-Tree?t=br5RiUWzR6hM67N8-0).

### `English Roadmap Tree/1) Sentence Core/`

Первый базовый этап. Здесь лежат материалы про каркас английского предложения: SVO, подлежащее, падежи, `to be`, `there is / there are`, dummy subject `it`, отрицания, закрытые и открытые вопросы, вопросы к подлежащему, косвенные вопросы, модальные глаголы и три базовые конструкции: `I am`, `I have`, `I + action verb`.

Карта этапа: `0 - Sentence Core.md`. Главный фундаментальный конспект: `Word order.md`.

### `English Roadmap Tree/Verb Patterns.md`

Краткая опора по управлению после глаголов: `promise to do`, `suggest doing`, `reply to someone`, `wait for something`, `discuss something`, `answer a question`. Файл используется вместе с дневной практикой для исправления повторяющихся ошибок вроде `suggest to check`, `reply someone` и `discuss about something`.

### `English Roadmap Tree/2) Time System/1 - Present Simple/`

Текущий этап про Present Simple. Файл `Present Simple.md` содержит регулярные действия, факты, расписания, состояния, утверждения, отрицания, вопросы, короткие ответы, `do/does`, `don't/doesn't`, `has`, `to be` в Present Simple, слова-маркеры, наречия и выражения частоты, правила окончаний `-s/-es` и `-y -> -ies`, а также отличие от Present Continuous для действий прямо сейчас.

### `English Roadmap Tree/2) Time System/2 - Past Simple/`

Новый этап про Past Simple. Файл `Past Simple.md` содержит базовое назначение времени, утвердительные предложения, отрицания через `didn't + base verb`, вопросы через `Did + subject + base verb`, правильные и неправильные глаголы, `was/were`, `had`, произношение окончания `-ed`, случаи употребления Past Simple и правила образования прошедшей формы у правильных глаголов: `-ed`, `-y -> -ied`, сохранение `-y` после гласной и удвоение согласной. Файл `Таблица неправильных глаголов.md` хранит V1/V2/V3, транскрипцию и перевод ключевых irregular verbs.

### `English Roadmap Tree/Tests/`

Практическая зона для checkpoints и тренировки навыков. Сейчас папка разделена по типам работы: `Any practice`, `Listening`, `Speaking`, `Writing`. Reading находится внутри `Any practice`, рядом с общей грамматической и дневной практикой.

### `English Roadmap Tree/Tests/Any practice/`

Общая практика и разбор ошибок. Сейчас содержит `Control Sentence Core TEST.md` и `Question review.md` с диагностикой по Sentence Core, вопросам, `to be` и `do/does`.

### `English Roadmap Tree/Tests/Any practice/Практика по дням/`

Дневная практика и история общения с ChatGPT/тестами/учебниками. `0 - README.md` описывает идею папки: собирать контекст занятий по дням и позже анализировать статистику прогресса. Помимо Present Simple checkpoint за `31.07.2026`, здесь есть августовские занятия за `06.08`, `10.08`, `12.08` и `15.08`: Past Simple, `did/didn't`, `was/were`, вопросы к подлежащему, Sentence Building, collocations и короткий письменный output.

### `English Roadmap Tree/Tests/Listening/`

Listening practice по материалам British Council A2. Сейчас есть:

- `22.07.2026 British council A2.md` - morning briefing, заметки по аудированию, фразы `I wanted to tell you about`, `canteen`, `cashless payment system`, `salary`, собственный output.
- `30.07.2026 Who's who in the office.md` - office introduction, colleagues, roles, partial dictation, Present Simple examples inside audio, retelling.
- `05.08.2026.md` - четыре коротких диалога, определение ситуации и эмоций, точечное распознавание Past Simple и пересказ;
- `11.08.2026.md` - диалог о планах на театр и концерт, результаты Preparation `12/12`, Task 1 `8/8`, Task 2 `6/6`, восстановление chunks и Sentence Building.

### `English Roadmap Tree/Tests/Any practice/Reading/`

Reading practice. Сейчас содержит:

- `23.07.2026.md` - текст про backend developer Alex, ответы по-русски и по-английски, закрепление Present Simple;
- `02.08.2026.md` - A2-текст о крушении туристического самолета рядом с линиями Наска с трехэтапным планом: чтение без словаря и формулировка основной мысли, полезные выражения и вопросы, затем краткий пересказ.
- `07.08.2026.md` - рассказ British Council `Frank's Last Case`, понимание сюжета, поиск Past Simple, пересказ голосовым вводом и тренировка произношения с результатом `79%`;
- `13.08.2026.md` - `First Star I See Tonight`, вопросы на gist/details, полезные конструкции и результаты Task 1/Task 2 по `8/8`.

### `English Roadmap Tree/Tests/Speaking/`

Speaking output и pronunciation. Занятие `08.08.2026.md` содержит быстрые ответы о рабочем дне, рассказ о задачах и нагрузке, а также тренировку трёх вариантов произношения окончания `-ed`.

### `English Roadmap Tree/Tests/Writing/`

Writing output. Сейчас содержит:

- `Essay about me.md` - текст о себе для проверки грамматики, исправления ошибок, улучшения формулировок и отслеживания прогресса в письме;
- `Writing 04.08.2026.md` - 75-минутный checkpoint по Present Simple и Past Simple: диагностика, перевод, два рассказа о рабочем дне, исправления, оценка навыков и список ошибок для повторения. Контролируемая грамматика выполнена на `12/12`, итоговая оценка занятия - `7/10`.
- `Writing 16.08.2026.md` - итоговый текст недели о рабочих проблемах, ожидании доступа к новому проекту и следующих шагах; содержит первоначальный вариант и короткий переработанный output.

### `Time Managment.md`

Учебный календарь с фактами и ссылками на результаты. В нём зафиксированы недели `03.08.2026-09.08.2026` и `10.08.2026-16.08.2026`, а также подготовлен план на `17.08.2026-23.08.2026`: Sentence Building, Listening A2→B1, следующий узел Time System, Reading B1, Speaking, transfer checkpoint и Writing review.

### `Words.md`

Корневой словарный файл для новых слов и выражений, которые появляются во время занятий. Помимо ранних рабочих и бытовых выражений, сейчас содержит `definition`, `definitely`, `guilty`, `prosecution`, `to twinkle`, примеры употребления и словарные заметки.

### `Ссылки.md`

Навигационная заметка для быстрых внутренних ссылок по материалам. Сейчас содержит ссылки на список вопросительных слов в `Word order.md`, слова-маркеры Present Simple, правило окончания `-es` в `Present Simple.md` и таблицу неправильных глаголов для Past Simple.

### `English Roadmap Tree/1) Sentence Core/Изображения/`

Папка с изображениями для заметок. Сейчас содержит `ROADMAP.png`, изображения для заданий и новые иллюстрации от `13.08.2026`. Перенос внутрь `Sentence Core` сохраняет связанные материалы рядом с основным разделом.

### `.obsidian/`

Переносимое окружение Obsidian: workspace, appearance, hotkeys, граф, тема Minimal и CSS-сниппет `english-hub`. В репозитории также сохранены файлы плагинов Dataview, Homepage, Note Locker, Minimal Settings, Style Settings и Read-only View. В текущей конфигурации включены `note-locker`, `homepage` и `obsidian-minimal-settings`.

## Current Learning Focus

Текущий фокус: закрепление **Sentence Core**, Present Simple и Past Simple через новые контексты, а не переход к следующему времени. Основная зона роста - естественное построение предложений: collocations, предлоги, артикли, определители и неправильные глаголы.

Активные темы Sentence Core:

- basic word order / SVO;
- `I am + noun/adjective/place`;
- `I have + noun`;
- `I + action verb + object/details`;
- `Are you...?` и вопросы с `to be`;
- `Do you...?` / `Does...?`;
- `work as`, `work with`, `interested in`;
- `there is / there are`;
- dummy subject `it`;
- modal verbs: `can`, `could`, `must`, `might`, `should`;
- отрицание через `not` после auxiliary/modal verb или `to be`;
- закрытые вопросы через auxiliary/modal verb в начале предложения;
- открытые вопросы через question word + auxiliary/modal verb + subject;
- вопросы к подлежащему;
- косвенные вопросы;
- простые утверждения, вопросы и отрицания.

Активные темы Time System:

- Present Simple для регулярных действий, привычек, фактов, расписаний и состояний;
- утверждения: base verb для `I/you/we/they`, verb + `-s/-es` для `he/she/it`;
- отрицания через `do not / don't` и `does not / doesn't` + base verb;
- вопросы через `Do/Does + subject + base verb`;
- короткие ответы: `Yes, I do`, `No, I don't`, `Yes, he does`, `No, he doesn't`;
- особенность `have -> has` для третьего лица;
- `to be` в Present Simple: `am / is / are`, отрицания и вопросы без `do/does`;
- различие между предложениями с `to be` и предложениями с full-meaning verb;
- основные случаи употребления: постоянные факты, привычки, расписания, последовательные действия, инструкции и демонстрация процесса;
- Present Simple не используется для действия, которое происходит прямо сейчас; для этого нужен Present Continuous;
- правила окончаний `-es` после `-sh`, `-ch`, `-s`, `-x`, `-o`;
- правило `-y -> -ies` после согласной и обычное `-s` после гласной;
- наречия частоты: `always`, `usually`, `often`, `generally`, `sometimes`, `rarely`, `seldom`, `hardly ever`, `never`;
- позиция наречий частоты: перед основным глаголом, но после `to be`;
- выражения частоты: `every day/morning/Friday`, `once`, `twice`, `three times` и далее;
- слова-маркеры: `always`, `usually`, `often`, `sometimes`, `rarely`, `never`, `every day/week/year`.
- старт Past Simple: действия и события в прошлом;
- Past Simple affirmative: regular verb + `-ed` или irregular verb second form;
- Past Simple negative: `did not / didn't + base verb`;
- Past Simple questions: `Did + subject + base verb`;
- правила образования regular past forms: `-ed`, `-y -> -ied`, `play -> played`, doubling consonant.

Активная практика:

- daily practice: Present Simple checkpoint за `31.07.2026`;
- daily practice: Past Simple и Sentence Building за `06.08`, `10.08`, `12.08` и `15.08`;
- reading: понимание A2-текстов без дословного перевода, выделение полезных выражений, ответы на вопросы и краткий пересказ;
- listening: British Council A2, распознавание ролей/фактов, partial dictation, фразы из аудио, пересказ;
- speaking: короткие спонтанные ответы, рабочий рассказ и произношение `-ed`;
- writing: self-introduction essay, рассказы о рабочем дне и итог недели с выбором между Present Simple, Past Simple и базовыми future constructions;
- checkpoint `04.08.2026`: контролируемая грамматика `12/12`, итог `7/10`; Present Simple пройден на базовом уровне, базовая структура Past Simple усвоена;
- повторение: `reply to someone`, `work on a task`, `be related to`, `finish the task`, `approve the change`, `at the end of the day`;
- question review: исправление ошибок в вопросах, `to be` vs `do/does`, agreement и артикли.

## How ChatGPT Should Use This Repository

ChatGPT должен использовать репозиторий как учебный контекст, а не как случайную свалку ссылок.

Рекомендуемый порядок работы:

1. Сначала читать этот `README.md`.
2. Затем читать `English Roadmap Tree/ROADMAP.MD.md`, если нужен roadmap.
3. Проверять текущий этап обучения перед предложением новых тем.
4. Использовать `English Roadmap Tree/1) Sentence Core/Word order.md` как главный файл по структуре предложения и вопросам.
5. Использовать `English Roadmap Tree/2) Time System/1 - Present Simple/Present Simple.md`, когда занятие касается настоящего времени, регулярных действий, `to be`, коротких ответов, частотности, расписаний или правил окончаний глаголов.
6. Использовать `English Roadmap Tree/2) Time System/2 - Past Simple/Past Simple.md`, когда занятие касается прошлого времени, `did/didn't`, regular/irregular verbs или правил `-ed`.
7. Проверять `Words.md`, если в занятии нужны слова, выражения или примеры их употребления.
8. Проверять `Ссылки.md`, если нужны быстрые внутренние переходы к важным заметкам и якорям.
9. Использовать `English Roadmap Tree/Tests/Any practice/`, `Any practice/Reading/`, `Listening/`, `Speaking/` и `Writing/` для проверки, анализа ошибок и планирования повторения.
10. Использовать `English Roadmap Tree/Tests/Any practice/Практика по дням/` как дневник занятий и источник статистики прогресса.
11. Читать `Time Managment.md` перед планированием следующего занятия и обновлять статус только по фактически выполненной работе.
12. Возвращать ошибки из `Writing 04.08.2026.md` и `Writing 16.08.2026.md` в новых контекстах, особенно collocations, предлоги, артикли, verb patterns и irregular verbs.
13. Предпочитать активные задания: построение предложений, вопросы, отрицания, исправление ошибок, mini-tests, reading/listening tasks, writing output и checkpoints.
14. Не добавлять ложные сведения о темах или файлах, которых нет в репозитории.

## Learning Workflow

Каждое занятие лучше вести по одному циклу:

1. **Topic** - выбрать одну конкретную тему.
2. **Explanation** - коротко объяснить правило и дать понятные примеры.
3. **Practice** - сделать упражнения на утверждения, вопросы и отрицания.
4. **Input** - добавить reading или listening, если тема уже достаточно понятна.
5. **Output** - написать короткий ответ, пересказ, mini-essay или speaking script.
6. **Check** - проверить ответы и объяснить исправления.
7. **Error log** - записать повторяющиеся или важные ошибки.
8. **Review** - вернуться к слабым местам на следующих занятиях.
9. **Checkpoint** - периодически проверять, стала ли тема активным навыком.

## Progress Tracking

Прогресс стоит фиксировать регулярно и одинаковым форматом.

В записи занятия должны быть:

- дата занятия;
- тема;
- тип практики: grammar, reading, listening, writing, mixed practice;
- путь к файлу дневной практики, если занятие записано в `Практика по дням`;
- затраченное время и статус в `Time Managment.md`, если занятие входит в недельный план;
- сделанные упражнения;
- ошибки;
- новые слова и фразы;
- что повторить;
- следующий шаг.

Рекомендуемый шаблон:

```markdown
## YYYY-MM-DD

Topic:

Practice type:

Daily practice file:

Exercises:

New words:

Mistakes:

Review:

Next step:
```

## Planned Structure

Эти папки рекомендуется создать позже. Сейчас их нет в репозитории:

```text
grammar/
sentence-building/
practice/
errors/
progress/
vocabulary/
input/
output/
sources/
checkpoints/
```

Рекомендуемые роли:

- `grammar/` - структурированные правила и грамматические заметки, если текущего roadmap-дерева станет мало.
- `sentence-building/` - паттерны и упражнения на построение предложений.
- `practice/` - отдельная папка для упражнений, если `English Roadmap Tree/Tests/` станет слишком большой.
- `errors/` - журнал ошибок, исправления и повторяющиеся слабые места.
- `progress/` - история занятий и краткие отчеты о прогрессе.
- `vocabulary/` - будущая папка для расширения `Words.md`: слова, фразы, collocations и тематические списки.
- `input/` - отдельная папка для текстов, аудио, видео и материалов для разбора, если они будут вынесены из `Tests/`.
- `output/` - отдельная папка для письменных ответов, speaking scripts и исправленных работ, если они будут вынесены из `Tests/Writing/`.
- `sources/` - надежные источники и справочные материалы.
- `checkpoints/` - будущая отдельная папка для регулярных проверок, если `English Roadmap Tree/Tests/` станет недостаточно.

## Long-Term Direction

Долгосрочная цель - подготовка к IELTS. Но текущий приоритет - крепкий Sentence Core, активные Present Simple и Past Simple, естественные словосочетания и регулярная практика input/output: порядок слов, простые утверждения, вопросы, отрицания, `to be`, частотность, reading, listening, speaking и writing. IELTS-практику лучше добавлять постепенно, когда базовое настоящее и прошедшее время устойчиво работают в самостоятельной речи и письме.
