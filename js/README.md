### Usage
Start a new Kevoree JS runtime in a container using:  

```sh
docker run --rm -it kevoree/js -n node0 -g sync -m /path/to/your/model.json

# or

docker run --rm -it kevoree/js -n node0 -g sync -k /path/to/your/model.kevs

# or just

docker run --rm -it kevoree/js
```
