# abronya

Всем привет!

Чтобы склонировать этот репозиторий, 
1) зайдите в него через gitHub и нажмите в левом верхнем углу кнопку Fork. Репозиторий склонируется в ваш gitHub аккаунт.
2) создайте папку на вашем компе и сделайте в ней клон репозитория след командой: 
git clone git@github.com:your_username/abronya.git
3) Склонированный репозиторий будет иметь привязку к удалённому репозиторию в вашем аккаунте, а не в моем(общем). Эта привязка называется origin
4) Чтобы отслеживать изменения еще и в моем аккаунте(туда мы будем сливать все наши изменения), надо сделать привязку и к нему.
Для этого перейдите в папку с репозиторием на вашем компе, открой гит и введи команду:
git remote add upstream git://github.com/abronytska/abronya.git
git fetch upstream

Теперь можно работать - создавать файлы, менять файлы и тд.
1) Добавляем все ваши изменения для коммита, коммитим и пушаем их в свой репозиторий:
git add -A
git commit -m "комментируем, желательно на англ и норм комментами"
git push origin
2) Чтоб залить ваши изменения в общий(мой) репозиторий надо уже через гитхаб сделать pull request
(зайти в вашем аккаунте в этот репозиторий и нажать кнопку pull request и там выбрать общий репозиторий).
3) Далее вы попадёте на предпросмотровую страницу, на которой сможете ввести название и описание ваших изменений.

Другие члены команды тоже делают пул риквесты и вам надо видеть их изменения. Для этого мы создали upstream привязку.
Для того чтоб подтянуть в ваш репозиторий чужие изменения:
git pull upstream master

Всем продуктивной работы!
Have fun!!
