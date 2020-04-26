# 10 Things to do after installing [Elementary OS](https://elementary.io/)
 #####  Written By Rohit Singh on 26 April 2020
---

[![desktop](https://elementary.io/images/screenshots/desktop.jpg)](https://youtu.be/XS6sPxcYd5Q)

Elementary OS is Ubuntu base great LINUX distro, a good choice for STUDENTS and Many people as well. It's just like MAC OS but It is much better than that. It is a light Weight linux Distro Allows you to work faster and It comes with cool animations in it.
## Here are few things you need to do after downloading Elementary OS :-)

### 1) Install dimmer App from app store : -
In many hardware there may have some brightness issue, to fix this download Dimmer app. It is very easy to use. Download it from app center.
![Photo](https://appstream.elementary.io/appcenter/media/bionic/com/github/panosx2.brightness/2FFAC77CF086C249EA237A5F986AA037/screenshots/image-1_orig.png)
![app](https://appstream.elementary.io/appcenter/media/bionic/com/github/panosx2.brightness/2FFAC77CF086C249EA237A5F986AA037/icons/64x64/com.github.panosx2.brightness_com.github.panosx2.brightness.png)

### 2) App Store error fixing : -

Some of you might face an error in app store like 

![error](https://i.stack.imgur.com/uG4SU.jpg)

Don't worry just open your terminal and type this 

`$ sudo sed -i /^deb cdrom/d' /usr/share/sources.list`

then press ENTER 

### 3) Downlaod Screen Recorder :-
This is a very needful app for you for making video tutorials and many more.
This app is so simple in use and produce very smooth video rendering. Download it from [AppCenter](https://appcenter.elementary.io/)

>![App logo](https://appstream.elementary.io/appcenter/media/bionic/com/github/mohelm97.screenrecorder/98E144B73F6A64B11A5EB68D9EB14B4F/icons/64x64/com.github.mohelm97.screenrecorder_com.github.mohelm97.screenrecorder.png)

![feature](https://appstream.elementary.io/appcenter/media/bionic/com/github/mohelm97.screenrecorder/98E144B73F6A64B11A5EB68D9EB14B4F/screenshots/image-1_orig.png)

### 4) Downlaod tweaks : -
Many of us loves to customise our desktop. It a user friendly tool which allows you to customise your Desktop theme and many more cool stuffs.
* Search for "Tweaks" in yopur appcenter
* install "gnome-tweaks"

   ![k](https://quassy.github.io/elementary-apps/img/windows/elementary%20Tweaks.png)
### 5) Install neofetch : -
This pakag will show your system config ina very cool way
* type this command in terminalto inastall neofetch`sudo apt install neofetch`
* type `neofetch` in terminal to see the magic.

![koy](https://scontent-yyz1-1.cdninstagram.com/v/t51.2885-15/e35/s1080x1080/89612632_138604687537451_3064781092810853025_n.jpg?_nc_ht=scontent-yyz1-1.cdninstagram.com&amp;_nc_cat=111&amp;_nc_ohc=WXeBrFUHaCAAX-48MSD&amp;oh=513c6fd9e61ca9186e15d88f4d9facd8&amp;oe=5ECCFA5E)

### 6) Install foremost : -
It often occur that you may delete some relevent files from a directory, that will cause really a problem. Here is the solution you just need to download a famous data recovery tool "foremost". It will help you to recover all your deleted data.
* type `sudo apt install foremost` then type `y`
* how to use it - 
* 
 For this scenario, we have kept an image named ‘dan.jpg ’ on our system. We will now delete it from the system with the following command,

$ `sudo rm –rf dan.jpg`

Now we will use the foremost utility to restore the image, run the following command to restore the file,

$  `foremost –t jpeg –I /dev/sda1`

Here, with option ‘t’ , we have defined the type of file that needs to be restored,

-I , tells the foremost to look for the file in partition ‘/dev/sda1’. We can check the partition with ‘mount’ command.

Upon successful execution of the command, the file will be restored in current folder. We can also add option to restore the file in a particular folder with option ‘o’

$ `foremost –t jpeg –I /dev/sda1 –o /root/test_folder`
  
### 7) Install Gparted : -
Downlaod this app from your AppCenter. This app will help you in maintaining your drive partitions very easily.




![hello](https://linuxhint.com/wp-content/uploads/2018/12/7-24.png)

### 8) Make custom short cuts : -
To get the best experience in Elementary you must know all shortcuts of it. You may also creat your custom short cuts.
* First, open system settings and click keyboard:

![kojhjdh](https://i.stack.imgur.com/lHbNs.png)

* Chose Custom, in the sidebar

![kdkdld](https://i.stack.imgur.com/OKGdN.png)

* Click the + button

![jdgdjd](https://i.stack.imgur.com/efPO4.png)

* Enter your command

![pop](https://i.stack.imgur.com/r0l8B.png)

* Click "Disabled", then press your chosen shortcut and it will show up:

![popopop](https://i.stack.imgur.com/RBvDj.png)
* And you are Done!
![yuy](https://i.stack.imgur.com/jeN3u.png)

### 9) Change themes : -
To change themes first go to the gnome-looks.org
* Downlaod your preferred theme archive file.
* Extract it.
* move this folder to `/usr/share/themes`
* open `Tweaks app`
* go to appearence 
* choose the theme :-)

### 10) Install mkusb :-
This is a very powerful tool. It will allow you to make live persistance usb of any OS.
type these command to download it :

`sudo add-apt-repository ppa:mkusb/ppa`  # and press Enter
`sudo apt update`
`sudo apt install mkusb usb-pack-efi`

![kfhfk](https://help.ubuntu.com/community/mkusb/artwork?action=AttachFile&amp;do=get&amp;target=mkusb128.png)

To learn more about this go to [mkusb](https://help.ubuntu.com/community/mkusb)
If you want to learn how to use it then [click here](https://youtu.be/ScCUDX5gtRw)
#### Thanks for staying with this blog




