# minecraft-launcher
Just the minecraft-launcher in a openjdk based container ;)

# How to use
```
docker run --rm \
	-e DISPLAY \
	-v /tmp/.X11-unix/:/tmp/.X11-unix/ \
	--device /dev/snd/ \
	-v $HOME/.minecraft:/root/.minecraft \
	somatorio/minecraft-launcher
```
