---
title: "NIKU - The Clingy Bot"
weight: 5
date: 2019-10-01T17:55:28+08:00
description: "NIKU is a clingy and attention-seeking robot companion who tracks down and headbutts human feet non-stop."

categories: ["Physical Computing", "Arduino", "Prototyping"]
featuredImage: "/images/niku/gizmo-1.jpg"
---
NIKU is a clingy and attention-seeking robot companion who tracks down and headbutts human feet non-stop.
{{< admonition note "About this project" >}}
3-week Physical Computing Project @idecourse
{{< /admonition >}}


## Intro



NIKU has a soft white body made of silicone to contain its electronic hardware. It resembles a juicy and meaty bun - hence the name NIKU (ニク: meat in Japanese). Through NIKU's playful interaction, we hope to fill the human psychological need of being wanted in this ever isolating society.

## Mechatronics

##### Hardware
• Dome-shaped silicone soft case

• 3D printed dome-shaped hard case and base plate

• 1 Arduino

• 2 DC motors attached to 2 3D printed wheels seperately

• 1 Ultrasonic sensor

• 1 Motor H-bridge

• 1 Ball pen tip

![](/images/niku/gizmo-2.jpg "Exploded render")

##### Interaction

![](/images/niku/gizmo-gif.gif "NIKU rotate to search for a target")

![](/images/niku/gizmo-gif-1.gif "NIKU slowly moves towards your foot")

![](/images/niku/gizmo-gif-2.gif "NIKU charges at your foot!")


##### Arduino void loop () logics

• Distance reading > 80cm: NIKU rotates to the right to search for targets around it.

• Distance reading < 80cm but > 5cm: NIKU moves forward with one wheel driving forward at a time.

• Distance reading < 5cm: NIKU charges forward and then reverse.

![](/images/niku/niku-hardware-info.jpg "Arduino Circuit")

## Ideation
![](/images/niku/gizmo-moodboard.jpg "Moodboard and Sketches")

NIKU's form design and internal hardware engineering were revolved around three key behaviours that we narrowed down to - clumsy, clingy and annoying.

![](/images/niku/gizmo-exp.jpg "Rapid and efficient experiments on moving mechanics and forms")

We made rapid prototypes to test out different sensors (IR, Ultrasonic, Thermal) and to experiment with a variety of moving mechanics (vibration, airflow, 2WD, 3WD, 4WD). We also concurrently tested out different orientations for the physical appearance of the robot.

## Prototype

![](/images/niku/gizmo-hardware-iteration.jpg "We teared down a toy 3WD car and soldered our own parts onto it for a rapid working prototype")

Throughout experiment phase, we made lots of look-like prototypes to mimic specific movement/looks that we desired. Those prototypes were indeed insightful but not enough for us to visualise how different parts of NIKU would work together.

To efficiently test out form factors and key functionalities, we hacked a 3WD toy car and soldered our own parts and arduino board onto it. We also made cardboard casing to visualise internal hardware placement.

Our working prototype worked like a charm and assisted us in finalising design and 3D printing parameters.

## 3D Printing + Resin + Assembly

![](/images/niku/gizmo-making.jpg "Silicone making with 3D printed mold and hardware assembly")

This stage was a ton of fun and learning! We made NIKU's silicone case with a custom 3D printed mold. With the help of workshop technicians, we were able to pull off NIKU's squishy look.

My teammate Kiwa did an amazing job at parametric modelling - all of our 3D printed parts fit nicely and hardware assembly was a breeze to complete.


## Dyson School WIP Show Feature

![](/images/niku/gizmo-show.jpg "NIKU was one of the six year 1 projects to be featured in IDE year 2's Work in Progress Show at Imperial College London.")
![](/images/niku/gizmo-gif-3.gif "NIKU and I on demo day!")
