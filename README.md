# SalesAndDeck
How to print stuff from Sales &amp; Dungeons with your Streamdeck.

## Description
Sales & Dungeons is a free software for printing handouts, random generators and more for your tabletop-rpg sessions. In this little tutorial I will show you how to trigger the API of Sales and Dungeons to print directly with a push on your Elgato Stream Deck.

## What you need
* A working installation of Sales & Dungeons ([get it here](https://sales-and-dungeons.app/))
* Some generator of template
* A working printer that works with S&D
* An Elgato Stream Deck

## Web Request Plugin
* Download and install the Web Request Plugin from the Elgato Market: https://marketplace.elgato.com/product/web-requests-d7d46868-f9c8-4fa5-b775-ab3b9a7c8add

## Config the Streamdeck button
* Drag the Web Request item from the list to a button
* Choose a generator or a template inside of S&D you like to bind to this key and press the little (i) in the upper, right corner:  
![](https://github.com/Elfenspalter/SalesAndDeck/blob/main/scr1.png)
* Click on "Print Generator with config" dropdown
* copy the URL. Should look like this: http://127.0.0.1:7123/api/printGenerator
* Paste this URL in your Web Request button inside your Streamdeck under "URL".
* Copy the example POST body out of S&A under the URL and paste it into the Web Request button under "Body".
* Select "application/json" under "Content Type" within the Web Request button and select "POST" as "Method".
* That's all. You should be able to press the button on your Stream Deck and your printer should print. Have Fun! ^^

## More Screenshots
It should look something like this in your Elgato Streamdeck button:  
![](https://github.com/Elfenspalter/SalesAndDeck/blob/main/scr2.png)

## Support
If you have questions or need help, contact me (Elfenspalter) on the [S&D Discord](https://sales-and-dungeons.app/)
