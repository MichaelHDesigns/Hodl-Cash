


Compiling Merge
---------------

### Static compile (linux)

    git clone https://github.com/ProjectMerge/merge
    cd merge/depends
    make HOST=x86_64-linux-gnu
    cd ..
    ./autogen.sh
    ./configure --prefix=`pwd`/depends/x86_64-linux-gnu
    make


Credits
-------

Hodl Cash would like to thank the PIVX Project for use of its existing platform (and for being good sports) - https://github.com/PIVX-Project/PIVX,
and as well - the Qtum project (for use of its great UI) - https://github.com/qtumproject/qtum.


License
-------

Hodl Cash Core is released under the terms of the MIT license. See [COPYING](COPYING) for more information or see https://opensource.org/licenses/MIT.

