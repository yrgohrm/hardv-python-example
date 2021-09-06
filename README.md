# Enkla exempel för kursen Hårdvarunära programmering

Följande är exempel på en enkel server/klient för MQTT som använder
sig av bibliotektet paho-mqtt samt en enkel webserver baserad på Flask.

Samtliga exempel använder sig av pipenv.

För att komma igång med pipenv:

Första gången måste du installera pipenv:
```
pip install pipenv
```

Sedan första gången du skall använda pipenv med något du hämtat från Git:
```
cd project-directory-with-pipfile
pipenv install
```

Sedan för att komma åt programmet och dess bibliotek (ståendes i katalogen med Pipfile):
```
pipenv shell
```

Sedan där i kan du köra Python som vanligt (eller flask för den delen).
