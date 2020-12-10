# Installation de Photon WorkShop (Ubuntu 20.04)
Dépendances 32 bits nécessaires à *Photon WorkShop*:

    apt install libc6:i386 \
                libxext6:i386 \
                libncurses5:i386 \
                libfreetype6:i386 \
                libmpg123-0:i386 \
                libxml2:i386 \
                libgl1:i386 \
                libgstreamer-plugins-base1.0-0:i386

Installation de wine :

    snap install wine-platform-4-stable

Installation de *Photon WorkShop* :

    export PATH=/snap/wine-platform-4-stable/current/opt/wine-stable/bin:$PATH
    export LD_LIBRARY_PATH=/snap/wine-platform-4-stable/current/opt/wine-stable/lib:$LD_LIBRARY_PATH
    wine ~/Téléchargements/Photon_WorkShop_V2.1.21.exe

Lancement de Photon WorkShop :

    export PATH=/snap/wine-platform-4-stable/current/opt/wine-stable/bin:$PATH
    export LD_LIBRARY_PATH=/snap/wine-platform-4-stable/current/opt/wine-stable/lib:$LD_LIBRARY_PATH
    wine ~/.wine/drive_c/Program\ Files\ \(x86\)/Photon_WorkShop_V2.1.21/Photon_Workshop_V2.1.21.exe
