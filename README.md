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
><br/>Вы можете создать в папке с coder.py файл <code>key.txt</code> и написать внутри него ключ шифрования любой длины. После этого код будет учитывать присутствие key.txt при кодирование файлов и в дальнейшем такие видеофайлы обратно декодироваться правильно будуту только с правильным ключом, указанном в key.txt.
