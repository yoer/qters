## how to clone respository

if you use version 1.6.5 of Git and later :

    git clone --recursive <span class="hljs-string">https:</span><span class="hljs-comment">//github.com/yoer/qters.git</span>
    `</pre>

    or older Git versions :

    <pre>`git clone https:<span class="hljs-comment">//github.com/yoer/qters.git</span>
    cd <span class="hljs-function"><span class="hljs-title">qters</span><span class="hljs-params">(which call <span class="hljs-variable">$QTERS_BASE</span> under)</span></span>
    git submodule update --init --recursive
    `</pre>

    ## how to build

    <pre>`Open <span class="hljs-variable">$QTERS_BASE</span>/build/Qters<span class="hljs-built_in">.</span>pro <span class="hljs-keyword">by</span> QtCreator
    <span class="hljs-literal">All</span> builded info will output <span class="hljs-keyword">to</span> <span class="hljs-variable">$QTERS_BASE</span><span class="hljs-subst">/</span><span class="hljs-built_in">..</span>/Qters_build folder
    `</pre>

    ## how to run

*   chaos<pre>`<span class="hljs-number">1</span>. <span class="hljs-keyword">copy</span> database <span class="hljs-keyword">from</span> <span class="hljs-string">'$QTERS_BASE/QrFrame/chaos/data/chaos.db'</span> <span class="hljs-keyword">to</span> <span class="hljs-string">'$QTERS_BASE/../Qters_build/debug_dest/data/chaos.db'</span>
    <span class="hljs-number">2</span>. run <span class="hljs-string">'$QTERS_BASE/../Qters_build/chaosd'</span>
    `</pre>

    ## framework

      ![qters-framework](http://img.hoop8.com/1607B/jLugJrcG.png)

    ### concepts

    #### what is service?

    <pre>`service <span class="hljs-keyword">is</span> a logic <span class="hljs-built_in">module</span> <span class="hljs-keyword">or</span> a <span class="hljs-reserved">function</span> <span class="hljs-built_in">module</span>, <span class="hljs-keyword">or</span> a bussiness <span class="hljs-built_in">module</span>, which developed <span class="hljs-keyword">by</span> different corporate sector <span class="hljs-keyword">or</span> workgroup.
    service would be loaded <span class="hljs-keyword">by</span> QPluginLoader <span class="hljs-keyword">if</span> <span class="hljs-built_in">module</span> had been configed <span class="hljs-keyword">in</span> database.
    `</pre>

    ### submodule(DONE)

*   qrtest
    <pre>`<span class="hljs-title">test</span> framework
    `</pre>
*   qrlogger
    <pre>`simple, convinient <span class="hljs-literal">and</span> <span class="hljs-keyword">thread</span> safe logger
    `</pre>
*   qrorm
    <pre>`<span class="hljs-title">orm</span> framework
    `</pre>
*   qrcommon
    <pre>`<span class="hljs-keyword">common</span> library
    `</pre>
*   qrframe
    <pre>`<span class="hljs-title">cilent</span> develop framework
    `</pre>

        *   chaos<pre>`  <span class="hljs-tag">a</span> client framework <span class="hljs-keyword">in</span> common use
    `</pre>

    ### submodule(DOING)

*   qrwidgets
    <pre>`widgets
    `</pre>
*   qrupdater
    <pre>`<span class="hljs-title">update</span> framework
    `</pre>
*   qrcache
    <pre>`<span class="hljs-keyword">cache</span>
    `</pre>
*   qrtools
    <pre>`toolkits