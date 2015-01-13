Как запустить
=============

1. Установить питон 2.7
2. Установить peewee (должно сработать pip install peewee)
3. Установить Pillow (зависит от платформы, подробности в [документации](https://pillow.readthedocs.org/installation.html))
4. Прописать переменную окружения SELFIE_MODERATOR_CODE
5. Создать файл src/local_settings.py и переопределить в нем локальные пути (можно не делать, если стандартные пути подходят)
6. Запустить python selfie.py