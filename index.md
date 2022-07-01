# Weather Indicator with IOT
The Weather Indicator detects weather changes and displays them through Leds. It shows a different color for each weather type (rain, snow, cloudy, clear). I chose the Weather Indicator as my project because I thought it'd be fun to have a hands on part and a coding portion. I was also really interested in Leds. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Joyce | Gunn | Building Objects | 9

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLXiQj1MWQhIhCNVRcwi0w5HXhJ392SdoWkd8fB8ecZwu0IvRmG5ZyONZIaklXKNpEhq_cw7kPQk2gWz8mrEpeYjM4v5zCyVF43M2UlpFJfUI4sHNMkyZ-fZOqBTtTlsmmWLaBDUVA0RcpV7d4Hgm-77=s1528-no?authuser=0)
  
# Final Milestone
My final milestone was designing the lid of the weather indicator. I used a CAD software called Fusion 360. My vase was different than the model vase. Mine tapered slightly at the end, so I had to adjust my measurements. I also struggled with hollowing out and connecting the shapes together. I also added modifications because I wanted to add an LCD screen to display the weather. The LCD screen changes to each weather change. When it's rainy, it says "It's Raining!", when it's cloudy, it says "It's Cloudy!" etc... Then, I assembled the rest of the parts and I finished my Weather Indicator!!

[![Milestone 3](https://res.cloudinary.com/marcomontalbano/image/upload/v1656690359/video_to_markdown/images/youtube--reM7xQbXg2k-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=reM7xQbXg2k "Milestone 3")

# Second Milestone
My second milestone was setting up IFTTT to monitor weather changes. I used a function called Weather Underground and then I connected it to Particle so it would know when to call my weather functions. Then, when I tried to call an action field, things started to get complicated. I was supposed to call the function "Led" so that the weather indicator's led's will work. I realized that in the step before, I didn't properly transfer my code to the arduino. I transferred half of it, but not the functions. For some reason, my first code wasn't transferring into my arduino so I had to copy my original code into another IDE before using that IDE as my "new" code. 

[![Milestone 2](https://res.cloudinary.com/marcomontalbano/image/upload/v1656690327/video_to_markdown/images/youtube--cq-RLXnrfU0-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=cq-RLXnrfU0 "Milestone 2")

# First Milestone
My first milestone was setting up the electronic part of the Weather Indicator. I used a breadboard, with lots of wires to connect to an particle and an LED ring which is controlled by a Particle Photon. For each row in the breadboard, if you have a wire in it, the whole row will automatically have the current. I mainly used male to female wires, because the breadboard and LED ring are female connections and the particle is a male connection. It was a bit difficult because the wires would often tangle up. Also, I soldered the wires connecting to the LED ring so they wouldn't slip. Then, I had to connect the arduino to Particle through my computer. I coded everything on Particle's Web IDE and then I transferred the information to the particle.

[![Milestone 1](https://res.cloudinary.com/marcomontalbano/image/upload/v1656603824/video_to_markdown/images/youtube--zqWfRrb0rYo-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=zqWfRrb0rYo "Milestone 1")

# Starter Project
My starter project was the TV Be Gone project. The purpose of this project is to build something that can wirelessly turn off a TV. The TV Be Gone Project is about putting certain parts, wires and sensors together. At the bottom, the black button is the on-off button. Then next to it, the 3mm LED blinks once you turn it on. The 10K resistor protects the LEDs from receiving too much voltage and current. The R1, R3 resistors help limit the flow of electricity to provide a specific voltage. The 220uF electrolytic capacitor is the C2 capacitor and the C1 is a ceramic capacitor helps to reduce voltage pulsation. The resonator controls the whole system. The transistors on top help and protect the LEDs and send signals to the TV. They prevent the LEDs from receiving too much voltage and current. Finally, the LEDs on top send an infrared signal to the TV to turn it off. 


[![Starter Project](https://res.cloudinary.com/marcomontalbano/image/upload/v1656008291/video_to_markdown/images/youtube--hRQQzCJszn4-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=hRQQzCJszn4&t=6s "Joyce W Starter Project")
