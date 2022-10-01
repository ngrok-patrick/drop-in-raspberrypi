# drop-in-raspberrypi
These are the commands you can use to add Ngrok to a Raspberry Pi from the Console

If you are on a Raspberry Pi Console, and want to run Ngrok real quick, these
are the commands you can run to do that.

```
sudo apt-get update
sudo apt-get install curl -y
curl -O https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-arm.tgz
tar xvfz ngrok-v3-stable-linux-arm.tgz 
./ngrok config add-authtoken 2EVelYOUR-AUTH-TOKENhfhZT9
```

`./ngrok http 3000` If you can't remember how to Start Ngrok

Maybe someone will find this useful

-P
