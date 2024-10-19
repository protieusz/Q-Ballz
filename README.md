# Q-Ballz
Q-Ballz, inspired by an anime with 2 trackballs, 2x CORE-A Mcus, 34 keys, 10 RGBs

# Description
Case design shape was inspired by a Neo Zeon prototype mobile suit, [Qubeley](https://gundam.fandom.com/wiki/AMX-004_Qubeley), one of the underrated MS from the Gundam Zeta series hence the name "Q-Ballz". Q-Ballz uses 2 trackballs as the previous OverLord, where this time the top ball is mouse movement and bottom is scrolling. The size of the custom keeb design is similar size to
Sachiel or the Excelsior.  Nice and compact for office use and wow factor with 10 RGBs on the vents and eyes. There might be some flaws on the "notches" that clips both top and bottom case together. Slight oversight but can make it work
with tiny DIY. Print at your own risk.

Oct 19, 2024: Q-Ballz is fully build and functional. All RGBs on both sides are fully working. Thanks to Drashna Jael're from fingerpunch discord for helping me out with QMK part and validation of my solder hack. Please see below pic for the hack details.

Oct 17, 2024: Q-Ballz fully build but only RIGHT side RGBs are fully working. Voltage and continuity all checks out. So I suspect it might be the QMK code.  Hopefully the QMK code can be fixed.
As for the effect of having set color RGBs for each sides, I tried using transparent colored plastic but it turns out that they are too thin and the RGB lights overpowered it. If someone can program where the RGBs on the right are always constant Blue for the circle vents while the Right eye is Pink, right vents pink while the rest of the LEFT side is pink. Anywayz Qubeley custom keeb mission accomplished.

Sept 18, 2024: PCB print will not be printed until October ish since my PMW3360 sensors and SA keycaps have not arrive yet. I am very excited for this build design.

# Disclaimer
This work is a non-commercial fan creation of custom keyboard case and PCB in the shape of Qubeley from the Gundam Zeta series. It is made out of love and respect for the Gundam Zeta series. All rights to Gundam and related content are owned by Bandai Namco Holdings Inc and its associated companies. The images, names, storylines and other elements of Gundam used in this work are the property of their respective copyright holders. Unauthorized commercial use is strictly prohibited. The license of this design reflects not for commercial use. Only the PCB files, QMK source will be open source. The case files due to copyright issues will not be open sourced.

Please print and use the case and PCB at your own risk. QMK code is derived from the QMK documentation and copy over from my OverLord build.

# Full Build
Oct 17, 2024

![IMG_3211](https://github.com/user-attachments/assets/de9f9f45-6352-4f11-8e68-2f5599638c53)
![IMG_3212](https://github.com/user-attachments/assets/95a890a5-0e45-4424-a7e1-dc23ce63500e)
![IMG_3225](https://github.com/user-attachments/assets/bac86274-ba73-4d51-bfdd-a5dbf08b8417)
I had to think outside the box by making the RGBs working on both sides. I edit the config.h RGB split settings to (0, 10) to have all the RGBs sourced from the RIGHT side from all the RGBs.
Then I solder the DOUT from the RIGHT side to the DIN of the LEFT for the RGBs and it worked! Shout out to Drashna Jael're from fingerpunch Discord channel for helping me out with QMK part and validation of my solder hack.
![IMG_3222](https://github.com/user-attachments/assets/598e3dc3-078b-40e8-9858-de94830123d9)
![IMG_3223](https://github.com/user-attachments/assets/e6f33705-e204-4bf4-8afb-2243b88beb1f)
![IMG_3224](https://github.com/user-attachments/assets/8854c01b-e248-4cf3-ba23-ee59bb044101)
![IMG_3209](https://github.com/user-attachments/assets/f474a0c6-d6d5-4988-9986-08aeeddf2f95)
![IMG_3208](https://github.com/user-attachments/assets/3d2a386e-9eb5-47a9-bc2b-fdfbbb358fa8)
![IMG_3207](https://github.com/user-attachments/assets/a8b72120-7601-4c49-898a-e23c3599ef5b)
![IMG_3206](https://github.com/user-attachments/assets/ea251b17-400e-4148-a2ab-f4b12a092601)
![IMG_3205](https://github.com/user-attachments/assets/fd53090b-0075-4154-971f-814dde1b4eec)
![IMG_3202](https://github.com/user-attachments/assets/7ed57b6d-e4a2-42b7-aa1b-e3fd75118260)
![IMG_3201](https://github.com/user-attachments/assets/a2d54511-30e9-4fa7-86d4-79e720ba365a)
![IMG_3200](https://github.com/user-attachments/assets/484714c2-c499-4bc7-aa5e-9a87afcd9b3c)
![IMG_3195](https://github.com/user-attachments/assets/7a717939-df08-4832-991c-cd5c7a9e0451)
![IMG_3081](https://github.com/user-attachments/assets/9ba4eff2-a0ae-443d-9c47-efba7db40b11)
![IMG_3057](https://github.com/user-attachments/assets/ef8ce847-d919-4762-8dbf-34830d23a424)
![IMG_3058](https://github.com/user-attachments/assets/fab2e2fe-87e7-4f82-a561-0162cf0b8657)
![IMG_2997](https://github.com/user-attachments/assets/a9fa5e6c-356e-4df8-aa6d-3f91c6799495)
![IMG_2996](https://github.com/user-attachments/assets/62b7c7d1-da3e-4fcf-9bbd-6fb2323910d5)
![IMG_2995](https://github.com/user-attachments/assets/1f0c1ea2-3bb6-4a04-87d8-e4057fb53b80)
![IMG_2994](https://github.com/user-attachments/assets/bad49670-51b8-4381-ab5d-02175b2efa55)
![IMG_2993](https://github.com/user-attachments/assets/037f17cd-7bba-48b0-8835-f702ccdbfe69)

# Renders

![Screenshot 2024-09-15 at 11 56 09 PM](https://github.com/user-attachments/assets/102ec68e-64e1-4807-a391-3a428c4114c7)
![Screenshot 2024-09-15 at 11 55 55 PM](https://github.com/user-attachments/assets/728c02e0-34e5-42b7-bdbf-cd8f7b6de592)
![Screenshot 2024-09-15 at 11 56 25 PM](https://github.com/user-attachments/assets/5397ba8c-584c-4776-a9ec-e5d1f23d3429)
![Screenshot 2024-09-15 at 11 56 35 PM](https://github.com/user-attachments/assets/d342e1f0-e7dc-4d11-9788-f9141f1fea21)

![Screenshot 2024-09-18 at 3 20 47 PM](https://github.com/user-attachments/assets/0360e0e7-4328-4884-8eca-0afa270354d1)
![Screenshot 2024-09-18 at 3 21 07 PM](https://github.com/user-attachments/assets/06cb01e0-4ad0-4ad6-9ef6-f6f5e8a8feb6)
![Screenshot 2024-09-18 at 3 21 19 PM](https://github.com/user-attachments/assets/ca48a3d8-c47b-4c28-99f4-522bdaaae1dd)
![Screenshot 2024-09-18 at 3 21 29 PM](https://github.com/user-attachments/assets/40a09148-8304-4dfa-84c0-6d9804fe93ec)

![Screenshot 2024-09-18 at 9 23 16 AM](https://github.com/user-attachments/assets/0c7e8b56-076b-448c-ba10-6614b99c8910)
![Screenshot 2024-09-18 at 9 23 30 AM](https://github.com/user-attachments/assets/711ae62b-3110-42c2-9638-b7bd4f9b016e)

![Screenshot 2024-09-15 at 4 52 59 PM](https://github.com/user-attachments/assets/5034bf88-672d-46f9-aad1-112d858c2a86)
![Screenshot 2024-09-15 at 4 45 36 PM](https://github.com/user-attachments/assets/4244cb27-7f79-42fd-84f2-546f11125681)
![Screenshot 2024-09-15 at 3 08 33 PM](https://github.com/user-attachments/assets/3356d69c-110f-445f-9ba0-6ebd593d0261)
![Screenshot_2024-09-15_at_12 41 15_PM](https://github.com/user-attachments/assets/0446f5d9-3845-49bf-9586-516341e97fa9)
![Screenshot_2024-09-15_at_12 41 02_PM](https://github.com/user-attachments/assets/f0bf30ac-1ea9-4337-b3fb-737c045a4b71)
![Screenshot 2024-09-15 at 11 39 33 AM](https://github.com/user-attachments/assets/f007f27b-6b04-46ae-9f79-dc47b394e307)
![Screenshot_2024-09-14_at_1 45 44_PM](https://github.com/user-attachments/assets/2530334a-58b7-4707-adb7-56468f0389f3)


# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

You are free to:

Share — copy and redistribute the material in any medium or format

Adapt — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.
Under the following terms:

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

NonCommercial — You may not use the material for commercial purposes.

ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Q-Ballz by ProtieusKeebs is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1)
