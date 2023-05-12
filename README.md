import telebot

# Создание экземпляра бота
bot = telebot.TeleBot(AAHTy4Mg2025WRkTpYPc
OZK6gI9Pqqucy8)

# Обработчик команды /start
@bot.message_handler(commands=['start'])
def send_welcome(message):
    bot.reply_to(message, 'Привет! Я телеграмм бот. Как я могу тебе помочь?')

# Запуск бота
bot.polling()
