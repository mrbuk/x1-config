
## Sound

Fix the low volume as described in the following [forum post](https://forums.lenovo.com/t5/Linux-Discussion/X1-Carbon-Gen-6-weird-audio-behaviour/td-p/4167282)

```
sudo cp sound/alsa-base.conf /etc/modprobe.d/alsa-base.conf
sudo cp sound/hda-lenovo-x1c6-init.fw /lib/firmware/hda-lenovo-x1c6-init.fw
```
