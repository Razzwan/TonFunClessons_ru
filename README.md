# Уроки по разработке на блокчейне The Open Network(TON)

В данном репозитории представлены уроки для блокчейна TON. Уроки расположены в соответствующих папках в формате .md, также к каждому уроку приложен код. Моё комьюнити - [здесь](https://t.me/ton_learn). Lessons in English [here](https://github.com/romanovichim/TonFunClessons_Eng).

> Если совсем не разбираетесь в блокчейн разработке, начините [отсюда](./intro/intro.md) 

# Пишем смарт-контракты на FunC
| Номер  | Урок | Рассмотренные концепции  | Ссылка | 
| ------------- | ------------- | ------------- | ------------- | 
| 1  | Первый смарт-контракт | Типы,Исключения, фукнции, деплой контрактов, запросы к смарт-контракту в тестовой сети  | [LINK](./lessons/smartcontract/1lesson/firstlesson.md)  | 
| 2 | Тесты на FunC для первого смарт-контракта  | Логика тестов на FunC ,cтруктура тестов, кортежи   |  [LINK](./lessons/smartcontract/2lesson/secondlesson.md) | 
| 3 | Сообщения, пишем прокси контракт | Сообщения, режимы сообщений, примтивы, ссылки на ячейки  |  [LINK](./lessons/smartcontract/3lesson/thirdlesson.md) | 
| 4 | Тестируем сообщения |  Адреса,TL-B, регистр с5 и выходные действия | [LINK](./lessons/smartcontract/4lesson/forthlesson.md)  | 
| 5 | Флаги и хранение данных в контракте | Op - для идентификации  операций, Computational fees, примитивное хранение данных в контракте   | [LINK](./lessons/smartcontract/5lesson/fifthlesson.md)  |  
| 6 | Тестируем флаги и хранение данных в контракте | Различные тесты для сообщений с флагами и хранения данных в регистре с4  | [LINK](./lessons/smartcontract/6lesson/sixthlesson.md)  | 
| 7 | HashMap хранилище  | Работа со Словарями(hashmap): хранение, удаление, поиск  | [LINK](./lessons/smartcontract/7lesson/seventhlesson.md) | 
| 8 | Тестируем HashMap хранилище  | Тестируем HashMap(словари), особые функции toncli для тестирования, регистр с7  | [LINK](./lessons/smartcontract/8lesson/eighthlesson.md)  | 
| 9 | Разбираем стандарт Jetton(Fungible Token)  | Токены, стандарты, стандарт Jetton, StateInit, воркчейны  | [LINK](./lessons/smartcontract/9lesson/ninthlesson.md)  | 
| 10 | Разбираем стандарт NFT(Non-Fungible Token)  | NFT, стандарт NFT, коллекции и отдельные NFT  | [LINK](./lessons/smartcontract/10lesson/tenthlesson.md)  | 

> Написание таких туториалов большая работа - буду рад вашей звездочке на репозитории 🌟 

# Разбираемся в Pipeline работы со смарт-контрактами

| Урок | Рассмотренные концепции  | Ссылка | 
| ------------- | ------------- | ------------- | 
| Простой контракт в ton-community/sandbox | создаем ton-community/sandbox проект, пишем и компилируем контракт | [LINK](./lessons/pipeline/simplesmartcontract.md)  | 
| Пишем тесты в ton-community/sandbox | тесты на фреймворке jest  |  [LINK](./lessons/pipeline/simpletest.md) | 
| Деплоим смарт-контракт используя QR-код | паплайн деплоя смарт-контракта в тестовую сеть |  [LINK](./lessons/pipeline/simpledeploy.md) | 
| Чат-бот смарт-контракт |   | [LINK]()  | 
| Пишем onchain тесты в тестовой сети |   | [LINK]()  |  

> Автор уроков публикует новые туториалы, пишет о интересных компаниях в блокчейн сфере [здесь](https://t.me/ton_learn) 

# Get-запросы в TON

| Урок | Рассмотренные концепции  | Ссылка | 
| ------------- | ------------- | ------------- | 
| ton.js | Получаем данные из смарт-контракта с помощью JS(ton.js)  | [LINK](./lessons/requests/20lesson/tonjs.md) | 
| ADNL Protocol Intro | Connection to ADNL, getAccountState, getMasterchaininfo  | [LINK](./lessons/requests/ADNL/adnlintro.md) | 
| ADNL Run GetMethod | Вызов Гетметода, логика аналитики продаж НФТ  | [LINK](./lessons/requests/ADNL/adnlgetsale.md) | 
| Collect account txes using ADNL | Logical time, последние транзакции аккаунта  | [LINK](./lessons/requests/ADNL/adnltxes.md) | 

# Авторизация и отправка транзакций с UI за 5 минут c TON Connect React UI

| Урок | Рассмотренные концепции  | Ссылка | 
| ------------- | ------------- | ------------- | 
| TON Connect auth button| Простой сайт с авторизацией через TonConnect, концепция разделения на кошельки и приложения Web3  | [LINK](./lessons/tonconnect/button.md) | 
| TON Connect send transaction | Использование Обёрток контрактов, отправка транзакций, вызов Get-методов c Фронтеда  | [LINK](./lessons/tonconnect/sendtx.md) | 

# Golang Scripts - удобные скрипты для работы с TON

| Урок | Рассмотренные концепции  | Ссылка | 
| ------------- | ------------- | ------------- | 
| Создаем кошелек и деплоим смарт-контракт | Работаем с TON с помощью GO, создание кошелька, hexBOC форма контракта, отправка сообщений, вызов GET метода | [LINK](./lessons/golang/14lesson/wallet.md) | 
| Создание NFT коллекции | Получаем информацию о NFT коллекции и отдельном элементе, Деплоим коллекцию и элемент в сеть | [LINK](./lessons/golang/15lesson/NFTCollectionDeploy.md) |
| Выпускаем свои токены: ICO | Jettons ICO, баланс кошелька Jetton  | [LINK](./lessons/golang/16lesson/ICO.md)
# Бонусы

| Урок | Рассмотренные концепции  | Ссылка | 
| ------------- | ------------- | ------------- | 
| Random in TON| Raffle Smart Contract, глобальные переменные и c4, функции администратора для баланса контракта   | [LINK](./lessons/bonus/random/random.md) | 
| Продажа NFT | Логика продажи с помощью смарт-контрактов, "сжигание" смарт-контракта | [LINK](./lessons/bonus/17lesson/nftsale.md) |
| Взламываем простой контракт | Уязвимость за счет оптимизации компилятором кода в отсутствие impure  | [LINK](./lessons/bonus/18lesson/hack.md) | 

# Архив

[Перейти в архив](./arhive)

## Lessons in English

Lessons in English [here](https://github.com/romanovichim/TonFunClessons_Eng), if you want to speed up the translation of lessons into English, there are donation addresses below.

## Вопросы и обсуждение уроков

https://t.me/ton_learn

## Помощь по развитию

Ton:  EQAvmc9oVnOvLFlUAgeNmZNZoKeDg9vTEiAQxNFw-t5mh3m7
 
## LICENSE

CC BY-NC-ND 4.0 https://creativecommons.org/licenses/by-nc-nd/4.0/