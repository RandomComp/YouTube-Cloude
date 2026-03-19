# YouTube-Cloude
---
## Создайте виртуальное окружение
><br/><code>python3 -m venv venv</code>
## Активируйте виртуальное окружение
**Для Windows:**
><br/><code>venv\bin\activate</code>

**Для Linux/MacOS:**
><br/><code>source venv/bin/activate</code>

## Далее вам понадобится установить зависимости
><br/><code>pip install -r requirements.txt</code>

**os, math, subprocess, tempfile, shutil, sys, re, hashlib -- встроенные модули python**
---
# Для кодирования любого файла:
><br/><code>python coder.py endcode FILENAME.xxx FILENAME.mp4</code>
<br/>Где .xxx - это расширение вашего файла, который находится в одной папке с coder.py
---
# Для декодирования видеофайла:
><br/><code>python coder.py decode FILENAME.mp4</code>
---
## Ключ шифрования
><br/>Вы можете указать ключ шифрования с помощью файла <code>key.txt</code> в рабочей папки, ключ может быть любой длины. После этого скрипт будет применять ключ шифрования при кодирование и декодировании файла, при этом нужно иметь правильный ключ шифрования, в ином случае, файл будет битым.
