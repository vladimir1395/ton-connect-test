# ton-connect-test
 Для внедрения данного подхода авторизации пользователя через Ton необходимо установка соединения на fronted.
 
Для работы с тон существуют следующие библиотеки:

                -- @tonconnect/sdk
                
                -- @tonconnect/ui
                
                -- @tonconnect/ui-react      
                
Для проверки авторизации через Ton Connect на backend есть готовая библиотека на Golang: 
   
                --https://github.com/tonkeeper/tongo

К сожалению реализации на java не существует.

## Демонстрация входа через TON-CONNECT 2.0

1.Установка на телефон приложения Tonkeeper

2.Локально запущен проект на фронтенд части (изменен и настроен под локальный запуск) пример взят по ссылке:

                 https://github.com/ton-connect/video-course/tree/master/5_ton-connect-ui-react

3.Локально запущен проект бэкенд части(изменен и настроен под локальный запуск) пример взят по ссылке:

                 https://github.com/ton-connect/demo-dapp-backend

4.Проблема использования ton-connect-manifest.json в локальной среде(приложение не развернуто на сервере) была решена переносом в GitHubGist

                 https://gist.github.com/vladimir1395/b63bdfea3bd92c0278e72b14ab1b248d

5.Для наглядной демонстрации при успешном входе на мобилке при нажатии на иконку будет просто открыта данная страничка моего публичного репозитория на github.

!!!! Для внедрения данного подход авторизации нужен еще один промежуточный сервис на java который будет соответствовать нашей инфаструктуре.

Полезные ссылки:

https://docs.ton.org/develop/dapps/ton-connect/sign

https://docs.ton.org/develop/dapps/ton-connect/manifest

https://www.youtube.com/watch?v=wIMbkJHv0Fs&list=PLyDBPwv9EPsCJ226xS5_dKmXXxWx1CKz_&index=5

https://github.com/ton-community/awesome-ton#-education

https://ton.org/community



