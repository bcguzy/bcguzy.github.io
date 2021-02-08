---
permalink: /
title: 
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my website! This website is primarily to show off my personal projects. This homepage features a few highlighted projects. For a full listing of my previous projects, go to the completed projects tab. If you need more information about me or would like to request a resume, email me at [bcguzy@gmail.com](mailto:bcguzy@gmail.com) or [add me on LinkedIn](https://www.linkedin.com/in/bcguzy/)
## AVR Thermometer
![A picture of the 4809 Thermometer](https://github.com/bcguzy/bcguzy.github.io/blob/master/images/4809_thermometer.jpg?raw=true)    
This project was made as part of my Embedded Systems class and uses the ATmega 4809 coded with the AVR instruction set. This project involved using many parts of the ATmega 4809 microprocessor including the analog to digital converter for the temperature sensor, the timer/counters on the chip for interrupts, and of course utilizing the I/O pins. I also learned about reading and using documentation for microprocessors, their instruction sets, and basic components for the circuit. Subroutines provided from the manufacturer were researched and used for multiplication and division of the ADC results to convert them to degrees Celsius. This project made me much more confident in working with embedded systems and using technical documentation.

# Summer 2020: APIs and Hardware Applications
I spent the summer of 2020 learning how to use APIs. I love the idea of taking the vast amounts of information from the internet and applying it to something new or interesting. I started with the basics of a simple weather website and worked my way up to a plant sprinkler that can adapt to the weather.
## WiFi Button Sprinkler
![A gif of the project in action](https://github.com/bcguzy/WebButton_Sprinkler/raw/master/media/ezgif-7-719b561e50d5.gif)  
[Source Code and Documentation](https://github.com/bcguzy/WebButton_Sprinkler)  
This project is a button hosted on the local network that can be used to turn on and off a sprinkler remotely. I used an ESP8266 NodeMCU, the motor shield for the ESP8266 for easy power delivery, a 9 volt battery for a power source, and a 9v solenoid valve to control water flow. This project helped me get familiar with connecting the ESP8266 to WiFi and successfully powering the solenoid valve using the motor shield. All of this knowledge was used in my next project, the WiFi Weather Sprinkler.
## WiFi Weather Sprinkler  
![a picture of the project's board](https://github.com/bcguzy/Weather_Sprinkler/blob/master/photos/wiring.jpg?raw=true)  
[Source Code and Documentation](https://github.com/bcguzy/Weather_Sprinkler)  
This was my main project during the summer and combined the knowledge gained from previous API and hardware projects this summer. It takes rainfall data from the OpenWeatherMap API to determine if a plant needs more water that day or not. I leveraged the deep sleep functionality of the ESP8266 to have a timed wake every morning so that it did not use any unnecessary power throughout the day.  
## [Responsive Weather](https://bcguzy.github.io/Brandons-Responsive-Weather/)
![weather image](https://bcguzy.github.io/images/weatherExample.PNG)
[Source Code and Documentation](https://github.com/bcguzy/Brandons-Responsive-Weather) - [View Website Here](https://bcguzy.github.io/Brandons-Responsive-Weather/)  
I started this project as an experiment and exploration into web design and APIs. The site uses bootstrap CSS, openweathermap API for the weather data, and owfont for the icons. During the process of making this website, I learned a lot about using REST APIs, responsive web design, JavaScript, and HTML. My knowledge of APIs and HTML gained from this project helped me with future projects in the Summer.



