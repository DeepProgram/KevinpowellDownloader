
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
+ [BeautifulSoup (Python)](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
+ [Requests (Python)](https://requests.readthedocs.io/en/latest/)
+ [Python-Dotenv (Python)](https://github.com/theskumar/python-dotenv)
## Installation

Install **DailyChronicleServer** with python

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