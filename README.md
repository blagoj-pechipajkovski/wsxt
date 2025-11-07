# wsxt - Web Serial XTerm

A simple combination of Web Serial API and XTerm.js that lets you comunicate with serial devices using just a chrome browser.

[Live Demo](https://zuzu.mk/public/wsxt/)

## Usage

- Open `index.html` or the live demo
- Click anywhere to open the port selection dialog
- Choose a port
- Done

## Limitations

- Has a fixed baud rate of 115200
- Only works on chrome/chromium based browsera because firefox does not support the web serial api
