# HK-Projcts QR Reader
## QR Code scanner for login hotspot MikroTik

### How to use

1. Add a button in login.html
```html
<button onclick="window.location='https://ahmednasserhk.github.io/HK4tech-QR-Scanner';">QR Code</button>
```
2. Add the following script to MikroTik via Terminal.
```
/ip hotspot walled-garden ip
add action=accept comment="HK-Projects QR Code Scanner" disabled=no dst-host=ahmednasserhk.github.io
```

### Powered by hk4tech.com
