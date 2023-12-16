## Part A. Plan 

Setting: Outside during a concert.

Players: user, audience, performers, security

Activity: Performers are playing music, the audience is listening and reacting to the music, and the user is communicating emotions to other users/audience members and performers.

Goals: 

User - Give real-time feedback on personal experience of performance.

Audience - Enjoy the performance and visually see the heart rate responses of users.

Performers - Give the audience a good experience.

Security - Keep everyone safe.

![images](./images/Storyboard.jpg)

Feedback:

Originally for my storyboard, I did not include fingers on the hands of my users. This made it difficult for the people reviewing my concept to discern what the third panel of my storyboard was conveying. By adding fingers to my drawing, the context of the drawing became clearer.


## Part B. Act out the Interaction

On paper my interaction did not originally include any additional sensors. When acting out the interaction, it became clear that I would need some measurement to map the color to. This led me to the idea of using a person's heart rate to map a color to the device.


## Part C. Wizard the device

### First Attempt:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/BuCfwMebbIc/0.jpg)](https://www.youtube.com/watch?v=BuCfwMebbIc)

### Follow-Up

The new Goal is to have the median heart rate response display on the stage of performers:
![images](./images/Second_Attempt.jpg)

## Part D. Costume the device

### Costume 1

![images](./images/Costume1.jpg)

This first design has the user wear the device around their neck. Although this allows for a hands-free experience and allows the user to dance, it is susceptible to overheating.

### Costume 2

![images](./images/Costume2.jpg)

The second design allows for the user to wear the device on their back. It allows for a hands-free experience. It also allows others to view the device colors from the rear. This design is still susceptible to overheating.


![images](./images/Costume3.jpg)

In the third design, the device is worn on the head with a lantern shade. This allows the device to light up the lantern and is ideal for lowlight settings. The placement on the head makes the light more visible to others than in the previous two designs but introduces a risk of the device getting damaged. Additionally, the problem of overheating is not as great of an issue, although this aspect can still be improved upon. 


## Part E. Record

[![Prototyped Video](https://img.youtube.com/vi/zE4qMLqsH2k/0.jpg)](https://www.youtube.com/watch?v=zE4qMLqsH2k)


# Staging Interaction, Part 2 

### Feedback:

Tester mentioned a product that is similar to my concept. She told me that K-pop fans will carry lightsticks at performances to display their support for a certain group. Each lightstick has color schemes and a design specific to a particular group. Fans will use their lightsticks throughout all performances. Consequently, people can visually see where fans of a particular group are.

This insight gave me the idea to integrate a display in my design that shows the heart rate responses of sections of users, by location in the crowd. This gives a visual map of the "vibes" of the audience and allows users to move to parts of the crowd that better suit the experience they wish to have.

## Changes for the next iteration

I will slightly alter the goal of my device. For this iteration of my device, I integrated a display showing the average heart rate of users by section in the crowd. This is in addition to the wristbands for each user, that show an individual's heart rate through color. The wristband will also have the capability of haptic vibration to signal to the audience when the next performance is about to begin. An optional feature is to also vibrate the wristband, pulsing to the tempo of the music.

![images](./images/Storyboard2.jpg)


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YqRf_tA6ODs/0.jpg)](https://www.youtube.com/watch?v=YqRf_tA6ODs)

Interactions Depicted:
1. Lights on, mapped to audience heartrate. The crowd murmurs in anticipation.
2. Lights go out, the wristband vibrates. The audience knows the show is about to start and cheers.
3. Lights flicker as the performers enter the stage.
4. Music begins and lights pulse to the temp of the music.

This prototype video uses LEDs as a stand-in for the display on the stage. An Arduino Uno was used to program the individual LEDs. A DC motor was used to simulate the vibrations of the wristband. The color changes of the wristband are not shown in this prototype video, however, the first prototype video above depicts the same color-changing functionality of the wristband.
