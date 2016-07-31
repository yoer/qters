## how to clone respository

    if you use version 1.6.5 of Git and later :
    
        git clone --recursive https://github.com/yoer/qters.git
    
    or older Git versions :

        git clone https://github.com/yoer/qters.git
        cd qters( which call '$QTERS_BASE' under )
        git submodule update --init --recursive
	
after clone, then execute '*submodule-master.sh*' to checkout all submodules's branch to master.

## how to build

    Open $QTERS_BASE/build/Qters.pro by QtCreator
    All builded info will output to $QTERS_BASE/../Qters_build folder

## how to run

*   [chaos](https://github.com/Qters/QrFrame/tree/master/chaos)
    ![qters-chaos](http://img.hoop8.com/1607C/10cJIqk1.png)
    1. copy database from '$QTERS_BASE/QrFrame/chaos/data/chaos.db' to '$QTERS_BASE/../Qters_build/debug_dest/data/chaos.db'
    2. run '$QTERS_BASE/../Qters_build/chaosd'

## framework

![qters-framework](http://img.hoop8.com/1607B/jLugJrcG.png)

### concepts

#### what is service?

    service is a logic module or a function module, or a bussiness module, which developed by different corporate sector or workgroup.
    service would be loaded by QPluginLoader if module had been configed in database.
    
### submodule(DONE)

*   [qrtest](https://github.com/qters/qrtest.git)

    test framework

*   [qrlogger](https://github.com/qters/qrlogger.git)

    simple, convinient and thread safe logger

*   [qrorm](https://github.com/qters/qrorm.git)

    orm framework

*   [qrcommon](https://github.com/qters/qrcommon.git)

    common library

*   [qrframe](https://github.com/qters/qrframe.git)

    cilent develop framework

    *   [chaos](https://github.com/Qters/QrFrame/tree/master/chaos)
    
        a client framework in common use
    

### submodule(DOING)

*   [qrwidgets](https://github.com/qters/qrwidgets.git)

    widgets
    
*   [qrupdater](https://github.com/qters/qrupdater.git)

    update framework
    
*   [qrcache](https://github.com/qters/qrcache.git)

    cache
    
*   [qrtools](https://github.com/qters/qrtool.git)

    toolkits
