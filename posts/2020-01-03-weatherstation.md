---
title: Weatherstation Project
published: 2020-01-04
---
In the autumn semester of 2020 we got the oppurtunity to make an weather monitoring station. The finalised project should be ready for use by a sailing club along the lake of Zurich.
## Beginnings
At the beginning of the semester we were provided with the hardware for the project: A "Raspberry Pi" and an 10 inch touchscreen display. Additionally we were given a software package to allow for easy importing of the weather data from the waterpolice of Zurich.
## Inheritance
By receiving a Python package for communicating with the data source, we sadly also inherited its flaws. Therefore our first task was repairing the provided software. We decided to create a copy of the package and to repair the package issue after issue, which resulted in a more complicated solution than a completly new code base but it did not require us to fully understand all functions and saved us a lot of time in the process.
After fixing the package we decided to make it publicly available for all other students.
## Monitor
When we eventually got the import working we could move on to the next step: programming our monitor. We almost instantaniously hit another bump on our road. Due to construction works at the main weather station they removed the precipitation data from their web service. We realized quickly that there was nothing we cloud do about that so we continued working knowing our final weather monitor would not be able to tell wether it was currently raining or not.
Luckily we still had the water and air temperature as well as wind data. With the use of the "dash" package we swiftly created a scrappy but working prototype. While we programming we simultaniously wrote our software documentation furthermore we provide initially setup instruction for the software besides a guide on how to put together the hardware parts we were given.
## OS
The default operating system for the Raspberry Pi is "Raspberr Pi OS" (previously "Raspbian") which we were not very comfortable with since we had previously only worked with "Ubuntu". Additionally "Raspberry Pi OS" was harder to install inside a virtual machine on our PC so we used "Ubuntu" for a big part of our development. Lucky for us the latest version of "Ubuntu" which was released in the middle of the semester. We expected big improvments in the development workflow since we no longer would have to work with two similar but everso different Linux distributions. So we almost immeadiatly made the decision to make the change to "Ubuntu" on the "Rapsberry Pi". However this also proved to generate some additional workload since we had to exchange almost every screenshot in our setup instructions due to the diffrent user interface but we never regreted the decision.
## Finish Line
In the beginning of January we got very close to a finished product. There are some small hidden possibilities for optimizations in the background process but the application works very well overall and covers all requirments stated in the project definition. We still have to create multiple presentations about our project so we will continue dealing with our project for the forseable future but the technical side is completed.
## Possiblities
The project in its current form is only a prototype. The user interface is functional but is hard to look at. As a part of the project we also conceived a design proposal based on the data we currently have access to. Speaking about data: The product can improved in the future when more data comes available like the precipitation.
Altough the are a lot of possibilites implementing the was not within the scope of this project. At same time 
