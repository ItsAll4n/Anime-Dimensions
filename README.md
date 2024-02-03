# Anime Dimensions AFK

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Installation:
1) First download the latest version of the program.
2) Extract the files to a folder of your choice.
3) Ensure "Pytesseract" is installed. https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-5.3.3.20231005.exe
4) Copy the "C:\Program Files\Tesseract-OCR" folder into the folder your extracted the program into.
5) Ensure "AutoIt" is Installed. https://www.autoitscript.com/cgi-bin/getfile.pl?autoit3/autoit-v3-setup.zip

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Config guide:

Default config.json file:
```json
{
    "notify_amount": true,
    "disconnect_notify": true,
    "webhook_url": "https://discord.com/api/webhooks/xxxxxxxx/xxxxxxxxxxxxxx",
    "webhook_color": "0x000000",
    "current_amount": 0,
    "currency": "Gems"
}
```

### notify_amount:
Whether or not the webhook should notify you your amount.

### disconnect_notify:
Whether or not the webhook should notify you if you disconnected.

### webhook_url:
The url of the webhook.

### webhook_color
The color of the webhook.

### current_amount:
Your current amount of currency in AFK.

### currency:
What currency you are currently farming.
