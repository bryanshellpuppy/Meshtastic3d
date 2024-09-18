# Meshtastic3d
Meshtastic Cases and other useful tools.

WARNING!!!!!
<img src="https://github.com/bryanshellpuppy/Meshtastic3d/blob/main/images/polarity_.jpg">
Check to polarity of your connectors - ALL OF THEM. I have melted enough boards, manufatures do not follow a standard when it comes to knockoff boards vs lipo cells. Make sure you are checking before connecting anything.

Depending on your printer, you may need to print each piece from the large complete STL file. You will also want the Reset Button and the button cover.

Parts Used - You will need a surface mount momentary switch for the user button. Similar or same as a black solder on click button. (Picture soon)

Hot glue the screen into the front cover. You will want a I2C 1.3" 132x64 Screen found on Amazon.com or other site that has 4 pins. Take note of the pins on the screen and the RAK 19007 board because some screen manufactures switch the VCC and GRD pins. WARNING: Plugging in the screen incorectly can kill it for good. Pressing to hard on the corner of the bare screen can kill it for good. These are cheap for a reason but dont waste your money.

Part List:<br>
<br>
(1) Momentary Click Button <a href="https://www.amazon.com/QTEATAK-Momentary-Tactile-Button-Assortment/dp/B07VQF8P2Y/ref=sr_1_35?crid=3QXPMZCZFW7U3&dib=eyJ2IjoiMSJ9.ruRDh8Tj1a13VD8jEURoVdYwJALM4uKzH_7rLd2hTHDGjHj071QN20LucGBJIEps.BuLYkAof1QPW6H8Vvi6uUFRkbhGifbejgvPs6ggz-ik&dib_tag=se&keywords=momentary+click+button+solder&qid=1725504484&sprefix=momentary+click+button+sold%2Caps%2C195&sr=8-35">Link</a> (Sorry, wish you didnt have to buy 200 of them)<br>
(1) Meshtastic Starter Kit - RAK 19007 / 4631 <a href="https://www.amazon.com/RAKwireless-WisBlock-Meshtastic-Starter-RAK19007/dp/B0CHKZJK9C">Link</a><br>
(1) RAK GPS Module with Antenna <a href="https://www.amazon.com/RAK-Wireless-RAK12500-Location-Module/dp/B0D33SFFGF/ref=sr_1_1_pp?crid=1SRTJUF1G9GOR&dib=eyJ2IjoiMSJ9.DZK1JnRMqSDaeN28Lb7iRZDTh7R93AEZbbrvWeAi7txX5VICSqbEqhsIMaJHye-m2UXts2cZGJGishPJZcRMrbf1uNctm89gK_qrHsVAHrP_IEKp8L2AGYs5uFISrolUhoIF3MzIezF2H8oSG-GjO7mQciol72UeobdIUi80q_i4PGi7co4vp5KMmolRrw7KyO7V8K74-9iXXAXYj3lW149s2tkaKg2l8IMbscy07c4.I8Z1-mIsX4EKdM90RHzpctskwEvLfeWifFc_VVFXhA0&dib_tag=se&keywords=rak+gps&qid=1725504168&sprefix=rak+gp%2Caps%2C177&sr=8-1">Link</a><br>
(1) 1.3" I2C OLED SSD1106 Display - Because the price can varry, I recommend checking Amazon for the best deal. Just note the pins VCC and GND. You may need to adjust your wires.<br>
(1) 915Mhz SMA cable to replace the small panel antenna you get in the kit, if it dosent have one already. <a href="https://www.amazon.com/Wishiot-Antenna-915MHz-Connector-Lora32u4/dp/B0BX2NFM9B/ref=sr_1_6?crid=121AMCDQNJ3MH&dib=eyJ2IjoiMSJ9.SNiFV78Qg3VZ6bR3M_wWj50T--Y_f4LtEoTRuckI1qb0YJY1ZGWaz7sqFf3gVF3CQUFTcddSbnXiCtKsnP4--gCG2i9Y0Y_-0WvN51UCuBfxmL4bFgqx5VqYLUkP2tB7pizFcXofpGF9sLvhVVxGtQP2QURgzZjgmlogNFF-QlP6tt9EQs1imFkDvLpQhsJ6jsrfUGdz13cuhBmi0qVnZiZbY7uU4aTwzb6hNxfxktc.H1YckMJ099bG6m_tq2R8rTA3oNG-ECW6rlswZI0PZl4&dib_tag=se&keywords=915+mhz&qid=1725504225&sprefix=915+mhz%2Caps%2C149&sr=8-6">Link</a><br>
(1) 915Mhz Antenna that fits the oreientation of your cable. - Inclueded in the link above<br><br>
(1) 2000Mah Lipo Battery pack with correct battery connection (or solder one onto the battery) <a href="https://www.amazon.com/1800mAh-battery-Rechargeable-Lithium-Connector/dp/B07BTTKM8H/ref=sr_1_18?crid=3CH3P2PN4S7PG&dib=eyJ2IjoiMSJ9.1bpVYctOhbIV6FY2OjNeO-TLfi-ERuJ7WiU6OG98ccjTP9bSViGC7Aku6hIzehvYfJzYeY6ffphZamrYZglYnfOgN5Md_TdTvCPKIly9inZkKZMkL1uzBSNp5_cvac6pOBdhhaHzuIgYR44Vk1Htpf7DYyXMoJfvHh0Sz-k4CloNC4NPRaQueLIiJK8BlJ49fa1o8nCkv6Hz_oh9n-5-C2mNYZ0CDnrPyw6F7ds0ita54RORRvfMJjLRqM6z89Qo8PW7SB6-LGrBHjGOPO4brjyXZSmIxXIf87dBE3V1n9g.smowABqF3aGO6kBVAu6nXsvaYrYNa5uYz_v2yzI9qWM&dib_tag=se&keywords=2000mah%2B3.7v%2Brechargeable%2Bbattery&qid=1725504327&sprefix=2000mah%2Caps%2C150&sr=8-18&th=1">Link</a> <br><strong>WARNING - CHECK POLARITY OF THE WIRES BEFORE CONNECTING. YOU MAY NEED TO SWITCH THE PINS TO MATCH THE RAK BOARD.</strong><br><br>
(1) 4 Pin Cable from display to RAK - JST XH 2.54 4 pin <a href="https://www.amazon.com/Sets-2-5-4-Connector-200mm-Female/dp/B01DUC1S14/ref=sr_1_14?crid=3C7KIY9T0MWL5&dib=eyJ2IjoiMSJ9.m15Ofd1u28AxlS0oDE_26sSwMRmm3YCizdEwpzx_ZqdYqpKedjzbA_qH8OdX4g407TVE4mrZ02iE2T3oqHHfk6nf7-Vd5H9dgUo8FA8W35S3NcDDAyfvLicfJ-b0vd7hgfztyEAMLcXaE-mLGsbIXrUcBTCA0OLT_VQBN7nlCVhRpLAMOwrCfZguJgn9Ihw2Didlf2Da4C8_NYiSvRod_nYj2Rwgtnshyv4YIzinoFPCs2oD4yc_RY-3EsIdNpclGbAdPyqMpRpwpwYS8kiShR40JINCWSlBrQjCzoY-sps.YBjUvPVivV7FtEEv76qWv5IV1GZev987I1v6Ts16ObM&dib_tag=se&keywords=4+pin+cable+connector&qid=1725504635&sprefix=4+pin+cable+connector%2Caps%2C168&sr=8-14">Link</a><br>
(1) Set of 2 wires to solder on to the button. You can scavange these from any project ;)<br>
(4) M3 20mm bolts <a href="https://www.amazon.com/mxuteuk-Metric-Screws-Suitable-Printer/dp/B0C7ZPZ214/ref=sr_1_1?crid=2IVZVQBHFFK37&dib=eyJ2IjoiMSJ9.CImQszsKZiemhuBPMvECRdS4a3z6uJ3kU97PMinpZu3_UgLXAEhcP8n8ErWp6G-4-YVX0J57Fp-KIztVKUFs57fC249vvOvRvagSodTXBNBPuCbB2WKJfGMeP1Y7tz8oNlB_6_Kpsw9zuCPkFv6TUgm9qsuigXwl8ecsz2B09jbRsrYbPLidHMiMiVOfuczhOMivBP_DV17cHEtCgNSCkEyxNLaVv67n8vJN9UzgdsU._fXwz0MDmDa-d0TluoLVdgydwWkfjC0R_YvDKBQQXx4&dib_tag=se&keywords=M3+20mm+bolts&qid=1725504727&sprefix=m3+20mm+bolts%2Caps%2C165&sr=8-1">Link For Nuts and Bolts</a><br>
(4) M3 Nuts<br>
<br>
<br>
If you want to make it look nice inside, you can connect a piece of right angle 2.54mm header pins to the I2C part of the board. This keeps the 4 pin cable connector tucked out of the way and makes removing the screen easy. <a href="https://www.amazon.com/Uxcell-a15062500ux0349-Single-40-pin-Breadboard/dp/B01461DQ6S/ref=sr_1_1?crid=1BBGFJ3TCZ990&dib=eyJ2IjoiMSJ9.wOjS79Xdz7AeZPKKXuBESL69Tsjj6Wo_kRf7Ld3b9feFQnz-_k_N9f4A1mG1uTvs_eelDZi99pFkMHq1RTp_nIVI5sWbjQFetu1tFaGb0idC8PKLNmTkzr5uoGBqLHJM-7KEdtuKAKbyOpJ5Szg9hfgseSbckdSek4y0zqpOSQE1KLxe5NZRAkWPqRSp_T74QOCJ2UEhu7RyE4vMIuvQlnjFLcReY0i6gYYxSvmf768.Pzc3dpPVY_zxAwG-9eCtX-jc8FMW7ed4OCQqvisnJZI&dib_tag=se&keywords=right+angle+bread+board+pins&qid=1725504866&sprefix=right+angle+bread+board+pin%2Caps%2C173&sr=8-1">Link</a><br><br><br>
I do alot of custom cables just to try and build a production ready item for Etsy someday, but you can solder all the parts and skip the connectors. Do not glue the button cover on until you make sure its working. I did this and tossed an entire print.

Assembly Pics:
Note: I hot glue my screen so I removed the posts for the screws as I switched to a larger screen from the .96" used in this guide made by <a href="https://www.printables.com/@TonyG">TonyG</a> on Printables. Alot of the base of this work comes from what he did, but I modified and rebuilt some of the model to allow the bigger screen and some internal changes that came with a wider device. You could print his smaller design, but the larger, easier to read screen will not fit. When there is support for a larger screen such as the 1.54, I will update my design to include that as an option. I dont want to repost TonyG's work on the smaller screen. Also you could go thinner on the back cover but on some of my nodes I put a 3000mah batter in there and needed the extra depth. I just use some thick double sided clear tape to hold the batter in place so if I want I can upgrade to the larger battery at any time without a reprint.<br><br>

Screen Wiring - Note the location of VCC and Ground. It may be different on your screen.
<img src="https://github.com/bryanshellpuppy/Meshtastic3d/blob/main/images/583944124df42389fef9086c5ece1834378ca0b8.png"><br>

NOTE STEP 5 IS NO LONGER NEEDED. USE THE USER BUTTON TO CONTROL THE GPS ON / OFF. ITS IN THE CODE NOW.


<img src="https://github.com/bryanshellpuppy/Meshtastic3d/blob/main/images/RAK_Assembly.jpg">
