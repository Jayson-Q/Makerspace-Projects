# RFID Jukebox

## Idea
A RFID jukebox made for a Christmas present for my wife. She had mentioned she had never received a mixtape when she was younger.

What started as a mixtape ended as a jukebox and a whole lot of albums and mixtapes!

## Parts used
- Custom Jukebox
- LilyGO TTGO T-Display ESP32
- Adonno Tag Reader (https://github.com/adonno/tagreader)

## Coding

### ESPHome
The display is made with "pages" within the display component, I built a page to display the song, artist and album name. Additional pages were creating as 
It then displays these pages in a sequence with which change on either a button press or on an interval delay before showing the next page.

### Home Assistant
Sensors are made to export the information using the Template option to conform to the latest best practice. My Home Assistant is setup with seperate files for each aspect to give granularity, and the file structure reflects this, however can be easily adapted.

## Construction
The TFT display on the Lillygo board is very clear and bright with easy visability. Some fonts like Arial can be problematic due to typesetting issues.

## Pictures / Video

![RFID Jukebox](https://user-images.githubusercontent.com/68851601/218323503-29c4ed33-b1b4-4bc6-b1c5-d3aa8cf0d70a.png)
