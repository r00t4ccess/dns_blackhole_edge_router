# dns_blackhole_edge_router
Edge Router DNS blackholing

copy script to 
/config/user-data
chmod +x update-adblock-dnsmasq.sh
ln -s /etc/crontab.hourly/update-adblock-dnsmasq.sh /config/user-data/update-adblock-dnsmasq.sh
