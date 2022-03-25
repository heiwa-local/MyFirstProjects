# Жизненный цикл Activity
IT Школа и IT Академия Samsung

Практическая работа 2.2

## Задание:

  Создать приложение для платформы Android с функциями отслеживания состояний активности.
  
## Функционал:

    1. При запуске приложения на экране отображается активность с заголовком «Контролёр состояний» без кавычек и по очереди высвечиваются Toast о срабатывании методов onCreate() -> onStart() -> onResume().
    2. При сворачивании приложения отображаются сообщения о работе методов onPause() -> onStop().
    3. При возобновлении работы приложения отображаются сообщения о выполнении методов onRestart() -> onStart() -> onResume().
    4. При повороте экрана выполняется последовательность Toast о работе методов onPause() -> onStop() -> onDestroy() -> onCreate() -> onStart() -> onResume().
    5. При закрытии приложения отображаются сообщения о методах onPause() -> onStop() -> onDestroy().
