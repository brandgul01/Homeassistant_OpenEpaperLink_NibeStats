# Homeassistant_OpenEpaperLink_NibeStats
Displaying values from Nibe F730 horizontally on a 2.9" ePaper display.

The text is in Swedish and the meaning is: Outdoor temp, Indoor temp, Hotwater temp, Charging temp.

Needed:

* GothamRnd-Bold.ttf in Media folder.
* A connection to your Nibe or other heating pump.
  I've connected mine to Homeassistant via the myuplink integration. https://www.home-assistant.io/integrations/myuplink
* The Weatherman template for showing the actual weather icon to the outdoor temperature. https://github.com/chunkysteveo/OpenEPaperLink-HA-Weatherman

After that, change the MAC-adress to your epaper-tag. 
Put the code in the automation YAML-editor. Run it.

    
