# ovos-binary-shop
Wheels and pre-compiled binaries for usage with ovos plugins / images


see releases for downloadable files


## Python 3.10

- [tflite-runtime aarch64](https://github.com/OpenVoiceOS/ovos-binary-shop/releases/tag/tflite-runtime_python_3.10_aarch64.whl)


## Python 3.11

- [tflite-runtime aarch64/armv6l/armv7l/x86_64](https://github.com/OpenVoiceOS/ovos-binary-shop/releases/tag/tflite-runtime_python3.11_linux_aarch64%2Farmv6l%2Farmv7l%2Fx86_64.whl)
- [onnxruntime-x86_64.whl ](https://github.com/OpenVoiceOS/ovos-binary-shop/releases/tag/tflite-runtime_python3.11_linux_aarch64%2Farmv6l%2Farmv7l%2Fx86_64.whl)


### PKGBUILDS

PKGBUILDS generated via https://github.com/anntzer/pypi2pkgbuild

each directory in this repo is a package

#### Dependency Build Tree:

*WIP* List order in which to build the pkgbuilds

*For Testing*:
- git clone https://github.com/OpenVoiceOS/ovos-binary-shop into a clean chroot / os environment
- cd ovos-binary-shop/python-$pkgname
- makepkg -si ("s" will resolve dependencies from AUR and Manjaro Repos, "i" will install them as official packages via pacman)

```
python-memory-tempfile
python-combo-lock
python-json-database
python-kthread
python-ovos-utils

python-mycroft-messagebus-client

python-ovos-backend-client
python-rich-click
python-ovos-config

python-quebra-frases
python-ovos-lingua-franca

python-langcodes
python-ovos-bus-client
python-ovos-plugin-manager

python-ovos-workshop

python-simplematch
python-padacioso

python-ovos-core
python-ovos-gui

python-ovos-stt-plugin-server
python-ovos-skill-installer
python-speechrecognition
python-pyaudio
python-srt
python-vosk
python-ovos-stt-plugin-vosk
python-webrtcvad
python-ovos-vad-plugin-webrtcvad
python-pocketsphinx
python-phoneme-guesser
python-ovos-ww-plugin-pocketsphinx
python-petact
python-precise-runner
python-ovos-ww-plugin-precise
python-ovos-ww-plugin-vosk
python-sonopy
python-precise-lite-runner
python-ovos-ww-plugin-precise-lite
python-ovos-listener

python-bitstruct
python-pprintpp
python-ovos-ocp-files-plugin
python-ovos-audio-plugin-simple
python-ovos-plugin-common-play
python-ovos-ocp-m3u-plugin
python-ovos-ocp-rss-plugin
python-ovos-ocp-news-plugin
python-ovos-tts-plugin-mimic3-server
python-ovos-audio

python-ovos-phal-plugin-color-scheme-manager
python-ovos-phal-plugin-connectivity-events
python-ovos-phal-plugin-ipgeo
python-ovos-phal-plugin-network-manager
python-ovos-phal-plugin-oauth
python-ovos-phal-plugin-system
python-bs4
python-url-normalize
python-requests-cache
python-wallpaper-finder
python-ovos-phal-plugin-wallpaper-manager
python-ovos-phal

python-pako
python-ovos-skills-manager
python-ovos-skill-setup
python-ovos-skill-volume
python-ovos-skill-hello-world
python-ovos-skill-stop
python-ovos-skill-homescreen
python-ovos-skill-installer
python-ovos-skill-naptime
python-ovos-skill-personal
python-ovos-skill-fallback-unknown
python-ovos-skill-filebrowser
python-ovos-skill-camera-git
python-ovos-skill-weather-git
python-pytube
python-tutubo
python-skill-youtube-music-git
```
