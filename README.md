# dotvim

My Vim configuration

## Installation

    $ cd ~
    $ mv .vim{,.bak}
    $ git clone https://github.com/illenseer/dotvim.git .vim
    $ cd .vim
    $ git submodule init; git submodule update
    $ cd ~
    $ mv .vimrc{,.bak}
    $ ln -sf .vim/vimrc .vimrc

Or in one line for copy and paste:

    cd ~; mv .vim{,.bak}; git clone https://github.com/illenseer/dotvim.git .vim; cd .vim; git submodule init; git submodule update; cd ~; mv .vimrc{,.bak}; ln -sf .vim/vimrc .vimrc
