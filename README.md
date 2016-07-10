# AART
Automatic Address Reputation Tool

 Ferramenta que com base na reputação do IP rejeita qualquer conexão do mesmo através de envio de comandos para o firewall (localhost ou remoto).

Requisitos:

- Análise de conexões provenientes da Internet (OUTSIDE) para LAN (INSIDE) (REALTIME)  e, 
- Log de conexões provenientes da INSIDE para OUTSIDE para os IPs contidos na base de dados. (NEAR-REALTIME - 30s)
- DB NoSQL ou MySQL/Postgres
- Python, Bash, C e outras linguagens são aceitas...(desde que independam de arquitetura para execução)
- Possibilidade de uso de REST API para integração com outras ferramentas (tools - futuro)
- Capaz de receber e processar log's de proxies, IDS/IPS, Firewalls, Syslog e arquivos (grande possibilidade de resolver a primeira questão)
- Documentação de quais bibliotecas e porque estão sendo utilizadas assim como das próprias funções.

Capacidade de processamento necessária não deve ser um impedimento no momento, apenas lembrem-se de que é interessante (e creio que sempre será) que a aplicação possa trabalhar com mutiplas threads.

A ideia do REST API é por conta de outros sistemas já utilizarem REST API como por exemplo https://cuckoosandbox.org/

Se integrarmos ambos já teremos um sistema poderoso contra vários tipos de incidentes...

Ex: 

- Ataques provenientes de botnets, tor, darknet, spammers...
- Malwares como Zeus, Ransomwares...
- Data Exfiltration...
- Etc...
