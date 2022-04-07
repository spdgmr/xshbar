# speedie's page

#### // [Project 081](https://p081.github.io) | [Elevendebloater](https://spdgmr.github.io/elevendebloater) | [sfetch](https://spdgmr.github.io/sfetch) | [More Projects](https://spdgmr.github.io/projects) | [spDE](https://spdgmr.github.io/spde) | [Discord server](https://ffdiscord.github.io) | [Twitter](https://nitter.net/spdgmr) | [YouTube](https://invidious.namazso.eu/speedie) | [RSS](https://raw.githubusercontent.com/spdgmr/posts/main/rss.xml)
--------------
# xshbar
#### Customizable xsetroot bar designed to be used with window managers.

![image](https://user-images.githubusercontent.com/71722170/162229643-7693f9b6-4e72-4d65-a397-975b8a605b2d.png)

#### Installation
- Install git
- git clone https://github.com/speediegamer/xshbar/
- cd xshbar
- make install
- See Usage.

#### Usage
xshbar must be used with a window manager that supports xsetroot and xsetroot must be installed. First install xsetroot and then make sure your window manager supports xsetroot.

Once you're sure it does, add ~/.config/xshbar/xshbar & to ~/.xinitrc

Now follow Basic Editing

#### Basic Editing
In order to use xshbar, it needs to have something to print. With xshbar this is done using plugins. A few come bundled with xshbar but not all.

##### cd ~/.config/xshbar/plugins 

and then you will be able to see all available plugins. Let's say we want date.plugin.

##### cp date.plugin ../plugins.use

You can now vim into that file and see all of its variables. We can mention these in the file we're about to edit.

##### cd ~/.config/zshbar && vim prn

prn is the file which contains what we will be printing.

![image](https://user-images.githubusercontent.com/71722170/162231229-0ebaabc9-9e12-4ba1-bc15-cc17542fd92c.png)

This is an example of what it can print. You can type plain text in XSHBAR_CORE_DISPLAY or specify a variable using $<myvariable>
