Домашние задания по теме Git
===
## Общее описание
Данный репозиторий содержит результаты выполнения заданий по теме системы управления версиями Git.
## Информация о курсе
- **Наименование курса:**  `Devops`
- **Раздел курса:**  `[DevOps - 1] - Basic. Git`
- **Ссылка на задания курса:** [https://lk.rebrainme.com/devops?page=tasks](https://lk.rebrainme.com/devops?page=tasks)
- **Ссылка на репозиторий:** [https://gitlab.rebrainme.com/devops_users_repos/3545/rebrain-devops-task1](https://gitlab.rebrainme.com/devops_users_repos/3545/rebrain-devops-task1)
- **ФИО студента:** `Валерий Д`

## Список файлов в репозитории
1. **nginx.conf** - файл конфигурации сервера Nginx с настройками "по умолчанию";
2. **README.md** - файл с описанием проекта.


## Описание типов файлов
| файл | тип | ссылка |
| ---     | --- | ---   |
| nginx.conf | текст | [download](https://gitlab.rebrainme.com/devops_users_repos/3545/rebrain-devops-task1/-/blob/master/nginx.conf) |
| README.md | текст | [download](https://gitlab.rebrainme.com/devops_users_repos/3545/rebrain-devops-task1/-/blob/master/README.md) |


## Структура содержимого репозитория
```
|—— 
   |—— nginx.conf
   |—— README.md
```
## Содержимое конфигурационных файлов
### Файл nginx.conf
  ```
worker_processes  1;
events {
    worker_connections  1024;
}
http {
    include       mime.types;
    default_type  application/octet-stream;
    sendfile        on;
    keepalive_timeout  65;
    server {
        listen       80;
        server_name  localhost;
        location / {
            root   html;
            index  index.html index.htm;
        }
        error_page   500 502 503 504  /50x.html;
        location = /50x.html {
            root   html;
        }
    }
}

  ```

<a href="http://linkedin.com/in/valeryd" target="_blank"><img src="https://www.askdavetaylor.com/ezoimgfmt/static.licdn.com/scds/common/u/img/webpromo/btn_myprofile_160x33.png" alt="Профиль студента на LinkedIn" style="height: auto !important;width: auto !important;" ></a>
  
## Лицензия
>Посмотреть лицензионное соглашение можно [здесь](https://github.com/IgorAntun/node-chat/blob/master/LICENSE)

Распространяется под лицензией **MIT**.


