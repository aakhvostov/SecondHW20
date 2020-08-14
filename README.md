# NeuroStartUp
![NeuroStartUp_logo](https://camo.githubusercontent.com/c6727c717cad1e4820481abb87524f90782445c5/68747470733a2f2f692e696d6775722e636f6d2f495a4f525769492e706e67)

NeuroStartUp — динамически развивающийся стартап, специализирующийся на поиске с использованием новейших технологий искусственного интеллекта. Наши преимущества:
* Высокая точность поиска
* Высокая скорость поиска
* Низкая цена

## Начало работы

Для получения копии данного проекта с последующим запуском на локальном ПК необходимо сделать следующие действия:
### Prerequisites:

1. [Скачать](https://git-scm.com/download/win) и [установить](https://github.com/netology-code/guides/tree/master/git) Git на Ваш ПК.

### Установка и запуск:

1. Перейти в **локальную** папку на ПК, в которой будет храниться репозиторий и открыть консоль, нажав правой кнопкой в любом месте папки и выбрав **Git Bash Here**
1. Выполнить первоначальные настройки: 
```
git config --global user.name "Vasya Pupkin"     * указать свои Имя и Фамилию
git config --global user.email vasya@localhost   * указать свой e-mail 
```

### Создание локального репозитория:

1. Скопировать в буфер обмена [ULR](https://github.com/aakhvostov/HwFirst.git) репозитория c сайта GitHub.com
1. ввести `git clone + URL` для клонирования репозитория GitHub на локальную машину.

## Лицензия

pass

## Вы можете встроить NeuroStartUp в ваши приложения с помощью следующих сниппетов (кусочков) кода.

### JavaScript:
```
<script src="https://localhost/neuro.sdk.min.js"></script>
```
### Java (Maven):
```
<dependency>
  <groupId>neuro</groupId>
  <artifactId>sdk</artifactId>
  <version>1.0.0</version>
</dependency>
```
### iOS (добавьте код в ваш Podfile):
```
platform :ios, '8.0'
pod "neuro-ios-sdk"
```