###[GotDeb](https://gotdeb.com)

Interactive bash script for VPS or Dedicated servers.
Build with low end systems in mind.
Requires Debian version 7.x or 8.x

###Installation
Run the script and follow the assistant:

`wget https://raw.githubusercontent.com/eunas/gotdeb/master/setup.sh --no-check-certificate`<br />
`chmod +x setup.sh && ./setup.sh`

###Script content

* Nginx
 * nginx Stable
 * nginx Mainline
 * Optional SSL support with self signed certificate or [Let's Encrypt](https://github.com/eunas/gotdeb/wiki/lets-encrypt)
* Blogs
 * Ghost
 * Wordpress
* [PHP](https://github.com/eunas/gotdeb/wiki/PHP-FPM)
 * PHP-FPM 5.6
 * PHP-FPM 7.0 (Debian 8 only)
 * HHVM
* MySQL 5.7 Server
* MariaDB 10.1 server
* [phpMyAdmin](https://github.com/eunas/gotdeb/wiki/phpMyAdmin)
* PureFTPD (FTPS enabled)
* OpenVPN Server (Works on NAT)
* [SoftEtherVPS (Works on NAT)](https://github.com/eunas/gotdeb/wiki/SoftEtherVPN)
* Squid3 Proxy Server
* sSMTP server
* Aria2 + webui
* Transmission BitTorrent Client
* [X2Go + xfce Desktop](https://github.com/eunas/gotdeb/wiki/Remote-Desktop)
* [Plex Media Server](https://github.com/eunas/gotdeb/wiki/plexmediaserver)
* [Observium](https://github.com/eunas/gotdeb/wiki/Observium)
 * Server
 * Client
* Linux Dash server monitor
* User Management
 * Add user
 * Delete user
 * List Users
* System Management
 * Remove unneeded packages and services
 * Install essentials packages
 * Update timezone
 * System tests
 * [Secure System](https://github.com/eunas/gotdeb/wiki/Secure-System)
   * fail2ban
    * Uncomplicated Firewall
     * Unattended Upgrades
 * Speedtest.net
 * Get OS Version
* About


###Disclaimer
Parts of the files are scripts found on various sites on the internet, and either modified or included.
Tested on a [LowEndSpirit](http://lowendspirit.com/) VPS with 128 MB Ram

###Credits
Xeoncross, mikel, Falko Timme, road warrior, Nyr and many others.