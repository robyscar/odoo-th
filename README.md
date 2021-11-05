Odoo Docker with Thai localization
----------------

Dockerfile for creating [Docker image](https://hub.docker.com/r/poonlap/odoo-th/tags?page=1&ordering=last_updated) using Odoo 14.0 (current year 2021) or other versions such as 13.0 with Thai language. (l10n_thailand, Thai localization) immediately


How to use
--------
```
$ git clone https://github.com/poonlap/odoo-th.git
$ cd odoo-th/docker
$ docker-compose up
```
Open a browser to the URL.
```
http://localhost:8069
```
[more details](docker/)

<!-- prettier-ignore-start -->
  [//]: # (addons)

Available addons (add from [OCA l10n-thailand](https://github.com/OCA/l10n-thailand))
----------------
addon | version | summary
--- | --- | ---
[th_address](th_address/) | 14.0.1.0.0 | A helper module for automatic importing address data and other settings.
[th_address_vat](th_address_vat/) | 14.0.1.0.0 | Auto-completion of the address when the tax ID is provided.

[//]: # (end addons)
  <!-- prettier-ignore-end -->
