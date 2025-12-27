# Chat Quote Form Simple

A lightweight WordPress plugin that adds a clean quote request form.  
Visitors enter their details and are redirected to a chat application with a pre-filled message they can review before sending.

Designed for small businesses that want fast, direct communication without storing user data.

## Features
- Simple quote request form via shortcode
- Redirects users to a chat app with a pre-filled message
- No database storage of user submissions
- Optional Google reCAPTCHA v2 to reduce spam
- Lightweight and fast
- No tracking or analytics
- Clean admin settings page

## Installation
**Via WordPress Admin**
1. Download the plugin ZIP.
2. Go to Plugins → Add New → Upload Plugin.
3. Upload the ZIP and activate.

**Manual**
1. Extract the plugin folder.
2. Upload to `/wp-content/plugins/`.
3. Activate from the Plugins menu.

## Configuration
1. Go to **Settings → Chat Quote Form Simple**
2. Set the destination phone number (international format, digits only)
3. (Optional) Enable Google reCAPTCHA by adding Site Key and Secret Key

## Usage
Add the shortcode to any page or post:

[chat_quote_form]

python
Copy code

Optional attributes:

[chat_quote_form title="Get a Quote" button="Open Chat"]

markdown
Copy code

## Privacy
- No user data is stored
- No cookies set by the plugin
- reCAPTCHA loads only if enabled

## Requirements
- WordPress 5.8+
- PHP 7.4+

## License
GNU General Public License v2.0 or later (GPLv2+)

## Author
GsmHelp Electronics Workshop  
https://www.service-evesham.uk

## Support
Please open an issue in this repository for bugs or feature requests.
