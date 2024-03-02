# Flying Pages for Shopware 6

**This Shopware 6 plugin integrates Flying Pages (https://github.com/gijo-varghese/flying-pages) into your Shopware store. All credits for the javascript library used in this plugin go to Gijo Varghese (https://github.com/gijo-varghese).**

Flying Pages prefetches internal pages before the user clicks on a link, making them load faster.
It does this by checking which links are in the viewport or on what link a user is hovering.

Within the plugin configuration you have the following options:
- Prefetch delay (in seconds): Start prefetching after a delay (in seconds). Will be started when the browser becomes idle, using requestIdleCallback. Default to 0.
- Ignore keywords: An array of keywords to ignore from prefetching. Example: '/logout','/cart','about.html','sample.png','#'
- Maximum requests (per second): Maximum requests per second the queue should process. Set to 0 to process all requests immediately (without queue). Default to 3.
- Hover delay (in milliseconds): Delay in prefetching links on mouse hover (in milliseconds). Default 50.

## Shopware 6 administration plugin configuration
![Plugin configuration](https://i.ibb.co/tzNgyQ3/plugin-configuration.jpg)

## Prefetching demo
![Prefetching demo](https://i.ibb.co/VWD7LKQ/flying-pages-prefetching-test.gif)

We have developed this plugin for Shopware v6.4.20.0. If you would experience any issues with your Shopware version, please let us know.
Feedback is always welcome.
