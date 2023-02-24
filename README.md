# box

Script 

upgrade-miab-with-ipv6-disabled.sh

will help you, if you are using Mail-in-a-Box and you do not have PTR record (reverse lookup) address for IPV6 and you want to upgrade your Mail-in-a-Box server.

It temporarily disables ipv6 in Ubuntu and after that updates Mail-in-a-Box.

NB! Manually reboot Ubuntu after using this script - otherwise some problems could occure in BIND, etc, even if you do not need ipv6 in Mail-in-a-Box (at least it was before v60).
