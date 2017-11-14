# Space Heart Attack

Space Heart Attack is part of a class project which aims at using an individual's heart rate in real time to play a game. The system consists in a hardware device wirelessly connected to a smartphone running a game app. Here we present the main features as well as the first prototype.

## Motivations

The heart rate is a relatively easy-to-measure parameter that provides useful information about an individual's health status. Given its clinical applicability, it is used to assist in the diagnosis of common cardia diseases like arrhythmia and myocardial ischemia. As a team of biomedical engineers -and in the context of the Medical Device Design course at NTU, Singapore-, we decided to explore on how to achieve an accurate measurement and monitoring of the heart rate, developing also an innovative and original approach to display this parameter: Space Heart Attack.

## Concept

ADAPTAR TODO:::
A smartphone app guides the user through several recipes, coming from different parts of the world and having diverse levels of difficulty. Step by step, the user receives feedback about his or her cooking technique in a fun and interactive way, allowing him or her to quickly be able to cook delicious food.

A small device is attached to the cooking pan or pot, and measures several parameters related to the food being cooked, such as temperature, CO2, or vibrations. This data is sent over Bluetooth to the smartphone, which analyses them, and convert them into an intuitive feedback. The device is removable and discreet, so it does not bother the user.

<p align="center">
	<img src="doc/Technical_slide.jpg" width="750"/>
</p>

## Hardware Device

ADAPTAR TODO:::
Main features:
* Three sensors measuring temperature, CO2 concentration, and acceleration
* Status LEDs
* Battery powered
* Optimized power consumption: BLE communication, low-power microcontroller, carefully selected sensors...

Early prototype:
* Arduino UNO
* Dallas DS18B20 thermocouple 
* InvenSense MPU-6050 IMU
* Bluetooth HC-05 module
* Green, Orange and Red LEDs controlled by the smartphone

## Mobile App

ADAPTAR TODO:::
Main features:
* Various recipes (levels) accessed on a remote database
* Online account management
* Score and achievments sharing with friends
* Real-time communication with the device
* Feedback such as: "increase/decrease temperature", "give a stir" or "food is burning"

The early prototype was developed for Android with Unity game engine and featured one full recipe. It is already available for feedback on [Google Play Store](https://play.google.com/store/apps/details?id=com.SevaneGames.RetWork).

<p align="center">
	<img src="doc/App_ui_2.png" height="400">
	<img src="doc/App_ui_1.png" height="400">
</p>

## What comes next

ADAPTAR TODO:::
Additional features that could potentially be implemented:
* Allow the user to rate recipes and suggest improvements, use machine learning to update the database based on the score given by many users
* Advanced feedback to the user using fuzzy logic
* Automatic ingredients ordering to local groceries with home delivery

## Awards NOO---> Achievements INSTEAD

ADAPTAR: This project won the second place of the GovTech Singapore Hackathon 2017, a 3-days event focused on idea development and implementation.

## Credits

* Hardware and firmware development: Ang Zhi Ting, Avneet Kaur, Han Jun Guang, Nikita Jacob, Sun Xue, Zhang Xinxin, Zhang Yimei	
* 3D design and printing: Ignacio Albert Smet
* Game app development: Alexis Pomares Pastor
