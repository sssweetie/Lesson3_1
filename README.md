# Lesson3_1

Это коммит из первого репозитория.

Он будет отображен в удалённом репозитории.

Сделали fork другого репозитория.

## Работа с удаленным репозиторием GitHub

Например, у нас есть репозиторий одного человека и репозиторий другого человека. Мы хотим все передать третьему, для этого мы можем воспользоваться удаленным репозиторием GitHub.

1. Создадим папку на нашем рабочем столе, назовем ее seminar3 и откроем в редакторе VS Code. В этот раз мы не будем создавать свой репозиторий, а возьмем готовый на сайте github.com, где заранее пройдем регистрацию. При создании репозитория, желательно поставить галочку возле создания readme файла, это создаст репозиторий в нашей папке автоматически.
2. В нашем созданном удаленном репозитории нажимаем кнопке Code и копируем его, для того чтобы создать клон нашего удаленного репозитория в локальном.
3. В VS Code прописываем команду git clone и адрес, который скопировали. После этого git скопирует репозиторий, находящийся на сервисе GitHub, в наш локальный репозиторий. То есть на нашем компьютере появится полная копия этого репозитория.
4. Отправить внесенные изменения в локальном репозитории на удаленный репозиторий можно через команду git push.

### Синхронизация между репозитроиями

Провести изменения файла в удаленном репозитории. Командой git pull выкачать все из удаленного в локальный репозиторий.

### Создание кнопки pull request

1. Делаем fork интересующего нас чужого удаленного репозитория.

2. Делаем git clone для нашей версии этого репозитория. *Так появится версия на нашем аккаунте, и именно эту версию мы и клонируем*.

3. Создаем ветку с предлагаемыми изменениями. Производим изменения только в этой ветке.

4. Отправляем все изменения на свой аккаунт командой push.

5. В окне на удаленном репозитории GitHub появляется возможность отправить pul request.