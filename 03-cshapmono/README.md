## Тестовые задания

### Стажер

Вакансия тут - https://hh.ru/vacancy/36772881

* ознакомиться с документацией https://github.com/dotnet-presentations/blazor-workshop/tree/master/docs
* запустить приложение через VS2019 Community Preview https://github.com/dotnet-presentations/blazor-workshop/blob/master/src/BlazingPizza.sln
* написать файл `run-debug.bat` в котором добавить секции 
* запустить приложении таким образом через `dotnet watch` чтобы при изменении файлов Razor приложение перекомпилировалось

**Примечание:**

* код скрипта `run-debug.bat` можно подсмотреть тут https://github.com/silverbulleters/OneScript.Web/blob/develop/debug-application/debug.bat
* код настроек файлов за которыми будет следить `dotnet watch` можно подсмотреть тут https://github.com/silverbulleters/OneScript.Web/blob/develop/src/OneScript/OneScriptWeb.csproj#L67

Суть тестового задания - пройти по шагам, запустить тестовое приложение и не потерять интерес к технологии

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
