# Changelog

## v0.0.2

- Added a header contaning links;
- Added a title;

## v0.0.3

- Removed unnecessary `print.css`, as it's possible to open the QR code image in a new tab (or locally, after having downloaded it), and print it.
- Fixed the double QR codes that would pop up instead of one.
- Added some more styling to buttons.
- In `style.css`, all absolute units (px) are now converted to relative units (em & rem).
- Replaced the `qrcode.js` with an uglified version of it (`qrcode.min.js`).
- Added the option to add the encryption type.
- Removed unnecessary font weights.
- Turned autocomplete off for the input fields.
