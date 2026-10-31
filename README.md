# `dpkg-curl-doas-bash`
(1) kill `apt-add-respository` for security reasons
(2) replace `sudo` with `doas` for security reasons
(3) `dpkg-curl-doas-bash` for security reasons

## `dpkg-curl-doas-bash https://pixi.sh/install.sh pixi`
* Then `sudo dpkg -i pixi_1.0.0_amd64.dpkg`
* Then `apt remove pixi`
* Then `dpkg-curl-doas-bash https://pixi.sh/install.sh pixi 2.3.4`
* Then `dpkg --listfiles pixi`
