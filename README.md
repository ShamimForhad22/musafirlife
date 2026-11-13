# MusafirLife

Front end design for MusafirLife.com, a visa processing, travel, and Hajj and Umrah agency serving customers directly.

## What is here

`index.html` is the whole site in one file. It has no build step and no dependencies apart from Google Fonts.

| Tab | Content |
| --- | --- |
| Home | Scroll driven flight: passport scanner, live tracking with WhatsApp updates, destinations, family and group booking, quotes and expiry reminders |
| Visa | Visit, tourist, business, student, medical and work visas for any country, with a process and common questions |
| Hajj and Umrah | Individual, family and group packages |
| Tickets and Tours | Air tickets, tour packages, hotels and extras |
| Track | File number lookup with a sample timeline |
| Order | Four step order flow with a live summary |
| Contact | Request form and office details |

## Run it

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Status

This is a design preview, not a working product.

- The order, tracking and contact forms do not send, store or charge anything.
- Text in square brackets, such as `[PRICE]` and `[YOUR PHONE NUMBER]`, is a placeholder to replace with real details.
- Traveller names and the passport shown are invented sample data.
- The destination scenes are drawn in code and can be replaced with real footage.

Going live needs the forms connected to WhatsApp, a payment gateway and a file tracking back end.
