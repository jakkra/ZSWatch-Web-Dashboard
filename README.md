# ZSWatch WebBluetooth Dashboard
<p align="center">
    A Web Bluetooth Dashboard for easily viewing sensors readings etc. on https://github.com/jakkra/ZSWatch.
</p>
<p align="center">
  <img src="assets/screenshot.png" width=70%/>
</p>

## Testing locally
- Comment out below code in `index.html`
    ```
    if (window.location.protocol === 'http:') {
    window.location.href = 'https:' + window.location.href.substring(5);
    }
    ```

- Run `python3 -m http.server`

- Open http://localhost:8000/ in Chrome.

## Credits
Based on https://github.com/adafruit/Adafruit_WebBluetooth_Dashboard
