# sensors-meta

### commands git submodules 
download all submodules
```bash
 git pull --recurse-submodules
```

add project as submodule (example: git submodule add <url> <path>)
```bash
git submodule add git@github.com-pessoal:frafaelptu/temperature-processing.git microservices/temperature-processing
```

clone all submodules (example: git clone --recurse-submodules <url>)

params: -j8: number of jobs to run in parallel
```bash 
git clone --recuse-submodules -j8 git@github.com:frafaelptu/sensors-meta.git sensors-meta-test
```