# gulp-for-wordpress-dev

This code was originally from the Lynda.com course Wordpress: Building Themes from Scratch using Underscores by Morten Rand-Hendriksen

Edit package.json to update:
* git repo
* URL for reporting bugs
* homepage URL

Edit gulpfile.js
* change the theme name to match the one you're working with
* in the Watch everything section:
    * change the proxy to match the URL of the dev site so you can access it on other devices on the same network
    * add tunnel: '[tunnel-name]' so you can acess the site on external devices on the same network using http://[tunnel-name].localtunnel.me

Note: Browsersync doesn't work on tunnel in this configuration
