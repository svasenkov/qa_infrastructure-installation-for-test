Переходим на сайт https://gradle.org/install/

На странице ищем текст который на скриншоте

![alt-текст][logo]

[logo]: https://github.com/Amidosha/qa_infrastructure-installation-for-test/blob/main/src/intall%20Gradle.jpg ""

Качаем, только **Binary-only**

Создаем новую директорию на диске C:\ и распоковываем папку

Должно получиться как на скриншоте

![alt-текст][2]

[2]: https://github.com/Amidosha/qa_infrastructure-installation-for-test/blob/main/src/intallt%20Gradle_2.jpg ""

Прописываем переменные среды:

Щелкните правой кнопкой мыши по значку «Мой компьютер» (на рабочем столе) и в меню выберите «Свойства».

1. Перейдите на вкладку «Дополнительно».
2. Нажмите «Переменные среды».
3. Под разделом «Переменные среды» нажмите «Создать».
4. В поле «Имя переменной» введите GRADLE_HOME
5. В поле «Значение переменной» введите путь по которому вы распоковали gradle

6. В данном случае C:\Gradle\
7. Нажмите OK.
8. Еще раз нажмите ОК.
9. Перезагрузите компьютер, чтобы изменения вступили в силу.
10. Проверяем, что Gradle установлен

```gradle -v```

#### Оглавление
1. [Установка JDK (Java SE Development Kit)](/src/Install_JDK.md)
2. [Установка Gradle](/src/Install_Gradle.md)
3. [Установка Idea](/src/Install%20Idea.md)
4. [Копирование проекта в идею из github](/src/github.md)
