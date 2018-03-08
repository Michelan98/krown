
![krownlogo](https://user-images.githubusercontent.com/31903604/37135817-03c81fbe-226d-11e8-8cf5-bda8c43ec57d.png)

Krown
================================

What is Krown?
----------------

Krown is an alt-coin that was created based on Litecoin v0.8.7.5

**N.B** 
This has been created purely for educational purposes. If you have any questions/comments/issues please feel free to contact me.

License
-------

Krown is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.


Testing
-------


### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./krown-qt_test


