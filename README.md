Телеграм бот

Это программа для создания квиза в Telegram.

В основном файле <вопросики_телеграм-бот.py>, в строке API_TOKEN = 'YOUR_BOT_TOKEN'. Заменить 'YOUR_BOT_TOKEN' на свой токен, Telegram-бота.

Файл <quiz_data.json>, содержит словари с вопросами, вложенными в список. Каждый словарь имеет 3 ключа:

		question - вопрос
  
  		options - варианты ответов
    
    	correct_option - индекс правильного ответа

Функционал бота:

		-Запуск прохождения квиза по кнопке;

		-При не правильном ответе, пишет какой был правильный;

		-Вывод кол-ва правильных ответов после квиза.

Команды бота:

		/start - Запускает создание кнопки "Начать игру" и присылает сообщение с текстом "Добро пожаловать в квиз"

		/help - Присылает сообщение: "Команды бота: /start - начать взаимодействие с ботом /help - открыть помощь /quiz - начать игру"

		/quiz, Начать игру - Запускает квиз с самого начала и обнуляет прошлый результат.

Ссылка на бот: https://t.me/Voprosiki99_bot
