## Лабораторная работа 1

1. Создаю новый файл с именем `script.bash`
```bash
touch script.bash
```

2. Открываю созданный файл `scrip.bash` через команду `nano` 
``` bash
nano script.bash
```

3. Вписываю в открытый файл скрипт
```bash
#!/bin/bash

echo "Welcome to ITMO University"
```

4. Сохраняю файл через клавиши `cntl+x` => `Y` => `Enter`. На главном экране я вижу опять терминал.

5. Вывожу содержимое (запускаю bash-скрипт) через команду `bash`
```bash
bash script.bash
```
 ![Screenshot from 2024-09-30 09-26-44](https://github.com/user-attachments/assets/34f0c2f5-4d93-4a71-b86b-fa6a54931b99)
 

 ### Задача

 1. Открываем уже созданный нами файл `script.bash`, через команду `nano`
``` bash
nano script.bash
```

2. Как справится с задачей указаной в лабораторной нашла в интернете, на сайте https://habr.com/ru/companies/ruvds/articles/326328/. Меняем третью строку так, чтобы в файле было написано:
```bash
#!/bin/bash

"Welcome, "$*
```

3. Сохраняем изменения через клавиши `cntl+x` => `Y` => `Enter`. На главном экране я вижу опять терминал.

4.  Вывожу содержимое (запускаю bash-скрипт) через команду `bash` и после написаной команды надо написать имя того, к кому будет адресован вывод файла
```bash
bash script.bash Vasya Pupkin
```

 5. После перехода на новую строку, программа выводит
`Welcome, Vasya Pupkin`

![Screenshot from 2024-09-30 09-32-07](https://github.com/user-attachments/assets/0e055f39-a136-4cd7-805f-61088a6d93ba)






