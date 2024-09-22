# Camera_Net
Src codes and files of Camera_Net (Flexscan3D supported)  <br>
<b/>Camera_Net-1.1.1.zip</b> - оригинальный исходный код библиотеки Camera_Net версии 1.1.1 (https://github.com/free5lot/Camera_Net) <br>
<b/>Camera_Net-1.1.2.zip</b> - оригинальный исходный код библиотеки Camera_Net версии 1.1.2 (https://github.com/free5lot/Camera_Net)<br>
<b/>Camera_Net-1.1.1-maxres.zip</b> - исходный код скорректированной библиотеки Camera_Net. (https://github.com/aspadm/Camera_Net/releases/tag/v1.1.1-maxres) Позволяет в программе Flexscan 3D использовать максимальное разрешение для камер DirectShow. (автоматически для камеры выставляется максимальное разрешение). Автор изменений: Alexey Kirillov <br>
<br>
Автовыставление максимального разрешения DShow камер. Полезно для сканящих на вебки/камеры без собственного ПО/драйверов.<br>
Не совместимо с LibFix по простой причине - заменяются одни и те же библиотеки.<br>
На гитхабе: https://github.com/aspadm/Camera_Net/releases/tag/v1.1.1-maxres<br>
Установка:<br>
В директории установки FlexScan ищем поддиректорию App\Scanner Modules\Advance:<br>
1. Сохраните оригинальные файлы Camera_NET.dll и DirectShowLib-2010.dll<br>
2. Скопируйте с заменой ОБЕ новые библиотеки.<br>
3. Теперь при запуске FlexScan3D будет использовать максимальное поддерживаемое разрешение камер.<br>
Ранее добавленные камеры передобавлять не нужно, но требуется сделать калибровку.<br>
<b/>Camera_Net-1.1.1_machinevisionCameras.zip</b> - Скорректированные библиотеки (dll файлы) для камер, работающих через DirectShow. Была добавлена поддержка промышленных камер. Автор изменений: GI'm 3D <br>
<b/>Camera_Net-1.1.1-machinevisionCameras_src.rar</b> - Т.к.  GI'm 3D исходный код не предоставлял, пришлось внести изменения в исходный код самостоятельно. Исходный код скорректированной библиотеки для камер работающих через DirectShow. Была добавлена поддержка промышленных камер. Автор изменений: Alexander Simonov (данные изменения в код написал сам, со всеми глюками и особенностями, как есть).<br>
