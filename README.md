# Telegramcommentpars
Этот небольшой проект поможет вам собрать все комментарии под определенным постом с публичной странцы в telegram.

Для начала вам необходимо получить api_id и api_hash так как парсер работает на api telegram. Это можно сделать через https://my.telegram.org/ . Введите свой номер телефона, подтвердите с помощью отправленного кода и перейдите на страницу инструментов разработки API . Там создайте приложение и скопируйте API ID и API HASH.
Для работы скрипта необходимо две библиотеки:
1) Telethon которая устанавливается командой pip install telethon
2) CSV которая устанавливается командой pip install python-csv 

Далее необходимо указать свой никнейм в telegram в поле "name" и название канала в поле "chat", также необходимо указать id поста в параметре reply_to (узнать id поста можно скопировав ссылку на пост и последнее цифровое значение будет id)

После запуска скрипта в папке проекта будет сформирован csv файл под названием final с которым можно продолжить работу.

This small project will help you collect all the comments under a certain post from a public page in telegram.

First you need to get api_id and api_hash since the parser works on api telegram. This can be done via https://my.telegram.org/ . Enter your phone number, verify with the submitted code, and go to the API Development Tools page. There, create an app and copy the API ID and API HASH.
The script requires two libraries:
1) Telethon which is installed by pip install telethon
2) CSV which is installed by pip install python-csv

Next, you need to specify your nickname in telegram in the "name" field and the name of the channel in the "chat" field, you must also specify the post id in the reply_to parameter (you can find out the post id by copying the link to the post and the last digital value will be id)

After running the script, a csv file called final will be generated in the project folder with which you can continue working.
