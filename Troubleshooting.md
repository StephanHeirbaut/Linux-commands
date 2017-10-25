# Troubleshooting

## Volg Het TCP/IP van beneden naar boven

### Fysieke en data link laag

- Bekabeling
- Switched en NIC LED's
- ip link voor instellingen NIC's

### Internet laag

- ip a voor adressering
- ip r voor default gateway
- ping tussen hosts en GW/DNS
- dig voor query DNS
- nslookup voor query DNS
- getent voor query DNS

### Transport laag

- sudo systemctl status [service] is de benodige service aan het draaien?
- sudo ss -tulpn op de juiste poort of interface?
- sudo firewall-cmd --list-all laat de firewall het verkeer toe?

### Applicatie laag
- sudo journalctl -f -u [service] check de log bestanden (error en access)
- config file syntax
- programmeurs
