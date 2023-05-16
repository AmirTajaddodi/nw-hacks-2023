# nw-hacks-pill-dispenser
Project submission for nwHacks 2023. Smart pill dispenser that reminds the user to take their medication, dispenses their pills. The pill dispenser also keeps track of the expiry dates and the temperature and humidity conditions. 

- The pill dispenser provides an auditory reminder to take medication/supplements at scheduled intervals
- It dispenses one pill at a time using a sonar sensor to detect the pill that falls into the container and prevent further dispensing of pills
- It displays temperature and humidity for constant moderation of weather conditions
- Displays expiry date so you’ll never forget about it

How it works:
1. Carefully insert pills into the tube, and input medication information on the website (name, expiry date, recurrence, optimal temperature & humidity)
2. When the time comes to take your medication, the servo motor will shake the tube so that ONE pill comes out, and stops when the sensor detects the falling pill within the tray.
3. As soon as the pill falls, the timer will begin for the next time the user must take their pill.

Also see website: https://github.com/tczg/PigeonPill

**Contributors:** Tony Gu (https://github.com/tczg), Emily Song (https://github.com/emilysxng), Gursharan Singh 
