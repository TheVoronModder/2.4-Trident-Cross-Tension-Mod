![Pirmary Pic](https://github.com/user-attachments/assets/dc7ca6a8-09c6-4975-8559-19e3c5a4f084)

>[!note]
> This mod incorporates a lot of other user mods, for 
credit and naming see the bottom of the page.

## What is this wild mod pack?

It’s pretty straightforward. AWD systems have their belts routed in a criss-cross fashion. This makes Input Shaping a breeze, as it aligns the X and Y belt tensions (belt shaping) and resonance (input shaping) almost perfectly.

Utilizing Kraken stepper motors from Omranello (https://github.com/D3vil-Design/Kraken-Stepper), it makes a lot of sense to apply a criss-cross belt tension pattern to the standard rear motor drive system, which only utilizes 2x stepper motors. (of course you can always upgrade those 2004 mah's for 2804's however the real performance is hidden within the Kraken steppers)

The front left tensioner is flipped to mirror the stock (OEM) right tensioner, and vice versa for the other.

>[!note]
>all the voron logos are mirrored for the reverse belt tension mod

Check the image below for belt tensioning details.

>[!tip]
>simplified belting
![belt simplified](https://github.com/user-attachments/assets/baba219d-0545-463d-8179-0bed9623a5d6)

>[!tip]
> both belts
![belt](https://github.com/user-attachments/assets/3878a689-6910-41f6-a36f-7c29e7d43deb)

>[!TIP]
>after many months of testing I have formed a hypothesis: Standard voron belt tensioning has more pressure on the Y axis causing Belt Shaper and Input Shaper values to be much lower than X axis, you can see this in the above image of belt routing where the light blue lines are the tension path and the motor / tensioner they are connected to on the same belt path plane.

## The proof:

>[!important]
>the below input shape images show how close each axis is, yes I have some thing loose in there.
>
>X axis is MVZ @ 12,500
>
>Y axis is MZV @ 11,200
>
>with a 2 wheel drive VORON!

![Input Shaper results](https://github.com/user-attachments/assets/e618fbe5-b9d2-4033-875d-de94af0874db)


## now to the mods!


>[!important]
>Trident:

![60b7e8f3-c73f-4614-8d32-be10a8db5811](https://github.com/user-attachments/assets/cb81e3ca-8e09-4396-a213-9e9da9c6ee82)






>[!IMPORTANT]
> Rear AB mounts modified from HartK's pin mod found below:
> [website] https://github.com/VoronDesign/VoronUsers/tree/main/printer_mods/hartk1213/Voron2.4_Trident_Pins_Mod
>
>Tensioner mod is a hybrid of Ramalama and Clee's Beefy Tensioners found below:
>Ramalama [website] https://github.com/Ramalama2/Voron-2-Mods/tree/main/Front_Idlers
>
>clee's beefy tensioners [webiste] https://github.com/clee/VoronBFI
