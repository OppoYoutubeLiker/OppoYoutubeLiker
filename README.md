<div align="center">
    <img height="150" src="https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/logo_small.png"></img>
    <h1>Simple YouTube Age Restriction Bypass</h1>

<h3>Это скрипт, который автоматически ставит лайк всем оппозиционным видео, которые вы смотрите на Youtube.</h3>
</div>

## Установка


- Установите в браузер дополнение для менеджера скриптов. Мы рекомендуем дополнение Tampermonkey, поскольку скрипт был написан в нем.

<div align="center">
  
   | [![Chrome](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/chrome.png)](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)  | [![Firefox](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/firefox.png)](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/) | [![Opera](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/opera.png)](https://addons.opera.com/en/extensions/details/tampermonkey-beta/) | [![Safari](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/safari.png)](https://apps.apple.com/us/app/userscripts/id1463298887)  | [![Edge](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/edge.png)](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)  |
   | ------------- | ------------- | ------------- | ------------- | ------------- |
   | [Видеоинструкция](https://www.youtube.com/watch?v=cu4XeYtqXbM)  | [Видеоинструкция](https://www.youtube.com/watch?v=J9cbNOO2rew)  | [Видеоинструкция](https://www.youtube.com/watch?v=V090xyUf8dU)  | [Видеоинструкция](https://www.youtube.com/watch?v=iTyLQRVtMCA)  | [Видеоинструкция](https://www.youtube.com/watch?v=Bcs4HhQXCaU)  |
    
  <h5>Альтернативные менеджеры скриптов: Violentmonkey или Greasemonkey</h5>

</div>
    
- Нажмите на [ссылку](https://www.youtube.com/watch?v=cu4XeYtqXbM) и установите скрипт.

## Как это работает
Как только пользователь попадает на страницу YouTube, скрипт каждые 10 секунд (опционально) проверяет, просматривается ли видео с оппозиционного канала и был ли уже поставлен лайк. Если это оппозиционный канал и нет лайка, скрипт сам ставит его.

 - Все оппозиционные каналы хранятся в скрипте в виде массива. Проще говоря, они заключаются в квадратные скобки и перевернутые запятые.

Пример: ["Алексей Навальный", "Навальный LIVE", "Популярная политика", ... ]

Поэтому каждый может добавлять свои каналы или удалять существующие.

 - Статус кнопки лайк считывается с маркера YouTube. Если лайк не установлен, веб-страница с видео содержит маркер "flase", в противном случае - "true".

API Youtube не требуется!
## Лицензия
Проект полностью с открытым исходным кодом. Наша собственная лицензия запрещает автократическим, диктаторским или ненавидящим демократию лицам использовать этот скрипт.

<div align="center">
  
[![GPLv3 License](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/GPLv3.png)](https://opensource.org/licenses/)   [![OWN License](https://raw.githubusercontent.com/OppoYoutubeLiker/OppoYoutubeLiker/main/Images/OWN.png)]()
  
</div>


## Конфиденциальность
Этот скрипт уважает вашу конфиденциальность и не собирает никакой информации.
