# hillel_python_hw_1
https://github.com/darloboyko/hillel_python.git
1. Возвращать содержимое файла с пайтон пакетами (requirements.txt)
PATH: /requirements/ открыть файл requirements.txt и вернуть его содержимое


2. Вывести 100 случайно сгенерированных юзеров (почта + имя) 'Dmytro aasdasda@mail.com'
PATH: /generate-users/ ( https://pypi.org/project/Faker/ )
+ параметр который регулирует количество юзеров


3. Считать файл hw.csv и посчитать средний рост, средний вес в см и кг соответственно
PATH: /mean/


4. Вывести количество космонавтов в настоящий момент (http://api.open-notify.org/astros.json) (https://pypi.org/project/requests/)
PATH: /space/


import requests
r = requests.get('https://api.github.com/repos/psf/requests')
r.json()["description"]


!!! прислать 3 файла main.py, utils.py, requirements.txt !!!
