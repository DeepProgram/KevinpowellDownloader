
# Kevinpowell.co Course Downloader


## Overview
This is an CLI application to automate the download [kevinpowell.co](https://courses.kevinpowell.co) course
## Feature

**Download Automation**
- Insert the course link and press enter


## Motivation
The motivation behind creating and maintaining **Kevinpowell Course Downloader** is that a lot of people can not watch videos online whenever the want. This also reduce the bandwidth usage.
## Requirements
+ [FFMPEG](https://www.ffmpeg.org/)
    - **Arch Linux / Majanro**
        ```bash
        sudo pacman -S ffmpeg
        ```
    - **Debian**
        ```bash
        sudo apt-get install ffmpeg
        ```
+ [BeautifulSoup (Python)](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
+ [Requests (Python)](https://requests.readthedocs.io/en/latest/)
+ [Python-Dotenv (Python)](https://github.com/theskumar/python-dotenv)
## Environment Variables

To run this project, you will need to add the following environment variables to your **.env** file

`COOKIE="__podia_session=%1655Fdsf4fsdfsdf489sdf4sd4f9sd4f98sd4f4sdfsdgfosdfgspofdjpjjspdjfpjsfpjf"`

**Get this __podia_session Cookie Value**
- Install [Edit This Cookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg) chrome extension
- Login to your [Kevinpowell.co](https://courses.kevinpowell.co) account
- Select Edit This Cookie extension and get the **__podia_session** value


## Installation

Install **Kevinpowell Course Downloader** with python

```bash
  git clone https://github.com/DeepProgram/KevinpowellDownloader.git
  cd KevinpowellDownloader
  pip install -r requirements.txt
```

## Usage

```py
python main.py -u "https://courses.kevinpowell.co/view/courses/conquering-responsive-layouts"
```
![App Screenshot](https://raw.githubusercontent.com/DeepProgram/KevinpowellDownloader/screenshot/download_command.png)


![App Screenshot](https://raw.githubusercontent.com/DeepProgram/KevinpowellDownloader/screenshot/downloaded_file.png)


![App Screenshot](https://raw.githubusercontent.com/DeepProgram/KevinpowellDownloader/screenshot/help_command.png)
