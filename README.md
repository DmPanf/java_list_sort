# java_list_sort
JAVA simple code for student list sorting based on Stream API

## JAVA on Manjaro Linux
- **`sudo pacman -S jdk-openjdk`**

- Команда javac Main.java компилирует ваш файл Main.java и создает файл Main.class, который содержит байт-код Java.
- **`javac Main.java`**

- Команда java Main загружает и выполняет класс Main.
- **`java Main`**
  

## Short Description [Main.java]

- Пример кода на Java, который демонстрирует использование Stream API для обработки коллекций данных.
- Код сортирует список студентов по оценкам и фильтрует только тех, у кого оценка выше определенного значения.
- В этом коде Student - это вложенный класс, который представляет студента с именем и оценкой.
- Создаем список студентов, а затем используем Stream API для фильтрации и сортировки этого списка.
- Stream API это мощный инструмент для обработки данных в Java, который позволяет писать более короткий, читаемый и многопоточный код.


## Short Description [Main2.java]

- Код демонстрирует использование интерфейса Comparable для сортировки объектов по определенному свойству.
- Использование интерфейса Comparable - это общепринятый подход для определения, как объекты определенного класса могут быть упорядочены или сравнены между собой.
- В этом коде Student - это класс, который реализует интерфейс Comparable.
- Метод compareTo используется для определения, как объекты Student должны быть упорядочены по их оценкам.
- Метод Arrays.sort сортирует массив студентов в соответствии с порядком, определенным методом compareTo.
- Пример показывает, как можно управлять порядком объектов в массиве или коллекции, определяя собственные правила сортировки с использованием интерфейса Comparable.
- Это очень полезно при работе с объектами, которые имеют естественный порядок, который должен быть отслежен.
