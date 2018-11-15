# Создание децентрализованного приложения для голосования
Создайте свое первый децентрализованное приложение, или Dapp, в Ethereum сети с этой инструкцией!
Чтобы загрузить, установить и запустить этот проект, выполните следующие действия.

## Зависимости
Установите эти зависимости для выполнения задания.
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

## Шаг 1. Клонирование проекта
`git clone https://github.com/blockchain-dapp/dapp-on-truffle-homework-ваш_аккаунт`

## Шаг 2. Установка зависимостей
```
$ cd dapp-on-truffle-homework-ваш_аккаунт
$ npm install
```

## Шаг 3. Запуск Ganache
Откройте клиент GUI ganache, который вы скачали и установили. Это приведет к запуску локального экземпляра блокчейна.

## Шаг 4. Компиляция и развертывание смарт-контракта для теста truffle
`$ truffle migrate --reset`

Будет скомпилирован и развернут контракт Migrations.sol из truffle box "pet-shop"
Вы должны развертывать смарт-контракт каждый раз, когда перезапускаете Ganache.

## Шаг 5. Настройка Metamask
* Разблокировать Metamask
* Подключите metamask к вашему локальному Ethereum blockchain, предоставленному Ganache.
* Импортируйте аккаунт, предоставленный Ganache.

## Шаг 6. Запуск и проверка работы приложения
`$ npm run dev`

Посетите этот URL-адрес в браузере: http://localhost:3000
## Шаг 7. Выполнить основное задание