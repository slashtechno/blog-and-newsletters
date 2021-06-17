# What Servers to run on the Raspberry Pi

The Raspberry Pi is great for running servers. These are some of my Favorites.

Rocket Chat
Rocket Chat is similar to Discord, Slack or Microsoft Teams. You can have multiple channels with video calling and direct messages as well. Rocket Chat takes 1-2 commands to get up and running. All you need to do is make sure snap is installed and install Rocket Chat. The, go to localhost:3000 in your browser or go to <your pi’s ip>:3000

```
sudo apt install snapd
sudo snap install rocket-chat-server
```

Nextcloud
Nextcloud is similar to Google Drive. Nextcloud allows you to have files hosted on your Pi or server, and have the files available anywhere. You can even integrate mail clients, note taking apps, and even document editing. The best part of this is that it uses a GUI that is easy to learn, yet advanced enough to be flexible to be used in many situations. The installation is pretty easy, you install snap, install the snap, and then go to localhost in your browser or your Raspberry Pi’s IP address.

```
sudo apt install snapd
sudo snap install nextcloud
```

Apache
With Apache, you can host a website on your Raspberry Pi. The Raspberry Pi Foundation has a good tutorial [here](https://projects.raspberrypi.org/en/projects/lamp-web-server-with-wordpress/) to install Wordpress and Apache. If you want to host a website without Wordpress, [this](https://magpi.raspberrypi.org/articles/apache-web-server) is a great tutorial.
