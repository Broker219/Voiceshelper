		                                      Голосовой ассистент “Oxy(Окси)”
    
  В директории программы необходимо запустить код в файле “main.py” (данный файл является главенствующим). После чего, программа начинает с нами говорить. При запуске 
программы, женский голос приветствует пользователя NONAME. Далее идет ожидание команды. Первое запрос не работает, в терминале напишет: ('Голос не распознан!')
После этого снова микрофон будет активен. Просто, отвечайте/ выбирайте/ произнесите необходимую команду из списка ниже, в связке с именем (“name()”) программы. 
Для лучшего восприятия команд, советуется применять вопросительные слова.

  Команды:
  Поприветствовать;
  Сколько время;
  Какая дата;
  Включить музыку;
  Спросить погоду; 
  Анекдот;
  Определение слова на сервисе ‘Википедия’;
  Включить видео, произноси название видео;
  Помощь с загадыванием случайного числа.
	
Вопросительные слова находятся в блоке option = {‘tellbar’}:
    'tellbar': ('скажи', 'расскажи', 'подскажи', 'сколько', 'какая', 'какой', 'какие', 'который', 'сейчас', 'включи', 
    'воспроизведи', 'найди', 'открой', 'покажи', 'поиграем',)

Так же добавлены искажения в произношении команд и различные вариации слов и словосочетаний схожих по смыслу 
с оригинальным запросом действий, попробуй поиграть. Например, скажи: «Я проснулся», «Мне скучно» или «Как-то здесь тихо».
	
Команды выключения музыки НЕТ. Необходимо выключать ее вручную

Как стало понятно по “шапке” описания – ассистент откликается на имя “Окси”, возможны различные проблемы как 
с оборудованием пользователя, так и с произношением имени, поэтому в отклик программы добавлены различные 
искажения данного имени:
    'name': ('окси', 'oxy', 'oksi', 'okci', 'окс', 'охи', 'фокси')


