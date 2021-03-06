# MailHops Thunderbird and Postbox Plugin
[www.MailHops.com](https://www.mailhops.com)

<img src="https://www.mailhops.com/images/logos/logo.png" alt="MailHops logo" title="MailHops" align="right" />

MailHops is an email route API. It does a few things:

1. Returns a route an email took based on the Received header IP addresses
1. Returns a map an email took based on the Received header IP addresses
1. Shows the weather of the sender when you provide a [DarkSky](https://darksky.net) API key
1. Will tag and mark messages as Junk if from a Country you don't like
1. Performs DNSBL check on messages

### MailHops Message View

<img src="images/screenshot-thunderbird.png" alt="MailHops Message View" title="MailHops Message View" style="border: 1px solid #777;" />

### MailHops Route Map

<img src="images/screenshot-map.png" alt="MailHops Route Map" title="MailHops Route Map" style="border: 1px solid #777;" />

### MailHops Options

<img src="images/screenshot-display.png" alt="MailHops Options" title="MailHops Options" style="border: 1px solid #777;" />

### MailHops Dashboard

<img src="images/screenshot-dashboard.png" alt="MailHops Dashboard" title="MailHops Dashboard" style="border: 1px solid #777;" />

### Editing the code
1. After you make changes you can run the [build.sh](build.sh) script
1. Open Postbox or Thunderbird and goto Tools->Add-ons and "Install Add-on From File..."
1. Choose mailhops.xpi from build script

```sh
$ chmod +x build.sh
$ ./build.sh
```

### MailHops API
- [https://github.com/mailhops](https://github.com/mailhops)

### Download
- [Download this plugin from Mozilla](https://addons.mozilla.org/en-US/thunderbird/addon/mailhops/)
