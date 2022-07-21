# **API Kittygram2**
### Описание:
Инстаграм для котиков без фронтенда. **Учебный проект**.<br/>
К проекту [Kittygram](https://github.com/Banes31/kittygram) заявлены новые требования: пользователи хотят самостоятельно регистрироваться в нашем сервисе.<br/>
Мало того: нужно настроить проект так, чтобы добавлять, обновлять и удалять информацию о котиках могли только их хозяева.
Судя по всему, нового релиза не избежать. Ну что ж, пусть будет Kittygram2.

### Что новенького?
- Модель Owner больше не понадобится, вместо неё будем использовать встроенную модель User;
- В новой версии проекта работаем исключительно с вьюсетами, так удобнее;
- Чтобы дать возможность пользователям самостоятельно регистрироваться через API и обеспечить доступ по токену, воспользуемся связкой JWT+Djoser.

### Стек:
![python version](https://img.shields.io/badge/Python-3.7-green)
![django version](https://img.shields.io/badge/Django-3.2-green)
![djangorestframework version](https://img.shields.io/badge/DRF-3.12-green)
![djoser version](https://img.shields.io/badge/djoser-2.1-green)
![simplejwt version](https://img.shields.io/badge/DRFsimplejwt-4.8-green)

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram2.git
```

```
cd kittygram2
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

### **Автор**
[Иван Зоренко](https://github.com/Banes31)
