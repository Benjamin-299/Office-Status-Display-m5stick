# Office Status Display: M5 Stick
Using an m5 Stack Stick C programmed with ESP home and Home Assistant to track the status of me and my partner who both work from home. 

## Overview:
My partner and I both work from home. My idea was to have a simple way to easily know if the other if free or busy at a quick glance. This grew into a bit more than just free/busy, but that is how these things go, right?
We both use the same model of Jabra headset with a charching dock/stand for work, and I had two m5 sticks laying around needing a use. With the addition of two m5 Unit Keys and hours (maybe days?) later, everything came to life!
I've called these status trackers, busy indicators, and a few other names. This project morphed from an initial attempt of using the m5stick as a remote for some smart itmes in my office and some reminiants of "room remote" may still appear. 

In the current state, these preform several primary functions. These are completed through a combination of ESPHome, Home Assistant, and some automation in Node Red (this could be done with HA native automation, or even as part of the esphome code, but I've not moved it yet). 

### Functions:
* Display a status icon for each user.
  * Working, Busy, Free, Music, Call
* Flashing LED to notify of status change, or other events.
* Exterior doors opened display on screens. 
* Input text helper can be displayed on the screens.


## Hardware:
* M5 Stack Stick C (SKU:K016-C) https://docs.m5stack.com/en/core/m5stickc
* M5 Stack Unit Key (SKU:U144) https://docs.m5stack.com/en/unit/key
* Jabra Evolve 2 65
  * Jabra Charching Dock/Stand

## Other Integrations used: 
* Google Calendar
  * Two calendars, one for each of us with an event titled 'work' reocurring each normal work day.
* HA Companion app
  * For reporting if music is being listened to, or if on a phone call
* Door Sensors
  * Open exterior doors are displayed on the screen.
* Input Text Helpers
  * Used to display a message on the screens.
 
## Details:
Well, this will get filled out someday (probably?). 
