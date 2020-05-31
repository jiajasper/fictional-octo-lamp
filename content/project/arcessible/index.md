---
title: "ARcessible  "
weight: 100
date: 2020-05-01T17:55:28+08:00
summary: "4-week Self-initiated Project on inclusive AR user experience design @idecourse"

categories: ["Augmented Reality", "WebXR","Aframe", "AR.js", "javascript", "Prototyping"]
---
This is an exploration project on making AR experience more accessible to the Vision Impaired People (VIP).

![](/images/arcessible/render.gif "")

Through this project I learnt about inclusive design and picked up new skills such as developing AR content on Web with WebXR and AR.js (Aframe).

Working closely with VIP was also an invaluable experience where I learnt that designer should be designing WITH the users as opposed to designing FOR the users.

### What is AR 
![](/images/arcessible/arcessible_1.png "")
![](/images/arcessible/arcessible_2.png "")

### Problem
![](/images/arcessible/arcessible_3.png "")
![](/images/arcessible/arcessible_4.png "")

### Current Barriers
![](/images/arcessible/arcessible_5.png "")

### How do VIP use their iphones?

![](/images/arcessible/arthur-using-phone.gif "I observed and studied how VIP use their phones")
The interaction can be summerized into audio instruction and three basic gestures: tap, double-tap and swipe.
![](/images/arcessible/arcessible_6.png "")


### User Testing and Insights

I then migrated the gestures that VIP use on their mobile phones onto a Web GPS AR app for the users to try; and got more insights on problems they encountered when using the AR application.

![](/images/arcessible/arthur-prototype-1.gif "")

![](/images/arcessible/arcessible_9.png "")

### User Needs

I consolidated my insights and listed out what VIP need in an AR interaction

![](/images/arcessible/arcessible_10.png "")

### AR-cessible Demo + Interaction Flow
By implementing WebSpeech API and Vibration API into AR.js - I was able to achieve accessible AR interaction where the haptic and audio act as the "sighted guide" throughout the experience.

{{< vimeo 423172741 >}}

![](/images/arcessible/arcessible_13.png "Logic and UX flow")
![](/images/arcessible/arcessible_15.png "Ticked all the boxes")




### Turning this interaction flow into a developer toolkit on WebXR platform
![](/images/arcessible/arcessible_11.png "The reason why I decided not to make an AR App specifically for VIP")
![](/images/arcessible/arcessible_12.png "")

I am currently working on perfecting the conponenet and plan to release this conponent on github for others to use when developing Web AR content with AR.js framework- stay tuned!