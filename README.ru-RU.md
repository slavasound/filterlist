<!--
This file is part of the Press the Attack project,
Copyright (c) 2018 Bogachenko Vyacheslav

Press the Attack is a free project: you can distribute it and/or modify
it in accordance with the MIT license published by the Massachusetts Institute of Technology.

The Press the Attack project is distributed in the hope that it will be useful,
and is provided "AS IS", WITHOUT ANY WARRANTY, EXPRESSLY EXPRESSED OR IMPLIED.
WE ARE NOT RESPONSIBLE FOR ANY DAMAGES DUE TO THE USE OF THIS PROJECT OR ITS PARTS.
For more information, see the MIT license.

Author: Bogachenko Vyacheslav <https://github.com/bogachenko>
Email: bogachenkove@gmail.com
Github: https://github.com/bogachenko/presstheattack/
Last modified: 24 November 2018
License: MIT <https://github.com/bogachenko/presstheattack/blob/master/LICENSE.md>
Problem reports: https://github.com/bogachenko/presstheattack/issues
Title: README.ru-RU.md
URL: https://raw.githubusercontent.com/bogachenko/presstheattack/master/README.ru-RU.md
Wiki: https://github.com/bogachenko/presstheattack/wiki

Download the entire Press the Attack project at https://github.com/bogachenko/presstheattack/archive/master.zip -->

# Press the Attack
[![site](https://img.shields.io/badge/site-up-%233fb912.svg)](https://bogachenko.github.io/presstheattack/)
[![wiki](https://img.shields.io/badge/wiki-up-%233fb912.svg)](https://github.com/bogachenko/presstheattack/wiki)
[![license](https://img.shields.io/badge/license-MIT-%233fb912.svg)](https://raw.githubusercontent.com/bogachenko/presstheattack/master/LICENSE.md)

Пользовательские фильтры блокирующие популярные трекеры, баннеры, загрузку и отображение рекламы на страницах сайтов и результатов поиска, а также включают косметические фильтры для проблемных сайтов.

Этот проект является оригинальным, он находится под лицензией MIT (смотреть [Лицензию](https://raw.githubusercontent.com/bogachenko/presstheattack/master/LICENSE.md)) и создал его [Богаченко Вячеслав](https://github.com/bogachenko)

Общая цель проекта - блокировать рекламу и уменьшать трафик, поступающий с доменов / веб-сайтов, которые вы посещаете.
Термин "реклама" в этом проекте не определен, потому что, как я уже сказал выше, помимо очевидных объявлений, я также блокирую косметические баннеры и всплывающие подсказки, которые, как я думаю, создают бесполезный трафик без какой-либо реальной выгоды.

Мой список не ограничен ни одним регионом. Тем не менее, мое личное внимание - это английские и русские регионы, так как я говорю на этих языках.

## Отречение

Вы можете обнаружить, что эти правила чрезмерно усердны, я обращаю особое внимание на регистрацию, шпионаж на пользователей, разработку и отслеживание.
Если вы обнаружите, что одно или несколько правил ломают сайт, определите правило проблемы и используйте комментарии, чтобы отключить его через настройки плагина и/или создать вопрос в «проблемах».

Я не несу ответственности за любые убытки, которые могут возникнуть в результате использования этих правил, включая контент, по ошибке скрытый или нарушенный одним из правил в этом наборе.

Обратите внимание, что в основном я использую uBlock Origin. Я сделаю все возможное, чтобы поддерживать совместимость с AdBlock Plus, но я не могу регулярно тестировать свой фильтр с помощью этого плагина. (Если у вас возникли проблемы с использованием AdBlock Plus, не стесняйтесь поднимать проблему.)

## Поддерживаемые блокировщики рекламы

Чтобы использовать эти правила, вам понадобится совместимый браузер.

* [uBlock **Origin**](https://github.com/gorhill/uBlock) (не [uBlock](https://www.ublock.org) <sup><small>[почему?](https://github.com/bogachenko/presstheattack/wiki/uBlock-Origin-vs-uBlock)</small></sup>)
	* [Firefox](https://addons.mozilla.org/addon/ublock-origin/)
	* [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
	* [Opera](https://addons.opera.com/en/extensions/details/ublock/)

Каждые браузеры и плагины немного отличаются друг от друга, плагин, представленный выше, с моим фильтром списка работает правильно (проверено лично), плагины, представленные ниже, не были проверены мной лично, и поэтому я признаю, что может работать некорректно.

* [AdBlock Plus](https://adblockplus.org/)
	* [Firefox](https://addons.mozilla.org/en/firefox/addon/adblock-plus/)
	* [Chrome](https://chrome.google.com/webstore/detail/cfhdojbkjhnklbpkdaibdccddilifddb)
	* [Opera](https://addons.opera.com/en/extensions/details/adblock-plus/)

* [Adblock](https://getadblock.com/)
	* [Firefox](https://addons.mozilla.org/en/firefox/addon/adblock-for-firefox)
	* [Chrome](https://chrome.google.com/webstore/detail/adblock/gighmmpiobklfepjocnamgkkbiglidom)
	* [Opera](https://addons.opera.com/en/extensions/details/adblock/)

* [Opera](https://opera.com)
    * [Opera Ad blocker](https://addons.opera.com/en/extensions/details/opera-ad-blocker/)
	
* [Adguard](https://adguard.com)
    * [Firefox](https://addons.mozilla.org/en/firefox/addon/adguard-adblocker/)
	* [Chrome](https://chrome.google.com/webstore/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg/)
	* [Opera](https://addons.opera.com/en/extensions/details/adguard/)
  
и все другие подобные плагины ...

## Использование

[ПОДПИСАТЬСЯ](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fraw.githubusercontent.com%2Fbogachenko%2Fpresstheattack%2Fmaster%2Fpresstheattack.txt&title=Press%20the%20Attack) - Нажмите ссылку, чтобы добавить список фильтров через браузер или добавить его вручную:

`https://raw.githubusercontent.com/bogachenko/presstheattack/master/presstheattack.txt`

## Документация

Более подробное описание проекта и документация см. в разделе [ВИКИ](https://github.com/bogachenko/presstheattack/wiki).

## Вклад

Я принимаю любые запросы на дополнительные правила. Перейдите на вкладку "Проблемы", откройте вопрос и сообщите о проблеме или пожелании, но не умножайте одни и те же вопросы, проблемы со списком решаются только здесь.
Любители пообщаться и/или использовать поток для собственного развлечения будут удалены, и регулярный рецидив будет запрещен.
Не забивайте его, молодые люди, он не создан для этой цели.