# (ISC)² 
## https://www.isc2.org/

# OISF
## https://oisf.net/

# SNORT
## https://www.snort.org/
## docker run --rm -it --name snort3 -h snort3 -u snorty -w ~/snorty  ciscotalos/snort3 bash

# Suricata
## https://suricata.io/
## docker run --rm -it --name suricata --net=host --cap-add=net_admin --cap-add=net_raw --cap-add=sys_nice   shawoo/suricata:latest -i bond0
## docker exec -it suricata tail -f /var/log/suricata/eve.json

# SELKS
## https://www.stamus-networks.com/selks#selks

# ZEEK
## https://zeek.org/

