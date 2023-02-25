
Definicja płytki do kominikacji w ROV1 dla Zephyr RTOS
###########

Overview
********

Pliki wymagane do kompilowania i wgrywania Zephyra dla płytki do komunikacji opartej na stm32f407zet6.


Building And Running
********************

Repo sklonować do katalogu:

 ~/zephyrproject/zephyr/boards/arm

 Kompilacja:

 west build -b seamore_f407zet6 <ścieżka do projektu>

 Wgrywanie:

 Wymaany jest programator ST-lnik w dowolnej wersji wpięty w płytkę. I używamy komendy:

 west flash

 Debugowanie:

 Użyć jakiegoś termonala UART np CH340 i wpiąć się w piny na płytce. Baudrate 115200.