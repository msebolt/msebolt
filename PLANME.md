
- servi.us (servius.me) [📚📚](xn--zt8ha.ws) (with user data)
  - servos repo
  - current state, project doc editor with toolbox *mattdown.com*
  - personal tactician with ai editor?
  - strack studios

Richard Matt
May 18, 2017 Lake Erie Plane Crash
Mackinac "Drowning Pool"

# strack

order (seals, box/bag with logo, sticker, collector's business cards, toy) (version/OR/etc.) to ship...

https://www.usps.com/business/web-tools-apis/documentation-updates.htm

https://www.alibaba.com


Roland 776 manifest 1776?

news statue

@media print { .breaker{break-after:always;} }

[site check](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fmattdown.com%2F)

|Expense|Receipt|
|-|-|
|server (5/2021)|mail attachment?|

[property](https://www.craigslist.com)

Vapor barrier, insulation
https://www.homedepot.com/p/Sika-50-lbs-Self-Leveling-Underlayment-517004/207086698

Bathroom remodel

http://www.keyfobprogram.com/2020-buick-enclave-remote-programming/

Driveway seal, Gravel/ concrete crawl space studio

Bamboo Toilet paper

8/9, 11:10am

For news, see [CSPAN](https://www.c-span.org/), [BBC](http://feeds.bbci.co.uk/news/rss.xml), [Gutenberg](http://www.gutenberg.org/wiki/Main_Page), [Wikipedia](http://www.wikipedia.org/wiki/Special:Random) *virtual news feed... enter name?*

keys (house, car, etc.)

https://fonts.google.com/icons?icon.query=user

https://developer.authorize.net/hello_world.html

"person=man/tribe/monster/animal"
"place=land/town/exterior/interior"
"thing=car/plane/ship/alien/abstract/plant"
...
"element=red(fire),orange(rock),yellow(city),green(forest),blue(water),purple(air/mountain),black(future),white(past)"

custom= tribes, french-indian war, international, state

Capacitor (super)

neoprene suit, 

## README

**Version 1.04**

[download script](https://dralun.com/dralun/bitos/build.sh)

*Requires BIOS access to boot from USB, use ESC, DEL, and/or a particular Function key on boot.*

How to build strack (with servOS)

1. Build a hardware box...

1. Download [Arch Linux](https://www.archlinux.org/download) and use `dd` to image an USB.
```
wget...
dd if=arch_linux.iso of=/dev/sda status=progress
```

1. Boot from USB, then run the build script. Reboot.
```
#iwctl --passphrase passphrase station device connect SSID #optional, wireless
pacman -Sy --noconfirm wget nano
wget https://ur.land/serv/build.sh
chmod +x build.sh #set options...
./build.sh
```
   
1. Use SSH *optional*, get IP with `ip addr`, then set router and forward ports to:
|Port|Function|
|-|-|
|80|http|
|443|https|
|2525|mail|
|587|tls|

1. Run site, use backup/restore *optional*:
```
./build.sh site #adjust processors, use 'lscpu'
```

## PLANME

double bios logo... device distribution with ar, eSim

https://gist.github.com/heyalexej/cc6c97b1ea42736b3ff7

https://www.ami.com/products/firmware-tools-and-utilities/bios-uefi-utilities/

fullscreen/file folder text editor/terminal/keyboard

import subprocess

command = 'sudo add-apt-repository ppa:ondrej/php'
process = subprocess.Popen(command.split(), stdout=subprocess.PIPE)
output, error = process.communicate()

pyotp
py torch?

argnot? Google still has maps(addresses), ads, pull mek
...https://wiki.openstreetmap.org/wiki/Using_OpenStreetMap_offline
env MOZ_USE_XINPUT2=1 firefox
...about settings? 

year.day of year-time (hover to show month/day of week)

Stryker font, dad's artitect...
(multi-lingual catch phrase, braille) translation?

escrow? (add drawing/signature), 

> [corp](https://ccfs.sos.wa.gov/#/Dashboard) attachment?
> [license](https://secure.dor.wa.gov/)
> [copyright](https://eco.copyright.gov)
> [patent/trademark](https://www.uspto.gov/) 

[Linode](https://cloud.linode.com/linodes), [site check](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fmattdown.com%2F)

|Expense|Receipt|
|-|-|
|server (5/2021)|mail attachment?|

(portfolio)
- Google? [domain](https://domains.google.com) [email](https://www.dynu.com) [emain](https://dcc.godaddy.com/domains/?isc=cjc1off30) *name.com? Tucows.com?* 
- [Chase](https://www.chase.com)
- [Alibaba]()
- ShutterStock, search for susanitah...

slide deck! [property](https://www.craigslist.com), treeop business account?

## How to install servius

Configure domains using **Google** [domain](https://domains.google.com), **Dynu** [email](https://www.dynu.com), and **GoDaddy** [emain](https://dcc.godaddy.com/domains/?isc=cjc1off30) *name.com? Tucows.com?*

Setup router with the following ports:

|Port|Function|
|-|-|
|80|http|
|443|https|
|2525|mail|
|587|tls|

Install certs using: (also configure haproxy)
```
certbot certonly --standalone -d ${site}, cp -r /etc/letsencrypt/live/${site} data/${site}
sudo -E bash -c 'cat /etc/letsencrypt/live/$DOMAIN/fullchain.pem /etc/letsencrypt/live/$DOMAIN/privkey.pem > /etc/haproxy/certs/$DOMAIN.pem'
```

Build a strack unit, attach an M.2 drive (enclosure) and run `servius/servos/install.sh old`. Deploy unit.

Go to site and setup user/password. Repeat build strack units for each additional and use add IP function.

### Additional commands

```
fdisk -l #show drives
df, ls -a, du -xhS | sort -h | tail -n15 #show file/folder info
lscpu #show hardware info
grep -R "term" #search

ip addr show #show network connections
ping google.com -c 2 #test network
```
