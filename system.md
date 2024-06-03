# System-Level URI Schemes

### Android System-Level URI Schemes

1. **Phone**
   - `tel:`: Opens the phone dialer with the specified number.
   - Example: `tel:+1234567890`

> **Note:**
> The `tel:` scheme works on both Android and iOS.

2. **SMS**
   - `sms:`: Opens the SMS app with the specified number.
   - Example: `sms:+1234567890`

3. **Email**
   - `mailto:`: Opens the email app to send an email.
   - Example: `mailto:example@example.com`

4. **Maps**
   - `geo:`: Opens the maps app at the specified coordinates.
   - Example: `geo:37.7749,-122.4194`

> **Warning:**
> Ensure that the coordinates are accurate to avoid misdirection.

5. **Web Browser**
   - `http:` and `https:`: Opens the browser with the specified URL.
   - Example: `https://www.example.com`

### iOS System-Level URI Schemes

1. **Phone**
   - `tel:`: Opens the phone dialer with the specified number.
   - Example: `tel:+1234567890`

2. **SMS**
   - `sms:`: Opens the SMS app with the specified number.
   - Example: `sms:+1234567890`

3. **Email**
   - `mailto:`: Opens the email app to send an email.
   - Example: `mailto:example@example.com`

4. **Maps**
   - `maps:`: Opens the maps app at the specified coordinates.
   - Example: `maps://?q=37.7749,-122.4194`

> **Danger:**
> Misuse of `maps:` scheme can lead to incorrect locations.

5. **Web Browser**
   - `http:` and `https:`: Opens the browser with the specified URL.
   - Example: `https://www.example.com`

### Example Code

#### Using System-Level URI Schemes in HTML

```html
<!-- Android -->
<a href="tel:+1234567890">Call Us (Android)</a>
<a href="sms:+1234567890">Send SMS (Android)</a>
<a href="mailto:example@example.com">Email Us (Android)</a>
<a href="geo:37.7749,-122.4194">Open in Maps (Android)</a>
<a href="market://details?id=com.example.myapp">Open in Google Play (Android)</a>

<!-- iOS -->
<a href="tel:+1234567890">Call Us (iOS)</a>
<a href="sms:+1234567890">Send SMS (iOS)</a>
<a href="mailto:example@example.com">Email Us (iOS)</a>
<a href="maps://?q=37.7749,-122.4194">Open in Maps (iOS)</a>
<a href="App-Prefs:root=WIFI">Open WiFi Settings (iOS)</a>
