# C#
https://metanit.com/sharp/tutorial/6.1.php  
https://docs.microsoft.com/en-us/visualstudio/releases/2019/release-notes-preview  
https://devblogs.microsoft.com/dotnet/  

https://www.youtube.com/watch?v=l0AVCzPTP-o  
Платформа .NET работает на операционной системе Windows и состоит их виртуальной машины CLR ([Common Language Runtime](https://en.wikipedia.org/wiki/Common_Language_Runtime)) и набор библиотек FCL ([Framework Class Library](https://en.wikipedia.org/wiki/Framework_Class_Library)) для исполнения байт-кода виртуальной машины, который можно сформировать компилятором для различных высокоуровневых языков программирования: C#, C++, F#, PHP, Visual Basic и т. д.  

Для операционной системы Linux существует платформа MONO или [DotGNU Portable.NET](https://en.wikipedia.org/wiki/DotGNU), которые могут выполнять байт-код, данные платформы состоят из виртуальной машины (VM) и FCL под API Linux.

# .NET Core (или .NET)  
.NET - это бесплатная кроссплатформенная платформа с открытым исходным кодом для разработки приложений различных типов.  
В .NET вы можете использовать несколько языков, редакторов и библиотек для создания веб-приложений, мобильных устройств, компьютеров, игр и IoT.  
https://dotnet.microsoft.com/  

Платформа .NET = CLR + FCL  
Common Language Runtime (CLR) - виртуальная машина для интерпретации байт-кода (JIT-кода Just In Time Compilation), формирования машинного кода (native-code) и запуска его на процессоре текущей ОС.  
Framework Class Library (FCL) - фроеймворк, библиотека классов для разработки приложений.  
Компилятор C# выполняет компиляцию исходного кода на языке C# в байт-код, байт-код хранится в файле *.exe но данный файл имеет метку, что это байт-код и ОС Windows запускает его на исполнение в виртуальной машине.

Репозиторий платформы .NET https://github.com/dotnet/core  
Загрузка SDK (для разработки) или .NET runtime (виртуальной машины для выполнения) с сайта https://dotnet.microsoft.com/download

После установки необходимо создать переменную среды DOTNET_ROOT со ссылкой на папку SDK .NET = \Programs\dotnet\  и добавить данный путь в переменную среды PATH.  

Пример web приложения https://dotnet.microsoft.com/learn/aspnet/hello-world-tutorial/intro  
Документация ASP.NET https://docs.microsoft.com/ru-ru/aspnet/core/?view=aspnetcore-5.0  
Учебные материалы по ASP.NET https://dotnet.microsoft.com/learn/aspnet  

[Книга "CLR via C#. Программирование на платформе Microsoft .NET Framework 4.5 на языке C#"](https://www.ozon.ru/context/detail/id/21236101/?from=bar)


Замеры производительности web-приложений  
https://www.techempower.com/benchmarks/

# Шаблоны проектирования
https://docs.microsoft.com/ru-ru/azure/architecture/patterns/cqrs  

# Frameworks
https://docs.microsoft.com/ru-ru/ef/core/managing-schemas/migrations/?tabs=dotnet-core-cli  

