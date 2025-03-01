# esphome-lvgl-480-KC
For Esphome-lvgl-480x480 (Guition 4" ESP32 S3 LVGL Display Switch)

I'm not a developer, so I don't know any languages. It's just a hobby.

**Note, this is for reference, not for everyone.**

This is for esphome Korean users and does not fit the English language.


**Key Features**

1. Kitchen Device Control
2. Weather. Clockwork
3. Air conditioning control
4. Play the radio (If you have a media player)
5. Power consumption monitoring & warning

**User's Guide**

there's no image & fonts file here, which is a free image, but it's not included because it's copyrighted. 

You have to find and use this part on your own.

The weather included in the source has to use certain HA HACS components in Korea, so you have to change the weather sensor to one that suits you.

```
substitutions:
  name: "esphome-480-kc"  # Only lowercase letters
  device_description: ESPhome Craft 480 Kitchen Version
  
  # Switch
  light_switch: your entity #HA Light Switch entity id
  induction_switch: your entity #HA Induction entity id
  rice_switch: your entity #HA Electric rice cooker entity id  
  fan_switch: your entity #HA HA Can entity id  
  
  # Sensors
  indoor_temp: your entity # HA indoor temperature sensor entity id
  indoor_hum: your entity # HA indoor humidity sensor entity id  
  energy_sensor: your entity # HA energy meter entity id  
  presence_sensor: your entity # HA KC presence or motion detecter entity id  

  #devices
  aircon_id: your entity #HA Air conditioner entity id
  media_player: media_player.entity #HA KC media player entity id
  
  #Radio channel, For Korea User, if you want to change channels, Edit radio-480.yaml
  kbscool: "https://your_radio_address"
  itv: "https://your_radio_address"
  mbcfm4u: "https://your_radio_address"
  KBSClassic: "https://your_radio_address"
  CBSMusic: "https://your_radio_address"
  YTN: "https://your_radio_address"
  TBS: "https://your_radio_address"
  MBCFM: "https://your_radio_address"
  KBS1FM: "https://your_radio_address"
  CBSFM: "https://your_radio_address"
  TBN: "https://your_radio_address"
  SBSLoveFM: "https://your_radio_address"
  EBSFM: "https://your_radio_address"
  KBS3FM: "https://your_radio_address"
  KBSHappyFM: "https://your_radio_address"
  SBSPowerFM: "https://your_radio_address"

  # location
  latitude: "37" # your home latitude
  longitude: "126" # your home longitude  

```

**Shorts Video**

https://youtube.com/shorts/XZFKfd7OopM


 **Main Page**

![1000011548](https://github.com/user-attachments/assets/570fdb4c-a2e6-4d31-9287-bf9d1ef7c84f)

**Weather Page**

![1000011549 (1)](https://github.com/user-attachments/assets/0d29ec11-76e8-42fd-8909-c2c223f9237a)

**Menu Page**
![1000011550](https://github.com/user-attachments/assets/7c8ca264-15bd-4650-bcf9-f0ee383bbf14)

**Air Conditioner Page**
![1000011551](https://github.com/user-attachments/assets/918551b4-c10f-4428-bd87-f46f6940fc71)

**Radio Page**
![1000011552](https://github.com/user-attachments/assets/aa383f2f-268b-448e-b6a5-db4db3bc6706)

**Energy Page**
![1000011553](https://github.com/user-attachments/assets/506632d9-94cf-4228-bef2-9aad1051fa07)

**Setting Page**
![1000011554](https://github.com/user-attachments/assets/dd26e9dd-4942-4262-81b3-9e0c910f7a60)
