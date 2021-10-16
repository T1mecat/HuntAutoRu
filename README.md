# HuntAutoRu

Автоматически прожимает последовательность кнопок для включения русского языка при входе в Hunt: Showdown.
Сохранение параметров еще не завезли, поэтому костыли.


# Установка
Просто скачайте HuntGFNru.exe последней версии со страницы:
https://github.com/T1mecat/GFNHuntAutoRu/releases
![browser_8h1SkKvjSI](https://user-images.githubusercontent.com/58136226/137602714-57d1a84b-8c66-492b-86d4-83c502d8ac0b.png)

# Требования для работы.
Браузер и Windows предупредят о неизвестном файле, приложение без подписи и с этим нужно смириться.
Если вы боитесь .exe файла, приложение можно собрать из AHK скрипта. Просто скачайте папку с данными скрипта и скомпилируйте штатными средствами AHK, результат будет тем же.
Приложение настроено для режима изображения 1080 x 1920, для других настроек нужны большие правки. Я готов их сделать, если кому-то будет необходимо.
Приложение думает, что GeforceNow может быть установлен только на диск C, еслис этим будут проблемы, с радостью решу в следующих версиях.

# Использование
Переместите HuntGFNru.exe в любое место на вашем компьютере, можно использовать даже из загрузок.
Иметь запущенный GeforceNow не обязательно, он откроется автоматически.
Нажмите два раза на HuntGFNru.exe и GeforceNow сам запустит Hunt: Showdown. После очереди и загрузки стима скрипт поймёт, что всё готово для него, развернет окно и начнёт нажимать последовательность клавиш.
Если что-то пойдет не так, скрипт уведомит вас, а настройки придется нажать вручную, либо закрыть окно игры и запустить скрипт еще раз.

# Перед использованием!!
Необходимо включить родительский контроль в Steam. И установить пароль на нём "0000". Можно использовать любой пароль, для этого, после первого запуска приложения пройдите по пути:
C:\Users\%UserName%\Documents\HuntGfn
И измените пароль в config.ini. Это можно сделать любым текстовым редактором.

# Как настроить родительский контроль
Перейдите в Steam > Настройки

![steam_Rx4zcfBZSL](https://user-images.githubusercontent.com/58136226/137602739-4700538e-f6a5-4a21-9168-0f62d8935ce6.png)

Семья > Управление семейным доступом

![steam_xJgGSgNNuZ](https://user-images.githubusercontent.com/58136226/137602752-19831c7d-0894-4c5a-963a-3354bdca886c.png)

Выберите такие настройки доступа:

![steam_QNw7bcM9kW](https://user-images.githubusercontent.com/58136226/137602774-43afe8a2-cad6-46fc-a5fb-e0ffcca280c0.png)

>Далее
Не выбирайте ни одной игры и нажимайте Далее.
Указываем почту, нажимаем Далее.
Вводим пин 0000

![steam_ZuqU2Dc0Z4](https://user-images.githubusercontent.com/58136226/137602816-943f40d0-2faf-4430-8511-79ce33309c85.png)
Нажимаем Далее.

Вводим код, который был выслан на почту.

![steam_DLE1gaN2F6](https://user-images.githubusercontent.com/58136226/137602845-1163c4f7-b279-42a3-8ea2-84c602ff687d.png)

И в последний раз - Далее. 
Готово, ваш аккаунт под семейным просмотром. Полностью открыть библиотеку и возможности можно нажав сюда и введя пароль.

![steam_Xt7KdYWVYL](https://user-images.githubusercontent.com/58136226/137602876-5cfd5fcf-1f2e-4fc6-a0b8-07d4f7d8ac0a.png)

