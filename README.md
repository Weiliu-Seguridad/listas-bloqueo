# WEINET – Listas de bloqueo personalizadas

Este repositorio contiene archivos de seguridad filtrados manualmente por Ing. Angie Jara responsable de la red de WeiNet para ser usados en MikroTik.

## Fuentes confiables utilizadas:

- BlocklistProject – Lista de abuse (abuse.txt)
  https://github.com/blocklistproject/Lists/blob/master/abuse.txt
- BlocklistProject – Lista de porn (porn.txt)
  https://github.com/blocklistproject/Lists/blob/master/porn.txt
- BlocklistProject – Lista de drogas (drugs.txt)
  https://github.com/blocklistproject/Lists/blob/master/drugs.txt
- BlocklistProject – Lista de malware (malware.txt)
  https://github.com/blocklistproject/Lists/blob/master/malware.txt
- StevenBlack hosts (https://github.com/StevenBlack/hosts)
- StevenBlack – Hosts extendidos (porn/social/gambling/fakenews)
  https://github.com/StevenBlack/hosts
- HaGeZi Blocklists – Pro++ (pro.plus.txt)
  https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.plus.txt
  https://github.com/hagezi/dns-blocklists/tree/main/domains
- HaGeZi – Threat Intelligence Feed (tif.txt)
  https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.txt
- https://urlhaus.abuse.ch/downloads/hostfile/
- https://raw.githubusercontent.com/ZeroDot1/CoinBlockerLists/master/list_browser.txt
- https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt
  
## Criterios de búsqueda:
## abuse, child, ilegal, csam, exploit, pedo, preteen, underage, molest, loli, teenporn, incest
## arms, gun, weapon, drugs, cocaine, heroine, meth, fentanyl, opiate, trafficking, humantraffiking, torture, gore, murder, rape, terror, darkweb, blackmarket, deepweb
## sendero luminoso, camarada gonzalo, etc.
## malware, pishing, trojan, worm, spyware, steals, ranson, keylogger, etc.

## Archivos en este repositorio:

| Archivo               | Descripción                               |
|-----------------------|--------------------------------------------|
| `bloqueo_dominios_riesgo_extremo.txt`      | Dominios filtrados de contenido ilegal (CSAM) |
| `bloqueo_trafico_extremista_violento.txt`| Lista personalizada con dominios propios   |
| `bloqueo_estafas.txt` | Dominios de phishing      |
| `bloqueo_dominio_malicioso.txt`| Dominios de malware    |
| `bloqueo_mineria_no_autorizada.txt` | Dominios de mineria      
| `bloqueo_streaming_no_legal.txt` | Dominios de pirateria     |
| `bloqueo_botnet_conocidas.txt` | Dominios de servidores botnet    |
