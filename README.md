<img src="docs/instabots_logo.png" alt="Showcase" height="100px">

## InstaBots
Do you want to make your instagram page famous? Try to use my bots to do it.

[![License](https://img.shields.io/github/license/fctaddia/InstaBots?color=0f9c98&label=License)](https://www.gnu.org/licenses/gpl-3.0.html)
[![InstaPy](https://img.shields.io/badge/Library-InstaPy-0f9c98)](https://github.com/timgrossmann/InstaPy)
[![Python](https://img.shields.io/badge/Build%20in-Python3-%233266a8)](https://www.python.org/)
[![Selenium](https://img.shields.io/badge/Build%20in-Selenium-%233266a8)](https://www.selenium.dev/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/78fcd1b1130a4a49a467228de3d65888)](https://www.codacy.com/manual/fctaddia/InstaBots?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=fctaddia/InstaBots&amp;utm_campaign=Badge_Grade)

Use InstaBots templates to grow your Instagram page.

### How to install InstaPy?
> **Tip:** Guide for Linux and macOS
#### Requirements
* Make sure you have at least **1GB of RAM**;
* Make sure you have a **CPU** of at least **1GHz**;
* **Firefox must be downloaded** because the Chromium drivers are not supported for the moment.

#### General dependencies
```sh
$ sudo apt update
$ sudo apt -y upgrade
$ sudo apt -y install unzip python3-pip python3-dev build-essential libssl-dev libffi-dev xvfb
$ sudo pip3 install --upgrade pip
$ export LANGUAGE=en_US.UTF-8
$ export LANG=en_US.UTF-8
$ export LC_ALL=en_US.UTF-8
$ locale-gen en_US.UTF-8
$ sudo dpkg-reconfigure locales
$ pip3 install --upgrade pip
```
#### Firefox
```bash
$ sudo apt install firefox
```
#### InstaPy
```bash
$ pip install instapy
```

> If you see an error telling you that something can't be uninstalled due to it being part of distutils, simply do  
`pip install instapy --ignore-installed`

### How to run InstaBots?
> Run InstaBots scripts without root privileges
```bash
$ python3 name_script
```
