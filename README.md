**GIT 04: Описание репозитория в README.md**
===============================================

## Описание
Данный репозиторий создан в ходе выполнения DevOps практикума от команды [fevlake](https://fevlake.com/).\
В процессе создания файла *README.md*, используя язык разметки **Markdown**, я изучил типовые методы работы с текстом:

* нумерованные списки
* не нумерованные списки
* ссылки
* картинки
* таблицы
* выделение блоков с кодом
* разного размера заголовки
* цитаты

Содержимое репозитория
-----------------------
В репозитории находятся два файла.

| Имя файла   | Размер | Назначение                           |
|-------------|--------|--------------------------------------|
| README.md   | 3.5K   | Файл с описанием репозитория         |
| nginx.conf  | 2.6K   | Файл дефолтной конфигурации nginx    |

<details><summary>Содержимое файла nginx.conf</summary>
<p>

### Первые 20 строк

```
#user  nobody;
worker_processes  1;

#error_log  logs/error.log;
#error_log  logs/error.log  notice;
#error_log  logs/error.log  info;

#pid        logs/nginx.pid;


events {
    worker_connections  1024;
}


http {
    include       mime.types;
    default_type  application/octet-stream;

    #log_format  main  '$remote_addr - $remote_user [$time_local] "$request" '
```

</p>
</details>

## При создании использовались
1) Система контроля версий git
2. Операционные системы Windows и Linux
3. Редактор кода visual studio code

![Screenshot](https://downloader.disk.yandex.ru/preview/ed4bcc03d0714b2ae7a9e545a710c204d29d071b523da91fb52b5260da87a257/623f254d/1UhUPE9nNjY92pDL2XYx2eB9fvNP8EPI-I-Mwu88zC54funShvLcbGJzbmuJUXvRoMkD3P3YhL6vQPcpWRt0mw%3D%3D?uid=0&filename=2022-03-26_16-31-22.jpg&disposition=inline&hash=&limit=0&content_type=image%2Fjpeg&owner_uid=0&tknv=v2&size=2048x2048)

## Cсылки на использованные источники
- [docs.github.com](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections) - инструкция по созданию раскрывающейся секции.
- [Самоучитель с интерактивными упражнениями по Markdown](https://commonmark.org/help/tutorial/index.html)

## Интересный факт

> Век живи — век учись

Очень известная фраза, которую можно услышать буквально от каждого учителя и которую любят приводить как аргумент для обоснования важности изучения того или иного предмета, на самом же деле неполна и часто ошибочно приписывается Ленину.

Автор оригинальной фразы — Луций Анней Сенека, и звучит она так:
> Век живи — век учись тому, как следует жить.