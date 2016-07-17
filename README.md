# Qters's folder structure in github
	mkdir Qters
	cd Qters
	git clone https://github.com/Qters/QrUpdater.git
	git clone https://github.com/Qters/QrLogger.git
	git clone https://github.com/Qters/QrTest.git
	git clone https://github.com/Qters/QrCommon.git
	git clone https://github.com/Qters/QrOrm.git
	git clone https://github.com/Qters/QrCache.git
	git clone https://github.com/Qters/QrFrame.git
	git clone https://github.com/Qters/QrWidgets.git
	git clone https://github.com/Qters/QrTools.git
	git clone https://github.com/Qters/Qters.git
	git clone https://github.com/Qters/build.git
	
	after those command, your folder structure should be like :
	./Qters
	./Qters/QrCache
	./Qters/QrCommon
	./Qters/QrFrame
	./Qters/QrLogger
	./Qters/QrOrm
	./Qters/QrTest
	./Qters/QrTools
	./Qters/QrUpdater
	./Qters/QrWidgets
	./Qters/Qters
	./Qters/build
	
	then, open ./build/Qters.pro by qtcretor


# Qters's Framework


  ![qters-framework](https://i.imgsafe.org/2c9624d.png)



**QrLogger**(FORKED)

  simple, convinient and thread safe logger for Qt-based C++ apps
  
  
**QrUpdater**(FORKED)

  update framework for Qters
  
  
**Qters**(DONE)
  
  qters framework project
  
  
**QrTest**(DONE)
  
  test framework for Qt-based C++ apps
  

**QrOrm**(DONE)

  orm framework for Qt-based C++ apps
  


**QrCommon**(DOING)

  common functions for Qters
  
  
**QrFrame**(DOING)

***chaos***(DONE)

  cilent develop framework for Qt-based C++ apps
 
 
**QrWidgets**(TODO)

  widgets for Qters
  

**QrCache**(TODO)

  cache framework for Qt-based C++ apps
  
  
**QrTool**(TODO)

  toolkits for Qt-based C++ apps
  

## concepts 

   Qters's Framework support to do job by the collaboration between company departments.
  
**Service**(USER TO DO)

  Separate codes by functional modules or logical module, different part can be develop by different department,
  and would be loaded by QPluginLoader if module had been configed in database;

**Application**(USER TO DO)

