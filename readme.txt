./configure --prefix=/usr && make && su -c 'make install'
./inotifywait -c -rme create,modify,delete,move,attrib,delete_self /home /etc