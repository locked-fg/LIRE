LIRE Fork
===

This is a Fork of the official LIRE Repo to make it available in maven projects. The only change is the direct integration of [jOpenSurf sources](tree/master/src/main/java/com/stromberglabs/jopensurf) into the main directory, so that a jar including this library can be built and installed localy.

Install:
---
* Clone the repo from GitHub:
    
    ```git clone https://github.com/locked-fg/LIRE.git```

* Install the lib into your local repo:

    ```mvn -Prelease install -DskipTests=true -Dgpg.skip=true```
    
	
LIRE
---
For all issues and questions regarding lire, refer to the original lire sources:
* [Original LIRE Readme](README.txt)
* [Lire Repo](https://code.google.com/p/lire/)
