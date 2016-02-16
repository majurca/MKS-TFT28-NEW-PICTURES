# MKS-TFT-NEW-PICTURES
New LCD pictures for 3d printer display from MAKERBASE-MKS
This repository contains a full set of customized pictures (91 files) for Makerbase MKS TFT Display.
In the LCD directory you can find the LCD files (*.bin), ready for upload to the display flash memory. Please, follow the Makerbase manual.
Also has been included the source files *.svg, if you want modify them. I used ìInkscapeî for create the pictures, a nice open source application.
The display allows 7 custom buttons; I configured this buttons with bed leveling features.
The 'config' file requires some configuration for Background colors and for the custom buttons.

cfg_background_color:0x000000

cfg_title_color:0xFFFFFF

cfg_state_background_color:0x800000

cfg_state_text_color:0xFFFFFF

cfg_filename_background_color:0xFF0015

cfg_filename_color:0xFFFFFF

cfg_printingstat_word_background_color:0xFF0015

cfg_printingstat_word_color:0xFFFFFF

cfg_BUTTON_3D_effects:0

moreitem_pic_cnt:6

moreitem_button1_cmd:G1 X5 Y5;

moreitem_button2_cmd:G1 X195 Y5;

moreitem_button3_cmd:G1 X195 Y195;

moreitem_button4_cmd:G1 X5 Y195;

moreitem_button5_cmd:G1 Z5;

moreitem_button6_cmd:G28 Z;

moreitem_button7_cmd:G28;
