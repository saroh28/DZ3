# Инструкция по работе с программой Git

## Начало работы
+ Создаем папку в которой будем хранить проект.
+ Устанавливаем Git и Visual Studio Code.
## Настройка VSC
+ Во кладке вид включаем терминал
+ В терминале:  git config ­­global user.name "######" и 
    
    git config ­­global user.email #####@gmail.com
## Создаем репозиторий
+ Открываем в проводнике нашу папку
+ В терминале набираем git init 
## Продолжаем работу в VSC
+ Создаем новый файл с расширением .md
+ В терминале набираем git add и название файла
+ В терминале набираем git commit -m "Комментарий"
## Создаем новые ветки
+ Набираем git branch и название новой ветки
+ Переключаемся на новую ветку: git checkout название ветки
+ Вносим изменения на новой ветке
+ Используем git add и git commit для добавления и сохранения изменений на новой ветке.
## Слияние веток
+ Переходим на главную ветку при помощи команды git checkout имя ветки
+ Набираем git merge имя ветки
## Удаление веток
+ Для удаления ветки (после слияния)
набираем git branch -d имя удаляемой ветки.
## Работа с удаленным репозиторием
+ Копируем ссылку нужного репозитория
+ Открываем папку
+ В VSC пишим git clone ссылка
+ Вносим изменения в проект
