# hakaton-prerequisites

## Frontend
Установить приложения:
+ [VS Code](https://code.visualstudio.com/)  
+ [WebStorm](https://www.jetbrains.com/webstorm/)

Установить пакеты:
+ [node.js](https://nodejs.org/) 10.15.3 LTS вместе с npm

  Проверить: 
  ~~~
  $ node --version
  $ npm --version
  ~~~
+ [Vue.js](https://cli.vuejs.org/guide/installation.html) 
  ~~~
  $ npm install -g @vue/cli
  $ vue --version
  ~~~
  
  
### Создание проекта
~~~
vue create hello-world
>Manually select features
 (*) Babel
 ( ) TypeScript
 ( ) Progressive Web App (PWA) Support
 (*) Router
 (*) Vuex
 ( ) CSS Pre-processors
 (*) Linter / Formatter
 ( ) Unit Testing
 ( ) E2E Testing
 
 ? Use history mode for router? (Requires proper server setup for index fallback in production) (Y/n) n
 > ESLint with error prevention only
 >(*) Lint on save
 > In dedicated config files
~~~

[Vuetify](https://www.youtube.com/watch?v=taLKQfoS87I&list=PL4cUxeGkcC9iCKx06qSncuvEPZ7x1UnKD&index=6&t=0s) или Bootstrap vue
Положить в репозиторий к джанго(перед этим удалить (в папке с VUE) .gitignore, .git и readme) 
и положить node_modules в .gitignore

  ---
## Backend
Установить приложения:
+ [Pycharm](https://www.jetbrains.com/pycharm/)

Установить пакеты:
+ Python 3.6(3.7), pip

### Создание проекта
создать 
+ Django проект
+ создать venv, запустить
+ Установить [Django cors header](https://pypi.org/project/django-cors-headers/)
+ Установить django-rest-framework
   ~~~
   pip install django-rest-framework
   ~~~
+ `pip freeze > requirements.txt`

### Склонировать проект к себе
+ Склонировать репозиторий
+ Cоздать venv и активировать (venv/Scripts/activate.bat)
+ `pip install requirements.txt`
+ `python manage.py makemigrations`
+ `python manage.py migrate`
+ `npm install package.json` (возможно cd в директорию) 

Если не находит таблицу, то

`python manage.py migrate --run-syncdb`
