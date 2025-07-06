# WEINET – Listas de bloqueo personalizadas

Este repositorio contiene archivos de seguridad filtrados manualmente por Ing. Angie Jara responsable de la red de WeiNet para ser usados en MikroTik.

## Fuentes confiables utilizadas:

- BlocklistProject – Lists (https://github.com/blocklistproject/Lists)
- StevenBlack hosts (https://github.com/StevenBlack/hosts)

- BlocklistProject – Lista de drogas (drugs.txt)
  https://github.com/blocklistproject/Lists/blob/master/drugs.txt
- StevenBlack – Hosts extendidos (porn/social/gambling/fakenews)
  https://github.com/StevenBlack/hosts
- HaGeZi Blocklists – Pro++ (pro.plus.txt)
  https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.plus.txt
  https://github.com/hagezi/dns-blocklists/tree/main/domains
- HaGeZi – Threat Intelligence Feed (tif.txt)
  https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.txt
  
## Criterios de búsqueda:
## abuse, child, ilegal, csam, exploit, pedo, preteen, underage, molest, loli, teenporn, incest
## arms, gun, weapon, drugs, cocaine, heroine, meth, fentanyl, opiate, trafficking, humantraffiking, torture, gore, murder, rape, terror, darkweb, blackmarket, deepweb

## Archivos en este repositorio:

| Archivo               | Descripción                               |
|-----------------------|--------------------------------------------|
| `csam_hosts.txt`      | Dominios filtrados de contenido ilegal (CSAM) |
| `abuse_ips.txt`       | IPs asociadas a tráfico malicioso           |
| `malware_domains.txt` | Dominios de malware o phishing              |
| `trafico_ilicito.txt`| Lista personalizada con dominios propios   |
| `phishing_list.txt`| Dominios de phishing    |
| `ip_mineria.txt` | Dominios de mineria         |
| `iptv_block.txt` | Dominios de pirateria         |
| `botnet_list.txt` | Dominios de servidores botnet    |
