sudo docker build -t anki-2.1.5 .
sudo apt install mplayer
sudo docker run -ti --rm -e DISPLAY=$DISPLAY --device /dev/snd:/dev/snd -v /tmp/.X11-unix:/tmp/.X11-unix anki-2.1.5

https://askubuntu.com/questions/175611/cannot-connect-to-x-server-when-running-app-with-sudo  // ???

http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/  // run gui app in docker
https://github.com/passbolt/passbolt_docker/issues/8  // /docker-entrypoint.sh\": permission denied"
https://stackoverflow.com/questions/41083436/how-to-play-sound-in-a-docker-container // $HOME
https://stackoverflow.com/questions/45700653/can-my-docker-container-app-access-the-hosts-microphone-and-speaker-mac-wind  // sound
