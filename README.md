# Тестовое задание для ЦФТ ШИФТ по направлению JAVA
## Задание
При запуске утилиты в командной строке подается несколько файлов, содержащих в перемешку целые числа, строки и вещественные числа. В качестве разделителя используется перевод строки.Строки из файлов читаются по очереди в соответствии с их
перечислением в командной строке.

По умолчанию файлы с результатами располагаются в текущей папке с именами integers.txt, floats.txt, strings.txt.

**Ключи**

\-o Путь для результатов

\-p Задаёт префикс имен выходный файлов

\-a Режим добавления в существующие файлы

\-s Вывод короткой статистики (содержит только количество элементов записанный в исходящие файлы)

\-f Вывод полной статистики


### Как запускать?
```
git pull https://github.com/larentiina/shift-demo.git
mvn clean package
java -jar .\target\shift-test-jar-with-dependencies.jar <args>
```
### Особенности реализации
Версия java - 17

Система сборки - Maven  3.9.5

Сторонние библиотеки:
- Apache Commons CLI
```
<dependency>
            <groupId>commons-cli</groupId>
            <artifactId>commons-cli</artifactId>
            <version>1.4</version>
        </dependency>
```
- Lombok
  ```
   <dependency>
            <groupId>org.projectlombok</groupId>
            <artifactId>lombok</artifactId>
            <version>1.18.30</version>
            <scope>provided</scope>
        </dependency>
  ```
