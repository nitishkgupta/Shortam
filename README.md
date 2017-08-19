# Shortam
Shortam is a simple and light front-end shortcode framework built on vanilla JavaScript and CSS. 

Shortcodes are provided using shortcode.js (https://github.com/nicinabox/shortcode.js)

<b>Note - Shortam is currently under developement (don't use it now in production)</b>

# Features
1) Very Light
2) Currently in developement
3) More components coming soon
4) Custom shortcodes support
5) And much more

# Installation

<b>You can use Shortam framework either by CDN or by fetching it locally.</b>

For CDN paste this code just above ```</body>``` section of your template - 

```
<script src="https://cdn.rawgit.com/nitishkgupta/shortam/7dadd3c2/shortam.js" type="text/javascript"></script>
<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/nitishkgupta/shortam/6d99d347/shortam.css"/>
```

# Documentation

## Alerts

Use this code to add alerts -

```
[alert id="test" width="70" type="green" text="test"]
```

<B>Customisations -</b>

1) width="70" // Width of alert in percentage (in this case 70%)
2) type="green" // Theme of alert (Supported - green/blue/red/orange)
3) text="test" // Text to be shown inside alert box (can be html)
4) id="test" // Adds id to the object for extra usage (optional, leave blank for null)

## Buttons

Use this code to add buttons

```
[bt id="test" type="green" href="http://abc.com" text="Download" target="_blank"]
```
<B>Customisations -</b>

1) type="green" // Theme of button (Supported - green/blue/red/orange)
2) href="http://abc.com" // Target of link (Use #! for null)
3) text="test" // Text to be shown inside button (can be html)
4) target="_blank" // Target of link (Supported - all html target values)
5) id="test" // Adds id to the object for extra usage (optional, leave blank for null)

# Upcoming Features

1) Bootstrap 4 support
2) More custom elements
3) Much more

# License

MIT License
