<br/>
<p align="center">
  <a href="https://github.com/robot-jr/PersianHandwriting">
    <img src="https://www.linkpicture.com/view.php?img=LPic640c0897b021a2094989129" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Persian Handwriting detector</h3>

  <p align="center">
    A demo of a persian handwriting detection
    <br/>
    <br/>
    <a href="https://github.com/robot-jr/PersianHandwriting"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/robot-jr/PersianHandwriting">View Demo</a>
    .
    <a href="https://github.com/robot-jr/PersianHandwriting/issues">Report Bug</a>
    .
    <a href="https://github.com/robot-jr/PersianHandwriting/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/robot-jr/PersianHandwriting/total) ![Issues](https://img.shields.io/github/issues/robot-jr/PersianHandwriting) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

![Screen Shot](https://imgflip.com/gif/7e2yv0)

ترجمه فارسی در پایین صفحه
Although there are OCR spesifically designed for this purpose,
they wont work on handwritten Persian or Arabic language
or at least those i tried didnt work...

so i made this demo for anyone who might be interested in doing this project

for the sake of the demo to be easy
i trained a Yolov8 nano Object-detection model on custom dataset
but for a commercial use i wouldnt use this model

this demo should work fine with hand written Persian digits
and for word written Persian digits from 0 to 9.


دمویی از پروژه تشخیص اعداد دست نویس فارسی به عدد و حروف

آموزش داده شده روی دیتاست کوچک و دست سازی از اعداد فارسی


## Built With

Yolov8

## Getting Started

 just download the pretrained weight
and then pip install the ultralytics pip package!
and your done...

### Installation

1. !pip install ultralytics

2. Clone the repo

```sh
git clone https://github.com/robot-jr/PersianHandwriting
```

3. type this 

```sh
yolo detect predict model=path/to/best.pt source="https://ultralytics.com/images/bus.jpg" 
```

4. change the path to downloaded weight and source to your liking



## Usage

https://imgflip.com/gif/7e2yv0





## Authors

* **robot-jr** - *Likes ComputerVision* - [robot-jr](https://github.com/robot-jr/) - **


