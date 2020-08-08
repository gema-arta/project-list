### project-list
 Projects Lists

Full function recovery (ngrp) for android -- net, usb-net, adb, syslog(remotelog, displaybootlog, logcat), backup-recovery helpers, compressors, installers, parted (partitionery), selinux managment, containters (nspawn, chroot), remote and display control, ndk and other libc wrapper \ integations other low level managment

Разработка "полнофункционального" recovery образа для андроид
1. Полноценная поддержка сети (локальной и глобальной) -- как классичесской wireless включая открытую и WPA режимы, внутренний baseband модем, так и расширенной в виде P2P wifi, PAN и прочего доступного в middleware устройства - cli \ gui инструменты для удобного управления
2. Поддержка USB RNDIS в режиме recovery - cli \ gui инструменты для удобного управления
3. Поддержка adb режиме recovery
4. Инструментарий для консолидации kernel и system журналов -- иструменты для локального, загрузочного (bootscreen) и удалённого сбора и просмотра журналов
5. Инструментарий для создания и восстановления резервных копий в режиме recovery и передачи \ приёма их вне устройства -- в первую очередь речь о dd \ nandroid и tar mode, но другие варианты дробного резервирования в особенности для Android 10+ актуальны, так встроенный интрументарий проверки целостности \ сжатия \ дедупликации
6. Инструментарий для установки различных компонентов из recovery mode
7. Управление таблицами разделов и файловыми системами, cli + gui
8. Расширеный инструментарий для работы с selinux метками, cli
9. Инструментарий установки для запуска изолиролванных nix окружений различеыми методами
10. Компоненты для удалённного управления recovery (telnet, ssh, scrcpy, vnc) и удобной передачи данных (nbd, sshfs, rsyncd) и тому подобное
11. Инструмент для быстрого \ автоматического исправления ошибок линковки libc и прочих библиотек при работе в recovery mode


Magisk NG (magiskng) -- advanced hide binary methods (LD_PRELOAD,fuse,overlayfs,PATHS,file offsets), hiders perset, impruve stability methods, control bootloops, helpers for project trerble

Consolidate needed projects for droid -- islands (multiple?) and other sandbox methods, isolated storage, firewall (traffic control systems), vendors firmware control sets, freezers, apps opts controls, devendowercation \ googlefication, gaps, full function gaps replacement (push etc), wakelock detectors \ controls, ads find and destroy
