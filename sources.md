
# Sources.list
No Debian e derivados o arquivo **/etc/apt/sources.list** contém os repositórios que serão usados pelos programas de gestão de pacotes.

Essas são algumas possibilidades do conteúdo do arquivo para as várias versões de Debian. 

. Buster (main)

    deb http://deb.debian.org/debian buster main
    deb http://deb.debian.org/debian buster-updates main
    deb http://security.debian.org buster/updates main

. Buster (non-free)

    deb http://deb.debian.org/debian buster main contrib non-free
    deb http://deb.debian.org/debian buster-updates main contrib non-free
    deb http://security.debian.org buster/updates main contrib non-free

. Buster (com back-ports)

    deb http://deb.debian.org/debian buster main
    deb http://deb.debian.org/debian buster-updates main
    deb http://security.debian.org buster/updates main
    deb http://deb.debian.org/debian buster-backports main

. Buster (non-free com backports)

    deb http://deb.debian.org/debian buster main contrib non-free
    deb http://deb.debian.org/debian buster-updates main contrib non-free
    deb http://security.debian.org buster/updates main contrib non-free
    deb http://deb.debian.org/debian buster-backports main contrib non-free

. Bullseye (main)

    deb http://deb.debian.org/debian bullseye main
    deb http://deb.debian.org/debian bullseye-updates main
    deb http://security.debian.org/ bullseye-security main

. Bullseye (non-free)

    deb http://deb.debian.org/debian bullseye main contrib non-free
    deb http://deb.debian.org/debian bullseye-updates main contrib non-free
    deb http://security.debian.org/ bullseye-security main contrib non-free

. Jessie (main)

    deb http://deb.debian.org/debian jessie main
    deb http://deb.debian.org/debian jessie-updates main
    deb http://security.debian.org jessie/updates main

. Jessie (non-free)

    deb http://deb.debian.org/debian jessie main contrib non-free
    deb http://deb.debian.org/debian jessie-updates main contrib non-free
    deb http://security.debian.org jessie/updates main contrib non-free

. Stretch (main)

    deb http://archive.debian.org/debian stretch main
    deb http://archive.debian.org/debian stretch-updates

. Stretch (non-free)

    deb http://archive.debian.org/debian stretch main contrib non-free
    deb http://archive.debian.org/debian stretch-updates main contrib non-free

. Sid (main)

    deb http://deb.debian.org/debian sid main

. Sid (non-free)

    deb http://deb.debian.org/debian sid main contrib non-free

. Linux-Libre

    deb https://linux-libre.fsfla.org/pub/linux-libre/freesh/ freesh main
