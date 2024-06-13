QR Code scanner for login hotspot MikroTik
How to use
Add a button in login.html
<button onclick="window.location='https://ahmednasserhk.github.io/myqr/';">QR Code</button>
Add the following script to MikroTik via Terminal.
/ip hotspot walled-garden ip

add action=accept comment="Mikhmon QR Code Scanner" disabled=no dst-host=ahmednasserhk.github.io/myqr
Powered by hk4tech.com
