# speedie's page

#### // [Project 081](https://p081.github.io) | [Elevendebloater](https://spdgmr.github.io/elevendebloater) | [sfetch](https://spdgmr.github.io/sfetch) | [More Projects](https://spdgmr.github.io/projects) | [spDE](https://spdgmr.github.io/spde) | [Discord server](https://ffdiscord.github.io) | [Twitter](https://nitter.net/spdgmr) | [YouTube](https://invidious.namazso.eu/speedie) | [RSS](https://raw.githubusercontent.com/spdgmr/posts/main/rss.xml)
--------------
# xshbar
#### Customizable xsetroot bar designed to be used with window managers.

![image](https://user-images.githubusercontent.com/71722170/163267664-186ef5d8-c772-4c47-ba80-dacc30e7d51c.png)

### Installation
- Install git
- git clone https://github.com/speediegamer/xshbar/
- cd xshbar
- make install
- See Usage.

### Usage
xshbar must be used with a window manager that supports xsetroot and xsetroot must be installed. First install xsetroot and then make sure your window manager supports xsetroot.

Once you're sure it does, add ~/.config/xshbar/xshbar & to ~/.xinitrc

Now follow Basic Editing

### Basic Editing
In order to use xshbar, it needs to have something to print. With xshbar this is done using plugins. A few come bundled with xshbar but not all.

##### cd ~/.config/xshbar/plugins 

and then you will be able to see all available plugins. Let's say we want date.plugin.

##### cp date.plugin ../plugins.use

You can now vim into that file and see all of its variables. We can mention these in the file we're about to edit.

##### cd ~/.config/xshbar && vim prn

prn is the file which contains what we will be printing.

![image](https://user-images.githubusercontent.com/71722170/162231229-0ebaabc9-9e12-4ba1-bc15-cc17542fd92c.png)

This is an example of what it can print. You can type plain text in XSHBAR_CORE_DISPLAY or specify a variable using $<myvariable>
You can also print the output of a command by using 
  
$(echo foo)

##### vim ~/.config/xshbar/xshbar

![image](https://user-images.githubusercontent.com/71722170/162249304-d0c9dd0e-a4aa-4757-bc97-7aee71717084.png)

Add your plugins to XSHBAR_IMPORT() like shown in the screenshot above.

When you're done, save the file, and kill your X session and startx. Enjoy!

### Plugins

Default plugins aren't enough for you? Fear not because there are more plugins available for you to grab.
See [this](https://spdgmr.github.io/xshbar-plugins) page for more information.

### Credits

- Me, I am so based
- You (thanks for using this)
- Possible contributors.

### License

xshbar is licensed under the MIT license. The GitHub repository contains a LICENSE file which you can read if you're not sure what terms apply to your usage of this software.

### NOTE
Please be very careful and look through plugins before adding them to plugins.use. Some plugins may be malicious and delete or steal user data or break your system.
