# Setup on Ubuntu

`sudo apt install python3-pip`

`python3 -m venv ~/venv/qmk`

`~/venv/qmk/bin/pip install qmk`

`~/venv/qmk/bin/qmk setup`

`mkdir ~/qmk_firmware/keyboards/one-quaker`

`cd ~/qmk_firmware/keyboards/one-quaker`

`git clone https://github.com/one-quaker/qmacropad9/`

`~/venv/qmk/bin/qmk compile -kb one_quaker/qmacropad9 -km default`

`~/venv/qmk/bin/qmk flash -kb one_quaker/qmacropad9 -km default`
