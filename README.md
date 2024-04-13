![Screenshot 2024-04-12 002035](https://github.com/exosever/hologotchi/assets/50787424/2cba6105-2b84-4f18-a88d-a0972ca0b307)


DEMOTIVATED

![DEMOTIVATED](https://github.com/exosever/hologotchi/assets/50787424/bcc8970b-bae3-462c-9eeb-0d66a3303baa)


DEBUG

![DEBUG](https://github.com/exosever/hologotchi/assets/50787424/d0f408cf-5faf-4c2e-bc77-481aa22a2bd4)


COOL

![COOL](https://github.com/exosever/hologotchi/assets/50787424/7e7836ff-6468-4041-a65e-66b048044c17)

BROKEN

![BROKEN](https://github.com/exosever/hologotchi/assets/50787424/6b8828bd-d653-426b-ae1e-e9fb6bbb79e0)


BORED

![BORED](https://github.com/exosever/hologotchi/assets/50787424/7885a168-99c1-493d-9d3d-18446eb2ca03)


AWAKE

![AWAKE](https://github.com/exosever/hologotchi/assets/50787424/f90e575d-d61f-4b4c-89fd-36e2d80369c2)


ANGRY

![ANGRY](https://github.com/exosever/hologotchi/assets/50787424/53433363-ffcc-47eb-8e4e-aff215ded205)


UPLOAD2

![UPLOAD2](https://github.com/exosever/hologotchi/assets/50787424/676455ce-af84-4d3c-8190-d2dab42aef8b)


UPLOAD1

![UPLOAD1](https://github.com/exosever/hologotchi/assets/50787424/5fc42249-211e-4893-baf6-95ba01c9915a)


UPLOAD

![UPLOAD](https://github.com/exosever/hologotchi/assets/50787424/3f65cee6-f033-40f8-9f5a-460422a0bfe7)


SMART

![SMART](https://github.com/exosever/hologotchi/assets/50787424/f6ffc271-76d1-452b-8f00-ea0e2b9db0fa)


SLEEP2

![SLEEP2](https://github.com/exosever/hologotchi/assets/50787424/685c9cb1-86d2-4e5f-a42f-ebcf8fc23f4b)


SLEEP

![SLEEP](https://github.com/exosever/hologotchi/assets/50787424/c43f591b-b8cd-417e-a38e-3577c79d1016)


SAD

![SAD](https://github.com/exosever/hologotchi/assets/50787424/19f3bc42-a719-4d0c-a573-987654d1b23a)


MOTIVATED

![MOTIVATED](https://github.com/exosever/hologotchi/assets/50787424/842f02fd-9fab-4821-9b09-5b9e35e3bb4c)


LOOK_R_HAPPY

![LOOK_R_HAPPY](https://github.com/exosever/hologotchi/assets/50787424/e1eb90ac-ee77-4847-b96c-6f2fcdbe5290)


LOOK_R

![LOOK_R](https://github.com/exosever/hologotchi/assets/50787424/6dfa505d-792d-49f3-98e3-1cfd689449ef)


LOOK_L_HAPPY

![LOOK_L_HAPPY](https://github.com/exosever/hologotchi/assets/50787424/e10c980d-8a69-4a66-868d-327f272a69b8)


LOOK_L

![LOOK_L](https://github.com/exosever/hologotchi/assets/50787424/9101ce7d-291d-4192-ba92-42525424d636)


LONELY

![LONELY](https://github.com/exosever/hologotchi/assets/50787424/ee70f2b6-eb88-41b6-aa06-b0dafeca2d2d)


INTENSE

![INTENSE](https://github.com/exosever/hologotchi/assets/50787424/6da621f2-ab55-444a-8428-0f9fdba79150)


HAPPY

![HAPPY](https://github.com/exosever/hologotchi/assets/50787424/e7750190-f23b-4e3e-8ee7-f08e7dc2d45e)


GRATEFUL

![GRATEFUL](https://github.com/exosever/hologotchi/assets/50787424/a485233f-b59e-49a2-9c73-feea46a7dd84)


FRIEND

![FRIEND](https://github.com/exosever/hologotchi/assets/50787424/f0297e4a-d129-4bea-96f3-f48b599e44e1)


EXCITED

![EXCITED](https://github.com/exosever/hologotchi/assets/50787424/13c53f5e-5e90-4118-b75a-8ebee02deff9)



## :heavy_exclamation_mark: Requirements
First and foremost, keep in mind that you must meet this requirements:
- A computer;
- The pwnagotchi must already be [`v1.5.5`](https://github.com/evilsocket/pwnagotchi/releases/tag/v1.5.5) properly configured;
- Perform a complete backup before making any modifications, including every file to be modified.

> **Important**
> The following steps were performed on a `Windows` computer using `PuTTY` as SSH client, `FileZilla` as FTP client and the pwnagotchi with a `Waveshare 2.13 V3 e-ink display` running on a `RPI0W`.
>> If you will use it in another fork or hardware, please be aware that you might need to adapt what is shown here

> **Note**
> If the folder doesn't specify which screen it was tested on, assume the sprites are for the `waveshare_v3` and similar sizes

> **Note**
> Anyone can contribute by making a pull request.
>> Don't limit yourself to just this article, feel free to create your own themes!

> **Note**
> This tutorial requires a minimum level of knowledge.

> **Note**
> If pwnagotchi updates automatically, this mod must be applied again.


## :heavy_exclamation_mark::heavy_exclamation_mark:  Disclaimer
> **Warning**
> From **roodriiigooo**: The content here is free for use, but it doesn't mean you can use it however you want. No author or contributor assumes responsibility for the misuse of this device, project, or any component herein. The project and modifications were **developed solely for educational purposes**.
> Any files, plugins or modifications of this project or original project found here should **not be sold**. In the case of use in open projects, videos or any form of dissemination, please remember to give credit to the repository ♥

> **Warning**
> Certain content may be protected by copyright, use with caution.


## :bookmark_tabs: Get Started

First, with the pwnagotchi connected to a computer in `MANU` mode, establish an SSH connection.

Login as root:
```console
pi@pwnagotchi:~ $ sudo su
root@pwnagotchi:/home/pi#
root@pwnagotchi:/home/pi# whoami
root
```
Navigate to root directory:
```console
root@pwnagotchi:/home/pi# cd /
```
Let's create two folders, one for backing up the files and another one to receive the custom faces:
```console
root@pwnagotchi:/# mkdir files-backup
root@pwnagotchi:/# mkdir custom-faces
```
Now let's navigate to the folder that contains the files we're going to modify:
```console
root@pwnagotchi:/# cd /usr/local/lib/python3.7/dist-packages/pwnagotchi/ui
```
Stop the pwnagotchi service
```console
root@pwnagotchi:/usr/local/lib/python3.7/dist-packages/pwnagotchi/ui# systemctl stop pwnagotchi
```
Here are the following files:
```console
root@pwnagotchi:/usr/local/lib/python3.7/dist-packages/pwnagotchi/ui# ls
components.py  faces.py  hw           __pycache__  view.py
display.py     fonts.py  __init__.py  state.py     web
```
Now run the following command to make a backup of the first file:
```console
root@pwnagotchi:/usr/local/lib/python3.7/dist-packages/pwnagotchi/ui# cp faces.py /files-backup/
```
Open the file using nano:
```console
root@pwnagotchi:/usr/local/lib/python3.7/dist-packages/pwnagotchi/ui# nano faces.py
```
Add these attributes to the code, resulting in the following:
```python
...
UPLOAD1 = '(1__1)'
UPLOAD2 = '(0__1)'
PNG = False
POSITION_X = 0
POSITION_Y = 40

def load_from_config(config):
    for face_name, face_value in config.items():
        globals()[face_name.upper()] = face_value
...
```
CTRL + O to save, CTRL + X to close file.

Now let's move on to the next file. Backup first, then edit:
```console
root@pwnagotchi:/usr/local/lib/python3.7/dist-packages/pwnagotchi/ui# cp components.py /files-backup/
root@pwnagotchi:/usr/local/lib/python3.7/dist-packages/pwnagotchi/ui# nano components.py
```
Locate this code snippet:
```python
class Text(Widget):
    def __init__(self, value="", position=(0, 0), font=None, color=0, wrap=False, max_length=0):
        super().__init__(position, color)
        self.value = value
        self.font = font
        self.wrap = wrap
        self.max_length = max_length
        self.wrapper = TextWrapper(width=self.max_length, replace_whitespace=False) if wrap else None

    def draw(self, canvas, drawer):
        if self.value is not None:
            if self.wrap:
                text = '\n'.join(self.wrapper.wrap(self.value))
            else:
                text = self.value
            drawer.text(self.xy, text, font=self.font, fill=self.color)
```
Now replace with:
```python
class Text(Widget):
    def __init__(self, value="", position=(0, 0), font=None, color=0, wrap=False, max_length=0, png=False):
        super().__init__(position, color)
        self.value = value
        self.font = font
        self.wrap = wrap
        self.max_length = max_length
        self.wrapper = TextWrapper(width=self.max_length, replace_whitespace=False) if wrap else None
        self.png = png

    def draw(self, canvas, drawer):
        if self.value is not None:
            if not self.png:
                if self.wrap:
                    text = '\n'.join(self.wrapper.wrap(self.value))
                else:
                    text = self.value
                drawer.text(self.xy, text, font=self.font, fill=self.color)
            else:
                self.image = Image.open(self.value)
                self.image = self.image.convert('RGBA')
                self.pixels = self.image.load()
                for y in range(self.image.size[1]):
                    for x in range(self.image.size[0]):
                        if self.pixels[x,y][3] < 255:    # check alpha
                            self.pixels[x,y] = (255, 255, 255, 255)
                if self.color == 255:
                    self._image = ImageOps.colorize(self.image.convert('L'), black = "white", white = "black")
                else:
                    self._image = self.image
                self.image = self._image.convert('1')
                canvas.paste(self.image, self.xy)
```
CTRL + O to save, CTRL + X to close file.

Now let's move on to the next file. Once again, backup first and then edit:
```console
root@pwnagotchi:/usr/local/lib/python3.7/dist-packages/pwnagotchi/ui# cp view.py /files-backup/
root@pwnagotchi:/usr/local/lib/python3.7/dist-packages/pwnagotchi/ui# nano view.py
```
Replace this one: 
```python
...
            'face': Text(value=faces.SLEEP, position=self._layout['face'], color=BLACK, font=fonts.Huge),
...
```
With that:
```python
...
	    'face': Text(value=faces.SLEEP, position=(config['ui']['faces']['position_x'], config['ui']['faces']['position_y']), color=BLACK, font=fonts.Huge, png=config['ui']['faces']['png']),
...
```
CTRL + O to save, CTRL + X to close file.

From this point on, the pwnagotchi is ready to display images instead of the default string.

## :page_with_curl: Configuration
From here, we will able configure the images for our custom Faces. So lets do that!

Prepare the files, there are a total of `25`. I use images of size `128x45`. To make it easier, name the files according to the facial expression or emotion:
> **_Default .png file names:_**  

~~~
LOOK_R, LOOK_L, LOOK_R_HAPPY, LOOK_L_HAPPY, SLEEP, SLEEP2, AWAKE, BORED, INTENSE, COOL, HAPPY, GRATEFUL, EXCITED, MOTIVATED, DEMOTIVATED, LONELY, SAD, ANGRY, FRIEND, BROKEN, DEBUG, UPLOAD, UPLOAD1, UPLOAD2, ICON, POSITION_X, POSITION_Y
~~~

Stop the pwnagotchi service, if its not:
```console
root@pwnagotchi:/# systemctl stop pwnagotchi
```

### :flower_playing_cards: Upload Images
Use `FileZilla` or any other method you know to upload your images to the `/custom-faces/` folder that was created earlier.

> **Note**
> If you don't have it, use one of my theme packages from [here](#art-themes-list)

Open the pwnagotchi's configuration file:
```console
root@pwnagotchi:/# nano /etc/pwnagotchi/config.toml
```
Locate this code snippet:
```python
...
ui.faces.look_r = "( ⚆_⚆)"
ui.faces.look_l = "(☉_☉ )"
ui.faces.look_r_happy = "( ◕‿◕)"
ui.faces.look_l_happy = "(◕‿◕ )"
ui.faces.sleep = "(⇀‿‿↼)"
ui.faces.sleep2 = "(≖‿‿≖)"
ui.faces.awake = "(◕‿‿◕)"
ui.faces.bored = "(-__-)"
ui.faces.intense = "(°▃▃°)"
ui.faces.cool = "(⌐■_■)"
ui.faces.happy = "(•‿‿•)"
ui.faces.excited = "(ᵔ◡◡ᵔ)"
ui.faces.grateful = "(^‿‿^)"
ui.faces.motivated = "(☼‿‿☼)"
ui.faces.demotivated = "(≖__≖)"
ui.faces.smart = "(✜‿‿✜)"
ui.faces.lonely = "(ب__ب)"
ui.faces.sad = "(╥☁╥ )"
ui.faces.angry = "(-_-')"
ui.faces.friend = "(♥‿‿♥)"
ui.faces.broken = "(☓‿‿☓)"
ui.faces.debug = "(#__#)"
ui.faces.upload = "(1__0)"
ui.faces.upload1 = "(1__1)"
ui.faces.upload2 = "(0__1)"
...
```

This snippet will be responsible for enabling our customization. If it doesn't exist, you can add it.

Add the new entries pointing to the folder where the images were placed, set the position where the custom Face will be displayed and set the activation flag to `True`.

```python
...
ui.faces.look_r = "/custom-faces/LOOK_R.png"
ui.faces.look_l = "/custom-faces/LOOK_L.png"
ui.faces.look_r_happy = "/custom-faces/LOOK_R_HAPPY.png"
ui.faces.look_l_happy = "/custom-faces/LOOK_L_HAPPY.png"
ui.faces.sleep = "/custom-faces/SLEEP.png"
ui.faces.sleep2 = "/custom-faces/SLEEP2.png"
ui.faces.awake = "/custom-faces/AWAKE.png"
ui.faces.bored = "/custom-faces/BORED.png"
ui.faces.intense = "/custom-faces/INTENSE.png"
ui.faces.cool = "/custom-faces/COOL.png"
ui.faces.happy = "/custom-faces/HAPPY.png"
ui.faces.excited = "/custom-faces/EXCITED.png"
ui.faces.grateful = "/custom-faces/GRATEFUL.png"
ui.faces.motivated = "/custom-faces/MOTIVATED.png"
ui.faces.demotivated = "/custom-faces/DEMOTIVATED.png"
ui.faces.smart = "/custom-faces/SMART.png"
ui.faces.lonely = "/custom-faces/LONELY.png"
ui.faces.sad = "/custom-faces/SAD.png"
ui.faces.angry = "/custom-faces/ANGRY.png"
ui.faces.friend = "/custom-faces/FRIEND.png"
ui.faces.broken = "/custom-faces/BROKEN.png"
ui.faces.debug = "/custom-faces/DEBUG.png"
ui.faces.upload = "/custom-faces/UPLOAD.png"
ui.faces.upload1 = "/custom-faces/UPLOAD1.png"
ui.faces.upload2 = "/custom-faces/UPLOAD2.png"
ui.faces.png = true
ui.faces.position_x = 0
ui.faces.position_y = 34
...
```

> **Note**
> **_1:_** Check if your installed plugins modify the 'faces'. If there are any, replace them with the equivalent custom image address. If you don't do this, the pwnagotchi may crash. The code looks like this: `ui.set('face', "(◕‿‿◕)")` or `view.set('face', "(◕‿‿◕)")`

> **Note**
> **_2:_** I recommend that you always use the same path (`/custom-faces/` folder) for your customization. That way, it becomes easier as you only need to replace the files!

CTRL + O to save, CTRL + X to close file.

Restart your device
```console
root@pwnagotchi:/# systemctl restart pwnagotchi
```

Enjoy!

## :writing_hand: How to Contribute?
> This is an entirely open project that accepts contributions via pull requests, your name will be placed as an author. If you have any questions, please open an issue.
1. Create a fork of this repository
2. Create your theme following the pattern of the ones already posted
3. Commit your changes in English
4. Include a brief summary of what was added
5. Submit your pull request

## :triangular_flag_on_post: Whats Next?
- [x] Update the docs for pwnagotchi `v1.5.5`
- [ ] Buy new hardware
- [ ] Mod for new forks (newer versions)


## :pill: Troubleshooting
- Check the log file, read and interpret:
```console
root@pwnagotchi:/# tail -f /var/log/pwnagotchi.log
```
- The logs may not be enough, so use:
```console
pi@pwnagotchi:~ $ sudo su
root@pwnagotchi:/home/pi# systemctl stop pwnagotchi
root@pwnagotchi:/home/pi# pwnagotchi
```
> With this command you directly run the pwnagotchi services and this way you can see what happens at run time, showing errors what does not appear in the log

- Restore the backup files that we placed in `/files-backup/` and try again

- If you don't have permission, try `chmod 777`

- Make sure that **all entries related to the plugins** are indeed in the `config.toml` file

- PM me [here](https://github.com/roodriiigooo/) 


## :star: Discover another projects
- [Fancygotchi](https://github.com/V0r-T3x/fancygotchi) by [V0r-T3x](https://github.com/V0r-T3x)


## :tophat: Thank You ♥
[Evilsocket](https://github.com/evilsocket/pwnagotchi) - [PersephoneKarnstein](https://github.com/PersephoneKarnstein) - [V0r-T3x](https://github.com/V0r-T3x) - [@demetrius_official](https://instagram.com/demetrius_official)
