# Project Title

ISO Week of the Year for MicroLogix 1400

## Getting Started

Clone project onto your PC and open with RsLogix 500

### Prerequisites

Rockwell Automation's
RsLogix 500

### Installing

Develope from the cloned rss file or create your own and copy the ladder into the existing

In RsLogix 500 under "Controller Properties" in the explorer tree, select "Function Files, select the
"RTC" tab and press the "Set Date & Time" to start the Real Time Clock

## Data file collision considerations 

Make sure these Data Files are clear:
B3:52/0
B3:52/1
B3:52/2
N7:150
N7:152
N7:160
N7:161
N7:170
N7:171
N7:172
N7:173
N7:174
N7:174
N7:175
N7:176
N7:177
N7:178
N7:179

### Output Result

The correct ISO week of the year will be output into N7:152



### Links Referenced
ISO Week established according to these websites:
https://en.wikipedia.org/wiki/ISO_week_date
http://myweb.ecu.edu/mccartyr/isowdcal.html


## Authors

* **Luke Biller**  - [billerl](https://github.com/billerl)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

