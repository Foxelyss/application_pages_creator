# Создатель ПРИЛОЖНЕНИЯ

_P.S.: Я знаю про качество кода, она была сделана за минут 10 чтобы успеть в сроки_

Эта cli утилита создаёт документ с кодом по ГОСТу.

Предоставьте программе файлы, она из них сделает документ приложения по ГОСТ. 

Примеры:

```bash
python main.py --application А --file a.docx ~/code/travel-booking/tests/**/*              
```

```bash
python main.py --application Б --file b.docx ~/code/travel-booking/src/DTO/* \
  ~/code/travel-booking/src/*.cs ~/code/travel-booking/src/Models/* \
  ~/code/travel-booking/src/Controllers/* ~/code/travel_booking_app/lib/**/*
```

