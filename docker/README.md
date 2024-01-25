### Build 
```
docker build . -t pcbtools:latest 
```


### Run 
```
docker run -it pcbtools:latest /bin/bash
```


### Run with local sharing 
```
docker run -it -v /Users/nathan/github/pcb-tools:/home pcbtools:latest /bin/bash
``` 
