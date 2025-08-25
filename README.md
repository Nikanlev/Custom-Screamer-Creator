# Custom-Screamer-Creator

To download, go to Releases - https://github.com/Nikanlev/Custom-Screamer-Creator/releases

Create your own screamer easily and simply

-=EN=-
1. Controls:
Movement - WASD
Movement (Alternative) - Arrow keys
LShift - Double movement speed

2. Character:
Replace the image `Your_character_image.png` with your own character image. The image must be named `Your_character_image` and be in .png format (to convert the image format, I recommend the website https://convertio.co/en/).

Regardless of its size, the character will always be positioned in the top left corner of the application.

3. Box that triggers a screamer upon contact:
Replace the image `Your_box_image.png` with your own image. The image must be named `Your_box_image` and be in .png format (to convert the image format, I recommend the website https://convertio.co/en/).

Regardless of its size, the box will always be positioned in the bottom right corner of the application.

4. Image that will be shown upon contact with the box(3):
Replace the image `Your_screamer_image.jpg` with your own screamer image. The image must be named `Your_screamer_image` and be in .jpg format (to convert the image format, I recommend the website https://convertio.co/en/).

The top left corner of the screamer image, regardless of its size, will be located in the top left corner of the application (if you want a full-screen screamer, change its size in pixels to 800x600).

5. Sound that will play once upon contact with the box(3):
Replace the sound `Your_screamer_sound.mp3` with your own sound. The sound file must be named `Your_screamer_sound` and be in .mp3 format (to convert the sound format, I recommend the website https://convertio.co/en/).

The sound can be of any length and size; it will play only once.

6. Background sound (stops when the box(3) is touched):
   Replace the sound Your_background_music.mp3 with your own sound. The sound must be named Your_background_music and be in .mp3 format (to change the sound format, I recommend the website https://convertio.co/en/).

   The sound can be of any length and size; it will play on a loop until we touch the box(3).

-=SETTINGS SECTION=-
1.  Background color: Write the background color in English in the bg_color.txt file.
    Examples - white | light gray

2.  Background music On/Off: In the bg_music_onoff.txt file, write 0 - to turn off the background music, 1 - to turn on the background music.

3.  Background music offset: In the music_offset.txt file, write a number indicating how many seconds to cut from the beginning of the music. Write 0 - to cut nothing (decimal fractions do not work).

4.  Normal walking speed: In the normal_speed.txt file, write a number indicating the normal movement speed in pixels (1 = 60 pixels per second, 2 = 120 pixels per second).

5.  Sprint speed: In the sprint_speed.txt file, write a number indicating the sprint speed (on LShift) in pixels (1 = 60 pixels per second, 2 = 120 pixels per second).

6.  Window height: In the resolution_HEIGHT.txt file, write a number indicating the height of the application window in pixels.

7.  Window width: In the resolution_WIDTH.txt file, write a number indicating the width of the application window in pixels.

8.  Simplified image resolution: In the simplified_resolution.txt file, write 0 or 1. 0 - disable simplified image resolution (in the application, images will be the same size as your original image. P.S. There might be errors due to images being too large, as objects will collide with each other). 1 - enable simplified image resolution (in the application, the box(3) and character(2) images will be 65 by 65 pixels, and the screamer screen will be stretched to full screen. P.S. This will prevent errors for inexperienced users).

9.  Application name: In the app_name.txt file, write the name that your application will have when opened and in the task manager.





-=RU=-
1. Управление:
Движение - WASD
Движение (Альтернативное) - стрелочки на клавиатуре
LShift - ускорить ходьбу в 2 раза

2. Персонаж:
Замените картинку Your_character_image.png на свою картинку персонажа. Название картинки должно быть Your_character_image, а формат .png (чтобы поменять формат изображения, советую сайт https://convertio.co/ru/)

Персонаж в независимости от его размера всегда будет стоять в левом верхнем углу приложения

3. Коробка, которую если коснуться, активируется скример:
Замените картинку Your_box_image.png на свою картинку. Название картинки должно быть Your_box_image, а формат .png (чтобы поменять формат изображения, советую сайт https://convertio.co/ru/)

Коробка в независимости от её размера всегда будет стоять в правом нижнем углу приложения

4. Изображение которое будет показываться при прикосновении к коробке(3):
Замените картинку Your_screamer_image.jpg на свою картинку скримера. Название картинки должно быть Your_screamer_image, а формат .jpg (чтобы поменять формат изображения, советую сайт https://convertio.co/ru/)

Левый верхний угол скримера в независимости от его размера, будет находиться в левом верхнем углу приложения (если хотите скример на весь экран, измените его размер в пикселях на 800x600)

5. Звук который будет проигрываться 1 раз пот прикосновении к коробке(3):
Замените звук Your_screamer_sound.mp3 на свой звук. Название звука должно быть Your_screamer_sound, а формат .mp3 (чтобы поменять формат звука, советую сайт https://convertio.co/ru/)

Звук может быть любой длины и размера, он проигрывается только 1 раз

6. Звук на фоне (останавливается при прикосновении к коробке(3):
Замените звук Your_background_music.mp3 на свой звук. Название звука должно быть Your_background_music, а формат .mp3 (чтобы поменять формат звука, советую сайт https://convertio.co/ru/)

Звук может быть любой длины и размера, он проигрывается на повторе, пока мы не коснёмся коробки(3)

-=РАЗДЕЛ С НАСТРОЙКАМИ=-
1. Цвет фона: напишите цвет фона на английском в файле bg_color.txt,
Примеры - white | light_gray

2. Включение/Выключение фоновой музыке: в файле bg_music_onoff.txt напишите 0 - чтобы выключить фоновую музыку, 1 - чтобы включить фоновую музыку

3. Оффсет фоновой музыки: в файле music_offset.txt напишите в виде числа то, сколько секунд нужно обрезать от начала музыки, напишите 0 - чтобы не обрезать ничего (десятичные дроби не работают)

4. Скорость обычной ходьбы: в файле normal_speed.txt напишите в виде чила то, какая будет обычная скорость передвижения в пикселях (1 = 60 пикселей в секунду, 2 = 120 пикселей в секунду)

5. Скорость бега: в файле sprint_speed.txt напишите в виде числа то, какая будет скорость бега (на LShift) в пикселях (1 = 60 пикселей в секунду, 2 = 120 пикселей в секунду)

6. Размер окна в высоту: в файле resolution_HEIGHT.txt напишите в виде числа то, какой размер в пикселях будет окно приложения в высоту

7. Размер окна в ширину: в файле resolution_WIDTH.txt напишите в виде числа то, какой размер в пикселях будет окно приложения в ширину

8. Упрощённый размер изображений: в файле simplified_resolution.txt напишите 0 или 1, 0 - выключить упрощённый размер изображения (в приложении картинки будут такого же размера, что и ваши исходные P.S могут быть ошибки из-за слишком большого размера изображения, так как объекты будут соприкасаться друг с другом), 1 - включить упрощённый размер изображения (в приложении картинки коробки(3) и персонажа(2) будут размера 65 на 65 пикселей, а экран скримера будет растянут на весь экран P.S это предотвратит ошибки неопытных пользователей)

9. Название приложение: в файле app_name.txt напишите то, какое название будет у вашего приложения при его открытии и в диспетчере задач
