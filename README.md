# goit-markup-hw-06

Bl-Group-2, Sulihan Kyrylo

1. Формі підписки у футері заданий пустий placeholder=' ' та абсолютно позиціонований label, що
   змінює положення при набиранні тексту. Також по фокусу в інпут форми змінюється колір його
   бордеру. Всім властивостям, що змінюються, задано css-перехід.

2. У скрипті модального вікна виявлена помилка - модальна форма закривалась по кліку в будь-яке
   місце бекдропу, навіть у саму модальну форму. Вирішити проблему наразі не вдалося, натомість
   додана можливість закривати модальне вікно клавішою Escape.

3. Такощ дещо доповнено css-правило, що відповідає за заборону скролу на сторінці з відкритою
   модальною формою - тепер при зникненні скролбару елементи сторінки не зміщуються.

4. Міткам модального вікна задана заборона виділення для запобігання випадкових виділень при фокусі
   поля по кліку на мітку.

5. Чекбокс у модальній формі приховано класом visually-hidden а також властивістю appearance: none;.
   Обидва варіанти спрацьовують, як треба, тому обидва наразі присутні в коді.

6. Всім полям форм, окрім поля коментарів, задано атрибут required для валідації внесених даних.