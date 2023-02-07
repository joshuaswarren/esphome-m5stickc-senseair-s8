# esphome-m5stickc-senseair-s8
Config to use an M5Stick C Plus with a SenseAir S8 CO2 sensor to report CO2 levels to Home Assistant via esphome

It took me some time to put all the pieces together from various forums and posts, so I'm hoping this will help save someone some time in the future.

Use the enclosed YAML file as a new config for the m5stick-c plus once you've adopted it in ESP Home. 

Connect the Senseair S8 via a Grove connector pigtail so that the RX and TX pins on the Senseair S8 are connected to pins G32 and G33 on the m5stick c plus. Connect the power and ground pin on the S8 to the power and ground pin on the same pigtail. Connect the pigtail to the m5stick c plus, power it up and program it and you should see a graph of CO2 readings on the display and in Home Assistant. 

You will also need to download the Open Sans font from https://fonts.google.com/specimen/Open+Sans and place the TTF files in config/esphome/fonts/ (you may have to create the fonts subfolder) in your Home Assistant filesystem. 
