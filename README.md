# guilder-callback

A one-page forwarder for my personal budget app. After I approve access at my bank, open banking requires an `https://` return address. This page just forwards the browser to the app running on my own laptop (`http://localhost:4321`).

It stores nothing, loads nothing from elsewhere, and sends nothing anywhere. The one-time code it passes along is useless without a private key that never leaves my laptop.
