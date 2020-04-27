## Тестовые задания

### Стажер

* ознакомиться с документацией https://github.com/dotnet-presentations/blazor-workshop/tree/master/docs
* запустить приложение через VS2019 Community Preview https://github.com/dotnet-presentations/blazor-workshop/blob/master/src/BlazingPizza.sln
* написать файл `run-debug.bat` в котором добавить секции 
* запустить

### Разработчик

* добавить функционал ASP.NET Identity таким образом, чтобы:
  * в sqlite базе приложения создались таблицы, положенные для IdentityDbContext (ASPNetUsers и т.д.)
  * добейтесь, чтобы аутентификация Twitter была сохранена в таблице AspNetUserLogins

### Ведущий разработчик

* добавьте в приложение `BlazingPizza` службу фоновых заданий на основе Hangfire
* подключите коммуникацию с пользователем через библиотеку SignalR
* реализуйте функциональность:
  * каждые 5 минут средствами Hangfire изменяйте статус доставки заказа клиента
  * оповещайте клиента при помощи SignalR об изменении статуса
