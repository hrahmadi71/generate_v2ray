# generate_v2ray
This bunch of code helps you to run v2ray on your server. To do so, you must first clone this repository:
```
git clone git@github.com:hrahmadi71/generate_v2ray.git
```
then run it using python:
```
sudo python3 generate_v2ray/main.py --vmess 
```
That's it! You're done. Just copy vmess string it gives you and use it for importing config to your client.

> Note: In this script, the port used for v2ray is sat on 8080. If you want to change it, just modify the `PORT` constant in the `main.py` file.
