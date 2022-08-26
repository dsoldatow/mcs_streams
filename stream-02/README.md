# 2 стрим

### Что сделали?

* Написали файл для всех интеграций с watchdata (watchdata.py)
* Написали процессор для нахождения всех новых трансферов в нескольких блокчейнах (processor.py)

### Ошибки, которые мы исправили

* Убежим быстрее блокчейна и перестанем получать трансферы, либо отстать

* В случае форка вернем форкнутые данные пользователю

* Если сервис упадет, потеряем часть блоков, потому что перезапустимся с последними в блокчейна

### Материалы
* [Слайды лекции](https://drive.google.com/file/d/12SrXWR6kDgH2YiGIiN9T2vw9CZh-EUYX/view?usp=sharing)