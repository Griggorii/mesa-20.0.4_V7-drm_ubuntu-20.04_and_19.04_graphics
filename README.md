# mesa-20.0.4_V7-drm_ubuntu-20.04_and_19.04_graphics
graphics , mesa , 20.0.4 hybrid 20.1.0 , libpng12 , alternative driver

Ubuntu X64 ubuntu 19.04 disco dingo , ubuntu 20.04 focal fossa , not ubuntu 18.10.19.10

Mesa download + instructions: https://yadi.sk/d/uzYT1AIDszXagg

optional install driver reinstall libnvidia-compute libnvidia-decode libnvidia-encode если был ранее установлен то переустановите так как скрипт может затереть хотя он у меня не может писать видео в obs через nvenc из за того что видео карта обрезок то у вас это вполне могло работать.

Wayland not crash tty

Если есть спецы по бинарному декомпилированию двоично-десятичный кода , а точнее это троичный скорее всего потому что utf-8 , а не ansi то надо вытащить именно вот что бы такой цвет был в более лёгких новых драиверах я просто сравнивал и видел что картинка по калорийности гораздо лучше в моих модифицированных драиверах хотя они сцеплены по депенденси тот же главный компонент libegl1 не по /usr/lib/x86_64-linux-gnu , а по /lib/x86_64-linux-gnu в wayland бывает что подтормаживает чуть больше чем на оригинале , но это из за того что тут есть libpng12 в придачу к libpng16 что позволит запускать qt4 приложения и сам qt4 но можно удалить libpng12 потому что ситема 19.04 и 20.04 использует libpng16 для этого всего то надо скачать https://github.com/Griggorii/libpng12-0_ubuntu_debian_amd64 после первой команды можно сделать sudo make uninstall и это удалит libpng12 я думаю только профи которые стоят у истоков создания операционок поимут что /lib теперь ссылкой и по этому такие костыли и потом что бы запустить прошивальщик тех же mtk телефонов типа SP_Flash_Tool_v5.1744 и наверное и другие нужна поддержка библиотеки libpng12 которую выбросили не понятно кто и как их после этого называть я понимаю захотели хаипа и дене итд перименовать бысто выдать qt5 тулкит , а что бы каким то боком вот так же прикрутить ну даже вручную дело пяти минут редхата каноникла упаковать в deb сбоку и положить в репозитории обозначить что это элемент qt4 такие то такие старые программы без него не запустятся итд готово. Для особо внимательных расскажу что это не фантастика фаилы могут изменяться прямо внутри не смотря на код нам останется снять кто умеет дефините и сделать уже новый драйвер как пример я могу дать вот этот браузер он будет работать на всех версиях убунт начиная от 16.04 не зависимо от версии glibc потому что продавлено на бинарном уровне открыт образ одного фокса в другом и соеденинён https://github.com/Griggorii/linux-firefox-config_v2_2019 это подобно .config в котором как ты настроишь так и снимешь дамп , криво настроишь ну и снимешь соответственно кривой дапм так что не надо надеяться что вы супер кодер так как программы могут само модифицироваться и на данный момент повторю это не фантастика у вас каждый дамп в tar.xz может на несколько баит или мегабайт отличаться от предыдущего если вы допустим заново что то переконфигурируете и сделаете make install то контрольная сумма такого тарболла может отличаться что об этом говорит уже что это другая конфигурация которая может быть лучше работать или наоборот.
_____________________________________________________________________________________________________________________________

dependency

# libEGL.la - a libtool library file
# Generated by libtool (GNU libtool) 2.4.6.42-b88ce

# The name that we can dlopen(3).
dlname='libEGL.so.1'

# Names of this library.
library_names='libEGL.so.1.0.0 libEGL.so.1 libEGL.so'

# The name of the static archive.
old_library=''

# Linker flags that cannot go in dependency_libs.
inherited_linker_flags=' -pthread'

# Libraries that this one depends upon.
dependency_libs=' -lxcb-dri2 -lX11-xcb -lX11 -lxcb -lxcb-dri3 -lxcb-xfixes -lxcb-present -lxcb-sync -lxshmfence /usr/lib/x86_64-linux-gnu/libgbm.la -lz -lexpat -ldl /usr/lib/x86_64-linux-gnu/libdrm.la -lm /usr/lib/x86_64-linux-gnu/libglapi.la -lpthread'

# Names of additional weak libraries provided by this library
weak_library_names=''

# Version information for libEGL.
current=1
age=0
revision=0

# Is this an already installed library?
installed=yes

# Should we warn about portability when linking against -modules?
shouldnotlink=no

# Files to dlopen/dlpreopen
dlopen=''
dlpreopen=''

# Directory that this library needs to be installed in:
libdir='/usr/lib/x86_64-linux-gnu'

Donate my demo beta full stack graphics support contract firm all device: griggorii@gmail.com

dlopen idea

