# ZABBIX-Audit-LoginPassword-Linux
Monitoramento de tentativa de Login com credenciais inválidas em Servidores Debian e Ubuntu com Zabbix. 
Tested on Zabbix 4.0.x / 5.0.0 / 5.4.0 | Debian 9 e Ubuntu 20.04

# Criação da Chave
Monitoramento realizado no arquivo /var/log/auth.log, arquivo precisa ter permissão de acesso.

![image](https://user-images.githubusercontent.com/88397673/156215437-a75e95fe-4128-4df8-b0d5-a3bfa6827e94.png)

# Criação da Trigger

![image](https://user-images.githubusercontent.com/88397673/156215646-95c6b82b-95d5-4a27-bd76-359a0a5f6638.png)

# Trigger em atuação

Teste em Ubuntu 20.04:
![image](https://user-images.githubusercontent.com/88397673/156216579-98cb81f4-d9d1-43b5-aaf7-5279fcc1c8e8.png)

Teste em Debian 9

![image](https://user-images.githubusercontent.com/88397673/156218104-eda23433-7f45-4aa7-8610-cab392544257.png)

Importe o Template, vincule-o ao Host e inicie o Monitoramento!
