# Создатель ПРИЛОЖНЕНИЯ

Эта cli утилита создаёт документ с кодом по ГОСТу.

Предоставьте программе файлы, она из них сделает документ приложения по ГОСТ. 

Код достаточно простой, если хотите добавить опцию, сделайте свой вклад!

Примеры:

```bash
python main.py --application А --file a.docx ~/code/travel-booking/tests/**/*              
```

```bash
python main.py --application Б --file b.docx ~/code/travel-booking/src/DTO/* \
  ~/code/travel-booking/src/*.cs ~/code/travel-booking/src/Models/* \
  ~/code/travel-booking/src/Controllers/* ~/code/travel_booking_app/lib/**/*
```

