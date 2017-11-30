AllWinner a33 X5en_MIPIjdf

TWRP touch recovery
-------------

TWRP recovery - device: http://4pda.ru/forum/index.php?showtopic=691682&view=findpost&p=56449768


Flash CWM or TWRP
---------

Run following commands

adb push recovery.img /sdcard/

adb shell "cat /sdcard/recovery.img > /dev/block/mmcblk0p10; sync"
