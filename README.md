# FreeRTOS - for esp-open-rtos

This is a fork of https://sourceforge.net/projects/freertos/ with support
added for esp-open-rtos.

The default branch is esp-open-rtos, which has the current code for
esp-open-rtos.

The master branch is select and periodic merges of the upstream code
from the FreeRTOS SVN repo and with line endings converted to unix
style. Modifications are to be kept in separate branches to make
rebasing easier and so that the changes can be easily seen.

The initial commit is version 7.5.2 which appears to be the base
version for the ESP8266 SDK port. Some select SDK versions are
maintained in the esp8266-rtos-sdk branch, and are based on the code
released at https://github.com/espressif/ESP8266_RTOS_SDK and again
with line endings converted to unix style and some re-organisation of
the files.
