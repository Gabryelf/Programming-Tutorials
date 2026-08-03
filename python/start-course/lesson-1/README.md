<div align="center">
  <br>
  <img src="https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/images/icons_lang/Python-Dark.svg" width="120" height="120" alt="Python">
  <br>
  <br>
  
  # 🐍 Урок 1: Первое знакомство с Python
  
  <p align="center">
    <strong>🚀 Старт в мир программирования</strong><br>
    <em>Установка, настройка и первый код</em>
  </p>

  
  <p align="center">
    <a href="#-цель-урока">
      <img src="https://img.shields.io/badge/🎯-Цель_урока-4B8BBE?style=for-the-badge" alt="Цель">
    </a>
    <a href="#-установка-python">
      <img src="https://img.shields.io/badge/📥-Установка_Python-3776AB?style=for-the-badge" alt="Установка">
    </a>
    <a href="#-первая-программа">
      <img src="https://img.shields.io/badge/💻-Первая_программа-FFD43B?style=for-the-badge" alt="Программа">
    </a>
  </p>

</div>

---


# 🐍 Урок 1: Установка Python и создание первой программы

> [!NOTE]
> Без установки особого программного обеспечения, нам будут недоступны файлы написанные на Python, которые нам надо будет писать. То есть ваш компьютер не знаком с этим языком и ему требуется интерпретатор, именно эта программа или служба, именно она будет объяснять машине (компу), что же именно мы написали! Но зачастую собранные специально готовые программы будут доступны на любом компьютере, даже на том на котором Python не установлен!

## 🎯 Цель урока
В этом уроке мы:
1. Установим интерпретатор Python на компьютер
2. Установим среду разработки (IDE) на выбор
3. Создадим первую программу "Hello, World!"
4. Научимся запускать код в терминале и в IDE

## 📋 Что нам понадобится
- Компьютер с Windows 10/11
- Доступ в интернет
- Немного терпения 😊

---

## Часть 1: Установка Python

### Шаг 1: Скачивание установщика

1. Откройте браузер и перейдите на официальный сайт Python:
   ```
   https://www.python.org/downloads/
   ```

   ![Скачивание Python](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py1.png)

2. Нажмите на жёлтую кнопку **"Download Python X.X.X"** (будет показана последняя версия).

3. Файл установщика сохранится в папку **Загрузки** вашего компьютера.
> Вы так же можете ознакомиться с документацией и сайтом в целом, так как это официальное храние языка и технологий связанных с ним.
> 
 ![Версии Python](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py2.png)
>
> Информация о версиях даст вам контроль над теми свойствами которые вы захотите использовать стабильно. Рекомендую не забывать про этот сайт и добавить его в закладки, что бы позже вернуться сюда за большей информацией.
>
 ![Документация Python](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py3.png)
>
---


### Шаг 2: Запуск установки

1. Найдите скачанный файл в папке **Загрузки** (обычно называется `python-X.X.X-amd64.exe`).

   ![Установка Python шаг 1](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py4.png)

2. **ВАЖНО!** В самом низу окна установки обязательно поставьте галочку **"Add Python to PATH"**.
   
   Это позволит запускать Python из любой папки через командную строку.

3. Нажмите кнопку **"Install Now"** для стандартной установки.

   ![Установка Python шаг 2](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py5.png)

4. Дождитесь окончания установки. Появится окно с сообщением "Setup was successful".

---

### Шаг 3: Проверка установки

1. Нажмите клавиши **Win + R**, введите `cmd` и нажмите Enter.
2. В открывшемся окне командной строки введите:
   ```bash
   python --version
   ```
   Вы должны увидеть что-то вроде:
   ```
   Python 3.12.0
   ```

   Если вы видите версию Python — всё работает!

    ![Установка Python шаг 3](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py6.png)


---

## Часть 2: Установка редактора кода

> [!TIP]
> Выберите один из трёх вариантов. Для новичков я рекомендую **PyCharm** или **VS Code**.
> Лучше всего если вы откроете все три сайта для скачивания и убедитесь сразу, что именно для вас подходит.
> Но, я все же советую, если это возможно, установить все три варианта, так как они равноценно полезны для тех или иных задач связанных с программированием. Далее мы разберем установку каждого из трех редакторов, а чуть позже в других уроках я покажу как именно работать в каждом из них.

### Вариант A: PyCharm (рекомендуется для полноценной работы с Python).

**PyCharm** — это профессиональная среда разработки с подсветкой кода, подсказками, отладчиком и множеством плагинов.

1. Перейдите на сайт: 
   ```
   https://www.jetbrains.com/pycharm/download/
   ```

   ![Скачивание PyCharm](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py7.png)

2. Выберите версию **Community** (бесплатная) и нажмите **Download**.

3. Запустите скачанный установщик.

4. В настройках установки оставьте все галочки по умолчанию и нажмите **Next**.

5. После установки запустите PyCharm.

---

### Вариант B: VS Code (универсальный редактор)

**VS Code** — лёгкий редактор с поддержкой Python через расширения. Но что еще важнее, в нем можно писать не только на Python, и это может пригодиться для смежных языков и технологий.

1. Перейдите на сайт:
   ```
   https://code.visualstudio.com/download
   ```

   ![Скачивание VS Code](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py8.png)

2. Скачайте установщик для Windows.
3. Запустите установку, принимая все настройки по умолчанию.

   ![Установка VS Code](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py9.png)

      ![Скачивание Sublime Text](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py10.png)

5. **Важно!** После установки установите расширение Python:
   - Откройте VS Code
   - Нажмите на иконку расширений (слева, 4 квадрата)
   - Найдите "Python" от Microsoft
   - Нажмите **Install**

---

### Вариант C: Sublime Text (минималистичный редактор)

**Sublime Text** — быстрый и простой редактор, хорошо подходит для написания небольших скриптов.

1. Перейдите на сайт:
   ```
   https://www.sublimetext.com/download
   ```

   ![Скачивание Sublime Text](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py11.png)

   ![Создание проекта](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py12.png)

3. Скачайте установщик для Windows.
4. Запустите установку, следуя инструкциям на экране.

---

## Часть 3: Создаём первую программу

Теперь мы создадим папку для наших проектов и напишем первую программу.

### Шаг 1: Создание папки проекта

1. Создайте папку `my_first_python` на рабочем столе (имя папки важно только для подсказок далее, вы можете назвать ее иначе).
2. Откройте эту папку.

---

### Шаг 2: Создаём файл с кодом

#### В PyCharm:
1. Откройте PyCharm → **New Project**
2. Укажите путь к папке: `C:\Users\Ваше_имя\Desktop\my_first_python`
3. Нажмите **Create**

   ![Создание проекта](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py13.png)

4. В открывшемся окне кликните правой кнопкой по папке проекта → **New → Python File**
5. Назовите файл `hello` и нажмите Enter.

#### В VS Code:
1. Откройте VS Code → **File → Open Folder**
2. Выберите папку `my_first_python` (или любую другую)
3. Нажмите на иконку "New File" в боковой панели или нажмите **Ctrl+N**
4. Сохраните файл как `main.py` (не забудьте расширение `.py`)

   ![Создание проекта](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py14.png)

     ![Создание проекта](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py17.png)

#### В Sublime Text:
1. Откройте Sublime Text
2. Нажмите **File → New File**
3. Нажмите **File → Save As...**
4. Выберите папку `my_first_python` (или любую другую), назовите файл `main.py`
 
  ![Создание проекта](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py15.png)


---

### Шаг 3: Пишем код

Вставьте в созданный файл следующий код:

```python
# ==========================================
# Первая программа на Python
# ==========================================

# Команда print() выводит текст на экран
print("Hello, World!")

# Можно выводить числа
print(42)

# Можно выводить несколько значений через запятую
print("Меня зовут", "Python", "!", "Мне", 33, "года")

# Команда input() запрашивает ввод от пользователя
name = input("Как тебя зовут? ")

# Выводим приветствие с именем
print("Привет,", name, "! Добро пожаловать в мир Python!")
```

> **Объяснение кода:**
> - `#` — это комментарий, компьютер его игнорирует, он нужен для людей
> - `print()` — команда для вывода текста на экран
> - `input()` — команда для ввода текста с клавиатуры
> - `name` — это переменная, в которой мы сохраняем введённое имя

---

### Шаг 4: Запуск программы

#### В PyCharm:
- Нажмите правой кнопкой по файлу `main.py`
- Выберите **Run 'main'**
- Или просто нажмите зелёную кнопку ▶️ в правом верхнем углу

   ![Запуск в PyCharm](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py16.png)

#### В VS Code:
1. Откройте файл `main.py`
2. Нажмите на треугольник ▶️ в правом верхнем углу
3. Или нажмите **Ctrl+F5**

 ![Запуск в VS](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py18.png)

#### В Sublime Text:
1. Откройте файл `hello.py`
2. Нажмите **Tools → Build**
3. Или нажмите **Ctrl+B**

 ![Запуск в VS](https://github.com/Gabryelf/Programming-Tutorials/blob/main/docs/screens/python/start-lesson-1/py19.png)

#### Через командную строку (работает всегда):
1. Откройте командную строку (Win+R → cmd)
2. Перейдите в папку с файлом:
   ```bash
   cd C:\Users\Ваше_имя\Desktop\my_first_python
   ```
3. Запустите программу:
   ```bash
   python hello.py
   ```

---

## 🎉 Результат

После запуска вы должны увидеть в консоли что-то вроде:

```
Hello, World!
42
Меня зовут Python ! Мне 33 года
Как тебя зовут? [Ваше имя]
Привет, [Ваше имя] ! Добро пожаловать в мир Python!
```

Поздравляю! Вы написали и запустили свою первую программу на Python! 🎊

---

## 📚 Домашнее задание

1. Измените текст приветствия на свой вариант.
2. Добавьте ещё одну переменную для возраста и выведите её.
3. Попробуйте вывести на экран математическое выражение, например: `print(2 + 2 * 2)`

---

## ❓ Что делать, если что-то пошло не так?

| Проблема | Решение |
|----------|---------|
| `python` не распознаётся | Вы забыли поставить галочку "Add to PATH" при установке. Переустановите Python. |
| Файл не запускается | Убедитесь, что файл имеет расширение `.py`, а не `.txt` |
| Ошибка синтаксиса | Проверьте кавычки и скобки — они должны быть на английской раскладке |

---

## 🔗 Полезные ссылки

- [Официальная документация Python](https://docs.python.org/3/)
- [Python для начинающих (видео)](https://www.youtube.com/)
- [Онлайн-песочница для кода](https://www.online-python.com/)

---

## 📁 Файлы урока

В этой папке вы найдёте:
- `README.md` — эта инструкция
- `screens/` — скриншоты для наглядности
- `hello.py` — наша первая программа

> **Урок 2:** переменные, типы данных и базовые операции с числами.



