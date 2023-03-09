# flyingpages_shopware6

This Shopware 6 plugin integrates Flying Pages (https://github.com/gijo-varghese/flying-pages).

Flying Pages prefetch pages before the user click on links, making them load instantly.
It does this by checking which links are in the viewport or on what link a user is hovering on.

Within the plugin configuration you have the following options:
- Prefetch delay (in seconds): Start prefetching after a delay (in seconds). Will be started when the browser becomes idle, using requestIdleCallback. Default to 0.
- Ignore keywords: An array of keywords to ignore from prefetching. Example: '/logout','/cart','about.html','sample.png','#'
- Maximum requests (per second): Maximum requests per second the queue should process. Set to 0 to process all requests immediately (without queue). Default to 3.
- Hover delay (in milliseconds): Delay in prefetching links on mouse hover (in milliseconds). Default 50.

We have tested this plugin on Shopware v6.4.20.0. If you would experience any issues with your Shopware version, please contact us.
