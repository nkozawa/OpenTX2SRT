# OpenTX2SRT
OpenTX2SRT converts OpenTX log to SRT file. SRT file contains subtitle for video editing software.

## Setup and run
OpenTX2SRT is running under Python3 environment.
- Install Python3 environment, if you need.
  I am testing this program under Python 3.8.5 (MacOS).
- Download OpenTX2SRT.py and srtFormat.py
- pip install pysimplegui
- python OpenTX2SRT.py

## How to setup OpenTX log
Please refer Oscar Liang's web page.　
https://oscarliang.com/log-gps-coordinates-taranis/

I recommend you to set correct date and time on OpenTX setup menu.

## Usage
<img src='/images/OpenTX2SRT.png' width=300>
1. Click "Browse" button to select OpenTX log file (csv file). Sample log file is available at https://github.com/nkozawa/OpenTX2GPX/blob/main/samples/CRSF-2021-08-29.csv.
2. If you see correct OpenTX Log filename, click "Proceed" button.
3. Select log items (up to 10 items).
4. Adjust order of items and choose separator. Separators: No space, single space, double spaces, slash '/', bar '|' and new line '\n' are available. If you select new line '\n', you can get multiple lines subtitle.
5. Update timestamp, if you need. Timestamp field shows date and time of first log entry.
6. Select flight session from pull down menu. OpenTX log usually contains multiple flight sessions.
7. Click "ExportSRT" button to export SRT file.

## srtFormat.py
You can edit srtFormat.py to add new OpenTX log items and edit format.

## Sample video
[![Alt text](https://img.youtube.com/vi/uzMHITpwiQ8/0.jpg)](https://www.youtube.com/watch?v=uzMHITpwiQ8)
