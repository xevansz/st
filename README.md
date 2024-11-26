## simple terminal
My very simple fork of st.

## patches added
* alpha & changealpha (transparency)
* Xresources w/ reload signal (pywal takes priority)
* ligatures
* scrollback ringbuffer, with mouse

## config
* copied keybindings from BreadOnPenguins, default color theme is nord
* **config.h**. Bindings are same besides:
  - ```alt + c``` & ```alt + v``` for copy-paste
  - ```alt + a``` & ```alt + s``` to increase and decrease alpha respectively
  - ```alt + shift + k``` & ```alt + shift + j``` to increase and decrease font size, respectively

## installation
```
git clone https://github.com/xevansz/st
cd st
sudo make install
```
