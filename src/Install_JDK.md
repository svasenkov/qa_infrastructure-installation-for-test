
1. Проверяем наличие уже установленной Java

Открываем терминал Windows и набираем ```java -version```

Если в ответ мы получаем, данную надпись

```java version "1.8.0_"```

Всё, что ниже нам не важно,

то JAVA у вас установлена правильно, 
если цифры отличны от тех, что выше,

то рекомендуется поставить 8 версию Java

Переходим на сайт https://www.oracle.com/ru/java/technologies/javase/javase-jdk8-downloads.html

Ищем данный пункт как на скриншоте

![alt-текст][logo]

[logo]: /src/install%20JDK.jpg ""

Скачиваем по ссылке напротив вашей системы, возможно потребуется регистрация

Устанавливаем и копируем путь куда установилась

Прописываем переменные среды: 

Щелкните правой кнопкой мыши по значку «Мой компьютер» (на рабочем столе) и в меню выберите «Свойства».
1. Перейдите на вкладку «Дополнительно».
2. Нажмите «Переменные среды».
3. Под разделом «Системные переменные» нажмите «Создать».
4. В поле «Имя переменной» введите JAVA_HOME.
5. В поле «Значение переменной» введите путь по которуму у вас установлена JAVA, обычно устанавливатся в C:\Program Files\Java\jdk
6. Нажмите OK.
7. Еще раз нажмите ОК.
8. Перезагрузите компьютер, чтобы изменения вступили в силу.
9. Проверяем, что версия JAVA теперь 1.8.0_

Если всё успешно переходим к следующему шагу

#### Оглавление
1. [Установка JDK (Java SE Development Kit)](/src/Install_JDK.md)
2. [Установка Gradle](/src/Install_Gradle.md)
3. [Установка Idea](/src/Install%20Idea.md)
4. [Копирование проекта в идею из github](/src/github.md)
