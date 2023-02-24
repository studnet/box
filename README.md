# box

This script helps you, if you are using Mail-in-a-Box and you do not have PTR record (reverse lookup) address for IPV6 and you want to upgrade your Mail-in-a-Box server.

This script temporarily disables ipv6 in Ubuntu and updates Mail-in-a-Box

NB! Manually reboot Ubuntu after using this script - otherwise some problems could occure in BIND, etc (at least it was before v60).
