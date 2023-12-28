# IDS-IPS

# SNORT
## docker run --rm -it --name snort3 -h snort3 -u snorty -w ~/snorty  ciscotalos/snort3 bash

# Suricata
## docker run --rm -it --name suricata --net=host --cap-add=net_admin --cap-add=net_raw --cap-add=sys_nice   shawoo/suricata:latest -i bond0
## docker exec -it suricata tail -f /var/log/suricata/eve.json
