# pihole
blocking lists

pihole -t is nice and simple but you can also do the following things to craft a better search query.

Display Only Blocked Queries (0.0.0.0)
sudo tail -F /var/log/pihole.log | grep 0.0.0.0

Display All Allowed Queries (Exclude Blocked)
sudo tail -F /var/log/pihole.log | grep -v 0.0.0.0