# doory

Код помогает генерировать простые редиректы с wildcard поддоменов.

Копируем какую-то страничку html любую, создаем в корне вашего хостинга файл index.html, вставляем туда код этой странички скопированной. 
Дальше, содержимое index.html из этого репозитория, точнее то, что там внутри <head> секции, помещаем внутрь head секции скопированного файла.

На хостинге нужно настроить wildcard поддомены, погуглите, как это сделать на вашем.

После этих манипуляций, должно все работать так: вы в корне сайта создаете какую-то папку, например test, помещаете туда внутрь файл index.html, внутри этого файла одна строчка - url, по которому нужно переходить. Дальше получается магия, папка test становится поддоменом вашего домена, который подключен к хостингу, и ссылка вида http://test.yourdomain.ru редиректит с задержкой рандомной от 3 до 5 секунд на тот url, который вы прописали в index.html файле подпапки.
  
Сейчас хорошее предложение есть у https://jino.ru/ там домен ru за 39 р. правда один, можно купить, но кто запрещает сделать много аккаунтов ) Хостинг нужен для этого самый простой без php даже, у них там такой 50+ рублей в месяц стоит, так что пользуйтесь. Дал бы рефералку, но на самом деле хостинг такое гавно, что даже рефералки у них нет )) Зато wildcard поддомен сразу подключен, ничего не нужно мудрить...

Если что, пишите в личку тут, может что-то подронее объясню: https://tarassenko.ru/wa.php?phone=79138665569
