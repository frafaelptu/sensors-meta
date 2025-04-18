# **_Sensors meta_**

It will group all microservices using git module strategy.

* [Design Doc](https://www.notion.so/Design-Doc-Ado-o-da-Arquitetura-de-Microsservi-os-no-AlgaSensors-1d9a5a02fcab80b6a650fac3f61e97da?pvs=4)
* [Microservices diagram](https://whimsical.com/projeto-algasensors-refinando-modelagem-9fUrUvjpdqoS5GT7ZescHs@9kGbMz9Kzt)



**References:** _AlgaWorks EMS Training_

### Commands git submodules 
download all submodules
```bash
 git pull --recurse-submodules
```

add project as submodule (example: git submodule add <url> <path>)
```bash
git submodule add git@github.com:frafaelptu/temperature-processing.git microservices/temperature-processing
```

clone all submodules (example: git clone --recurse-submodules <url>)

params: -j8: number of jobs to run in parallel
```bash 
git clone --recuse-submodules -j8 git@github.com:frafaelptu/sensors-meta.git sensors-meta
```