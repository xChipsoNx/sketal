## Machine-Learning Chatter

#### Инструкция для получения токена
1. В первую очередь, идём и регистрируемся на Dialogflow и попадаем в панель управления.

2. Жмём на кнопку Create agent и заполняем поля по усмотрению (это никакой роли не сыграет, это нужно лишь для следующего действия). Жмём на Create.

3. Расскажу, почему созданный нами ранее «Агент» никакой роли не играет. Во вкладке Intents есть «команды», по которым работает бот. Сейчас он умеет лишь отвечать на фразы типа «Привет», и если не понимает, то отвечает «Я вас не понял».
После создания нашего пустого агента, у нас появилась куча других вкладок. Нам нужно нажать на Prebuilt Agents (это уже специально обученные агенты, которые имеют множество команд) и из всего представленного списка выбрать Small Talk.

4. Наводим на него и жмём Import. Далее ничего не меняя, жмём Ok. Агент импортировался и теперь мы можем его настроить. Для этого в левом верхнем углу жмём на шестерёнку возле Small-Talk и попадаем на страницу настроек. Теперь мы можем изменить имя агента, как захотим. Меняем часовой пояс и во вкладке Languages проверяем,чтобы был установлен русский язык.

5. Возвращаемся на вкладку General, спускаемся немного вниз и копируем Client access token.

6. Вставляем в нужное поле. Теперь наш ИИ полностью настроен.

7. Осталось лишь теперь его учить и учить. Делать это можно во вкладке Training. Там можно посмотреть все сообщения, которые писались и что на них ответил бот. Там же его можно и обучать, говоря боту где он ответил правильно, а где нет.