## how to clone respository

    if you use version 1.6.5 of Git and later :
    
        git clone --recursive https://github.com/yoer/qters.git
    
    or older Git versions :

        git clone https://github.com/yoer/qters.git
        cd qters(which call $QTERS_BASE under)
        git submodule update --init --recursive

## how to build

    Open $QTERS_BASE/build/Qters.pro by QtCreator
    All builded info will output to $QTERS_BASE/../Qters_build folder

## how to run

*   chaos
    1. copy database from '$QTERS_BASE/QrFrame/chaos/data/chaos.db' to '$QTERS_BASE/../Qters_build/debug_dest/data/chaos.db'
    2. run '$QTERS_BASE/../Qters_build/chaosd'

## framework

![qters-framework](http://img.hoop8.com/1607B/jLugJrcG.png)

### concepts

#### what is service?

    service is a logic module or a function module, or a bussiness module, which developed by different corporate sector or workgroup.
    service would be loaded by QPluginLoader if module had been configed in database.
    
### submodule(DONE)

*   qrtest

    test framework

*   qrlogger

    simple, convinient and thread safe logger

*   qrorm

    orm framework

*   qrcommon

    common library

*   qrframe

    cilent develop framework

    *   chaos
    
        a client framework in common use
    

### submodule(DOING)

*   qrwidgets

    widgets
    
*   qrupdater

    update framework
    
*   qrcache

    cache
    
*   qrtools

    toolkits
