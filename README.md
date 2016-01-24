# TelegramBot
Telegram API in PHP
Create a New Bot

    Add @BotFather to start conversation.
    Type /newbot and @BotFather will ask the name for your bot.
    Choose a cool name, for example The Nice Bot and hit enter.
    Now choose a username for your bot. It must end in bot, for example NiceBot or Nice_Bot.
    If succeed, @BotFather will give you API key to be used in this library.

Telegram Bot API

Telegram Bot API - Introduction to Bots.
Example usage Class TelegramBot

require('TelegramBot.php');

$TokenAPI = 'Your Api Key Here';
$BotNow = new TelegramBot($TokenAPI);

// Send message to user.
$ChatId = "26038459"; // id Chat
$TextMsg = "Hello world";
$BotNow ->SendMessage($ChatId,$TextMsg); // Success!

ClassTelegram.php Function List

    Request()
    RequestFile()
    GetUpdates()
    SetWebhook()
    getMe()
    SendMessage()
    ForwardMessage()
    SendPhoto()
    SendAudio()
    SendDocument()
    SendSticker()
    SendVideo()
    SendVoice()
    SendLocation()
    SendChatAction()
    GetUserPhotos()
    GetFile()
