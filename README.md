# Diploma
Дипломный проект курса Skillbox "GO-разработчик"
Сервис, который будет принимает запросы по сети и возвращать данные о состоянии систем компании. 
Данные выводятся на веб-страницу сайта компании и содержат в себе StatusPage, географию и статусы сервисов.
Киенты смогут проверить свой регион на наличие ошибок самостоятельно, = сократится кло-во обращений.

### Для копирования проекта:
Копируем себе локально проект  командой 
```
git clone https://github.com/RublevAleksey/go-diploma
```

### Для запуска:
1 переходим в папку simulator
```cd go-finale/simulator```
2 запускаем симулятор командой 
```go run main.go```
сгенерируются тестовые данные, которые получает сервис
3 переходим в папку cmd 
```cd go-finale/cmd```
4 запускаем сервис командой 
```go run main.go```
5 переходим в папку web 
```cd go-finale/web```
6 запускаем status_page.html для отображения результата 
```go run status_page.html```



