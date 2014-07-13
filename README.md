Torque 3D українською
===========

У цьому репозиторії я буду викладати матеріали по двигуну Torque 3D українською. Якщо ви розробник і ентузіаст з України, можливо вам це буде корисно. Якщо ви бажаєте допомогти перекладати чи знайшли помилки у перекладі - відпишіться. Перекладати буду не швидко, бо робота і сім’я... Але обіцяю довести справу до кінця і підтримувати переклади в актуальному стані.

Планую перевести наступні матеріали:
- [FPS Tutorial] (вже почав перекладати, приблизно закінчу до кінця серпня-вересня).
- [Guides] (12 статей, попередньо планую закінчити до нового року).
- [Documentation] (ну і саму офіційну документацію).

Також окремо напишу статтю про збірку Torque 3D під Ubuntu у всіх деталях, коли з’явиться офіційна підтримка.

Плани на майбутнє
=========

[Оригінал англійською]

> Зверніть увагу, що план розвитку у даний час обговорюється Керівним комітетом. Ця версія представляє наші загальні уявлення і наміри та може змінитись, коли ми ухвалимо кінцевий план! Коли це відбудеться, ми опишемо майбутні версії двигуна тут з запланованим функціоналом.

Короткострокові плани
----

Першочерговим завданням для нас буде очищення репозиторію (сховища джерельного коду на GitHub), налагодження нових зв'язків з суспільством, та комплекс заходів, які зроблять Комітет ефективнішим в майбутньому.

  - Завершити і запустити [даний сайт].
  - Налаштувати автоматичне тестування для полегшення обслуговування кодової бази.
  - Об’єднати (можливо, у нестабільну гілку) або відхилити всі наявні pull-requests (запити на включення). Зокрема:
  > - Використовувати CMake, як альтернативи для нинішнього Project Generator (Генератора проектів)
  > - 64-розрядна версія двигуна
  > - Сумісність з Visual Studio 2013

Середньострокові плани
----

  - Реалізувати підтримку Linux та OSX через OpenGL рендеринг.
  - Реалізувати підтримку DirectX 11 та PhysX 3.3.
  - Додати нові модульні шаблони сценаріїв (скрипти) і розподіл контенту.
  - Об’єднати з більш складними pull-requests, зокрема поліпшення у мові TorqueScript.

Довгострокові плани
----

  - Очистити вихідний код двигуна (наприклад, STL контейнерів, тощо).
  - Реалізувати модульний скриптовий двинун, який дасть можливість використовувати інші мови сценаріїв (Lua, C#, тощо).
  - Позбавитись від хардкоду (костилів) у деяких класах.
  - Покращити стандартні редактори (World Editor, Datablock Editor, Shape Editor та Material Editor).

[Оригінал англійською]:http://torque3d.org/engine/#roadmap
[FPS Tutorial]:http://www.garagegames.com/products/torque-3d/fps
[Guides]:http://www.garagegames.com/products/torque-3d/guides
[Documentation]:http://www.garagegames.com/products/torque-3d/documentation
[даний сайт]:http://torque3d.org/
