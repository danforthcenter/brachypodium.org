# brachypodium.org

This repository contains the brachypodium.org website static build files.

After updating, to rebuild the site run the following on the webserver:

```bash
scl enable rh-ruby25 bash
jekyll build -d /var/www/brachypodium.org
```
