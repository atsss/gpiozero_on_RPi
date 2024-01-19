# gpiozero_on_RPi
## Development environment
- Raspberry Pi CM4
- Raspberry Pi OS - Bullseye/Bookworm
- [IO board](https://www.waveshare.com/cm4-io-base-b.htm)
- [boot/config.txt](https://github.com/atsss/RPi_configs/blob/main/bookworm/imx219.txt)

## Docs
- GPIO Zero
> https://gpiozero.readthedocs.io/en/stable/index.html

## How to run script
1. Set up vitualenv (Optional)
```
virtualenv --system-site-packages -p /usr/bin/python3 venv
source venv/bin/activate
```
2. Install packages
```
pip install -r requirements.txt
```
3. Run script
```
python test.py
```
