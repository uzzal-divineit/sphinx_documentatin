Clone and Run **PrismERP 3.1.0**
===================


This guide will show you how to clone and run **PrismERP 3.1.0**

----------


PrismERP has its own repository structure that needs some defined steps to successfully  clone. Also, there is privacy and security setting to access the repository. And after cloning the repository, some extra library needs to be downloaded. In this documentation we will go cover all the necessary steps to run PrismERP 3.1.0.   

> **Note:** 


> - **Access Permission:** You need access permission for your  git account. Without it, you cannot clone the. *(See  [environment setup][2] )*
> - **Environment Setup:** you need to add [apache-maven-3.3.9][1] to your environment variable path and also ``` JAVA_HOME ``` to your system variable. *(See  [environment setup][2] )*

# Cloning from server repository
The very first thing is clone **prismERP** from server repository. To clone, you have two options-

	A. Using Source Tree GUI software 
	B. Using terminal/cmd

### Method-A:  *Using Source tree GUI*
>-  **Note:** Divine IT git server has no SSL security certification. you need to manually disable SSL security option for cloning from git.divineit.net. 

####  Disable SSL security 
Go to 
	Tools>Options 
	 --> Select Git tab
	 --> Select Git tab
	 --> Check the "Disable SSL certificate validation"
	![ ](https://github.com/uzzal-divineit/sphinx_documentatin/blob/master/res/disable_SSL.png)

#### Clone 
from source tree, select clone sub menu 
![](https://github.com/uzzal-divineit/sphinx_documentatin/blob/master/res/clone_menue.png)

now enter remote git address and location of local folder
here, our remote git repository address is ```https://git.divineit.net/prism/prism-all.git```


![](https://github.com/uzzal-divineit/sphinx_documentatin/blob/master/res/clone_location.png)

click clone

  [1]: https://repo.maven.apache.org/maven2/org/apache/maven/apache-maven/3.3.9/apache-maven-3.3.9-bin.zip
  [2]: http://
  [3]: https://
  [4]: http://
  [5]: https://
  [6]: http://
  [7]: http://
  [8]: http://
