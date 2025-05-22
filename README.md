---
layout: post
title: Первая страница новой истории
date: '2025-01-09 04:52:16 +1000'
author: police_of_miami
pin: true
---
### Прекрасное начало
Приветствую на первой странице новой базы знаний Студенческого совета ИМКТ! Здесь будут размещаться гайды о популярных и не очень темах, связанных с IT.

### Как стать автором?
Для того, чтобы внести вклад в нашу базу знаний, достаточно сделать следующее:

* Клонировать репозиторий командой: 
```bash
git clone https://github.com/studsovet-imct/WikiPublication
```
{: .nolineno }
* Создать ветку в репозитории командой:
```bash
git branch <branch_name>
```
{: .nolineno }
* Перейти на данную ветку: 
```bash
git checkout <branch_name>
```
{: .nolineno }
* Создать файл в формате `YYYY-MM-DD-<name-of-post>.md`
* В данном посте вы можете руководствоваться [этими советами](https://chirpy.cotes.page/posts/write-a-new-post/). Обязательно укажите заголовок:
```markdown
---
title: TITLE
date: YYYY-MM-DD HH:MM:SS +/-TTTT
categories: [TOP_CATEGORIE, SUB_CATEGORIE]
tags: [TAG]     # TAG names should always be lowercase
---
```
{: file="_posts/YYYY-MM-DD-name-of-post.md" }

> При написании статьи обращайте внимание на [синтаксис Markdown](https://www.markdownguide.org/cheat-sheet/). С ним у вас откроется больше возможностей для редактирования текста.
{: .prompt-tip }

* Залейте ветку в репозиторий:
```bash
git commit -m "your informative message"
git push
```
* Сделайте Pull Request на странице репозитория.

Опционально можете указать себя как автора! Само собой, в рамках цензуры.
Для этого нужно в файле `_data/authors.yml`{: .filepath} добавить себя по формату шаблона.
> По умолчанию при отсутствии указания автора будет указываться `Студенческий совет ИМКТ`
{: .prompt-info }

