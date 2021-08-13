# License Plate Recognition (차량 번호판 인식기)

- Recognize location of plate
- Recognize characters in plate using [tesseract](https://github.com/tesseract-ocr/tesseract)

## Tesseract Lib install
$ sudo apt-get update
$ sudo apt-get install libleptonica-dev 
$ sudo apt-get install tesseract-ocr tesseract-ocr-dev
$ sudo apt-get install libtesseract-dev

$ sudo apt-get install tesseract-ocr-kor -y
$ tesseract --list-langs


**Click image to see [demo video](https://youtu.be/PpTl7xxGXh4)!**  
[![result.png](https://github.com/kairess/license_plate_recognition/raw/master/19%EC%98%A47777.jpg)](https://youtu.be/PpTl7xxGXh4)

## Dependencies
- Python 3+
- pytesseract 4.0
  - [kor.traindata](https://github.com/tesseract-ocr/tessdata/blob/master/kor.traineddata)
- OpenCV
- numpy
- matplotlib




