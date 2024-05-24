**Status:** Maintenance (expect bug fixes and minor updates)

# mujoco-py-mask

This library is a modification of mujoco-py==2.0.2.5 that adds support for getting segmentation masks.

## Install

1. Obtain a 30-day free trial on the [MuJoCo website](https://www.roboti.us/license.html)
   or free license if you are a student.
   The license key will arrive in an email with your username and password.
2. Download the MuJoCo version 2.0 binaries for
   [Linux](https://www.roboti.us/download/mujoco200_linux.zip) or
   [OSX](https://www.roboti.us/download/mujoco200_macos.zip).
3. Unzip the downloaded `mujoco200` directory into `~/.mujoco/mujoco200`,
   and place your license key (the `mjkey.txt` file from your email)
   at `~/.mujoco/mjkey.txt`.

If you want to specify a nonstandard location for the key and package,
use the env variables `MUJOCO_PY_MJKEY_PATH` and `MUJOCO_PY_MUJOCO_PATH`.

Ensure that the specified cython version is installed
```bash
pip install cython==3.0.0a10
```
Then manually install
```bash
cd mujoco-py-mask
pip install -e .
```

## Credits

`mujoco-py` is maintained by the OpenAI Robotics team. Contributors include:

- Alex Ray
- Bob McGrew
- Jonas Schneider
- Jonathan Ho
- Peter Welinder
- Wojciech Zaremba
- Jerry Tworek
