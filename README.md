# **Forked from ashtrobe/grasswoex. Many thanks**

# **HOW TO GET GRASS USER ID USING ANDROID DEVICE [COMMUNITY EDITION]**  

Download and install [Kiwi Browser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser&hl=en).

Login to grass web and go to the dashboard, then open the Developer Tools in the Kiwi browser.

Go to the **Console** tab and paste this code:

> localStorage.getItem('userId')

If you can't paste, type `allow pasting` and press Enter, then paste the line above.

## **CONFIGURE TERMUX**

After Installing Termux, Make Sure You Allowed Storage Permission On Termux (device app) Settings. Or Run This Command In Termux -

> termux-setup-storage

**Install Python 3.10 -**

> pkg update && upgrade
 
> pkg install tur-repo
 
> pkg install python-is-python3.10

> pkg install -y rust binutils
 
> CARGO_BUILD_TARGET="$(rustc -Vv | grep "host" | awk '{print $2}')" pip install maturin

# **GIT CLONE THIS SCRIPT**

> git clone https://github.com/justmejay/grasscommscript.git

**CHANGE DIRECTORY TO SCRIPT FOLDER**

> cd grasswoex

**Install Requirements**

> pip install --upgrade pip

> pip install -r requirements.txt

# RUN SCRIPT
> python lite.py

