# Intro

Quick and dirty network discovery tool which does a recurisve walk of a network based on router ARP caches. Desgined/tested for/with Mikrotik devices, but can likely be easily modified for other devices (pull requests will be considered). 

# INSTALL/RUN

    go get -d ./
    go build snmp_arp_discover.go
    ./snmp_arp_discover -e "some_router" -c "public"