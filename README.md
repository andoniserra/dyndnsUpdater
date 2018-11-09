# dyndnsUpdater
OVH DYNDNS updater

This script updates your configured DYNDNS hosts on OVH.
You can get more information about creating them [here](https://docs.ovh.com/gb/en/domains/hosting_dynhost/)

The script uses the commands ```curl``` and ```dig```, make sure you have them installed in your system, ```dig``` is ususally included on ```dnsutils``` package.

There is not very much to explain about it, give execution permission, fill user pass and hosts, create a cron schedule and let it update the dynamic hosts automatically while you prepare a cup of tea.
