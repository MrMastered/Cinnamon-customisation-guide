### **Welcome to my Linux customisation guide!** 

#### Here are things we will go over in this guide:
- [Themes](#themes)
- [Fonts](#fonts)
- [Cursors](#cursors)
- [Extensions](#extensions)
- [Wallpapers](#wallpapers)
- [Widgets](#widgets)
- [Icons](#icons)
- [Application styles](#application-styles)


---
###  ⚠WARNING⚠ Any issues that you face will be your responsibility!!!

---


### Themes:

In Linux Mint there are many themes to pick from, you can either find them if you go to:

![Themes Screenshot](images/Screenshot%20from%202025-05-12%2018-01-37.png)

and on there you have to click on "Advanced settings":

![Advanced Settings](images/Pasted%20image%2020250512180422.png)

After you do that you can click on Add/Remove:

![Add/Remove](images/Pasted%20image%2020250512180548.png)

which allows you to install a theme from the official Cinnamon-Look Store,

**note that this only works if you want to install "Desktop themes"!**

Now click on "Desktop" and select the Theme you installed.

---

### Fonts:

Fonts are a really cool thing in Linux, you can install your favorite font using:

#### - Package manager
#### - A website designed for fonts e.g. 1001fonts

**Please note that package manager also means "software center"**

##### For this guide we'll be installing the font "Jetbrains-Mono"

The way you install it is:

![JetBrains Mono Search](images/Pasted%20image%2020250512181213.png)


and then you run this command in your terminal for Debian based systems:

```
sudo apt install fonts-jetbrains-mono
```


For Arch based systems:

```
sudo pacman -S ttf-jetbrains-mono
```

For Fedora

```
sudo dnf install jetbrains-mono-fonts-all
```


Now after we've installed the font, let's apply it!

For this you're going to open your system settings and search for **"Font Selection"**

![[Pasted image 20250512183428.png]]


And now we can apply the font here:

![[Pasted image 20250512183554.png]]

Pick the fonts you want to use for these parts of the font display!

---

### Cursors

For cursors we need to go to a website!

https://www.cinnamon-look.org/browse/

and click on cursors!

![[Pasted image 20250512184001.png]]

When you click on "Cursors" it will redirect you to another page (still on cinnamon-look) where you can download the cursor you want from.

For the tutorial I'll be using this cursor:

![[Pasted image 20250512184150.png]]

You can click on "Download" which will show you a drop down, click on that and it will start installing the cursor.

Now navigate to where you installed the cursor.

![[Pasted image 20250512184453.png]]

right click the file and hit extract here!

Now you should have a normal folder, highlight the folder and hit  CTRL + X to cut, now hit
CTRL + H to show all hidden files.

Now we're going to go back to the home folder and we want to find the .icons folder, if it doesn't exist create it:

![[Pasted image 20250512185512.png]]

now after entering the folder we're going to paste the cursor in here:

![[Pasted image 20250512185654.png]]

Now let's head over to "Themes" to use this cursor

![[Pasted image 20250512190004.png]]

Click on the "Mouse Pointer" and select the cursor you installed!

Note that cursors that are installed externally won't have the actual look of the cursor, so just look for the name of it!

---

### Extensions

In Cinnamon there are so called "Extensions", which allow you to customise your system even more of the system.

To find them we're going to search for them:

![[Pasted image 20250512190630.png]]

Here you can manage your extensions and download new ones:

![[Pasted image 20250512190706.png]]

To apply a newly installed extension click on the plus, and to configure one click on the gear icon at the far right.

---

### Wallpapers:

For wallpapers you can find them on the following websites:

**Basically everything**

https://www.pinterest.com

https://alphacoders.com/

https://www.deviantart.com/

**For Anime:**

https://sakugabooru.com/post

https://safebooru.org/

https://pixiv.pictures/

---

### Widgets:

Cinnamon also has these fun things called "Desklets" that you can place on your desktop here's a quick example of my desklet:

![[Pasted image 20250512191453.png]]

The clock in the top left is the desklet I'm using.

To use desklets:

Search for "Desklets"

![[Pasted image 20250512192123.png]]

Open it up and you'll get an interface similar to this one:

![[Pasted image 20250512192218.png]]

Here you can download desklets, manage them, and change general settings which applies to most desklets!

To apply a desklet click on the plus, to configure the desklet click on the gear icon on the far right.

---

### Icons:

For icons you can follow the exact same guide for [[#Cursors]] but all you have to change is to select "Icons" on the website, and instead of changing "Cursors" in your themes you have to change the Icons.

---

### Application styles:

For application styles we're going to head over to https://www.cinnamon-look.org/browse/ again, and press on "GTK3/4 Themes".
For this tutorial I'll be using Jasper-Gtk-Theme:

![[images/Pasted_image_20250512193638.png]]

Download the theme and go to your install location, there extract the folder and go to your .themes

![[Pasted image 20250512193832.png]]

Place the files in here and close it.

Now go to themes and select it under: "Application".

---

Thanks for reading, hope you got to know how to customise your system more!!
