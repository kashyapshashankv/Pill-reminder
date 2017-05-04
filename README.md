# Pill-reminder using Arduino and GSM

Pill reminder is a device which will reminde the user when to take their pills.

I have used Arduino Pro mini,GSM module(SIM800), Bluetooth module(HC-05), IR Sensors and DS3231 RTC module.

The user need to set time at which he/she is instructed to take medicine using an app which i made using MIT app inventor. Since the model has both GSM and Bluetooth module User can select whichever way of connection he wants like he can use SMS service as well as Bluetooth. Once time is set, it will be compared with current time(using RTC) and accordingly user will get Reminder using LED, buzzer and SMS. Once the person opens the box IR module will sense it and LED, Buzzer and SMS will not be send further. All the compartment of the box works independently from each other. As we have GSM module even the doctor can send the instruction if he/she wants to do some modification in timing of pills.



@kashyapshashankv
