# Projeto-Phishing Dio.me CyberSecurity
Criar uma página falsa de login do Facebook para capturar credenciais.

Ferramenta: Kali Linux / Social-Engineer Toolkit (SET).
Metodologia:

Configurar o SET para clonar a página do Facebook.
Capturar as credenciais da vítima ao inserir dados no formulário falso.
Armazenar os dados em um arquivo de log local.

1º Abra o terminal e inicie o SET:
sudo setoolkit

2º Escolha o módulo de engenharia social:
Digite 1 (Social-Engineering Attacks) e pressione Enter.

3º Selecione o Web Attack Module:
Digite 2 (Website Attack Vectors) e pressione Enter.

4º Escolha a opção Credential Harvester Attack:
Digite 3 (Credential Harvester Attack Method) e pressione Enter.

5º Selecione a técnica Site Cloner:
Digite 2 (Site Cloner) e pressione Enter.

6º Insira o endereço IP para receber os dados:
O SET pedirá o endereço IP da sua máquina onde os dados capturados serão enviados.
Se estiver rodando o ataque na mesma máquina, use o IP local. Para saber seu IP, execute:

ifconfig
Insira o IP obtido, por exemplo: 192.168.0.21

7º Insira a URL do site a ser clonado: 
https://www.facebook.com/login

8º Finalize a configuração:
O SET irá clonar a página do Facebook e iniciar o servidor HTTP.

9º Envie o link falso para a vítima:
O SET gerará um link que a vítima deve acessar.
Se estiver na mesma rede, use o IP local; caso contrário, utilize um domínio ou IP público.

10º Monitore as credenciais capturadas:

As credenciais inseridas pela vítima serão exibidas no terminal e armazenadas em um arquivo de log na pasta do SET:

/var/www/html/

Atenção Pontos Importantes ( Este projeto foi feito para fins de estudo da DIO.ME) 

º Use esse método apenas em redes controladas, com autorização do proprietário.

º Caso precise rodar fora da sua rede, utilize ferramentas como ngrok para expor localmente seu servidor na internet.

º Sempre informe às pessoas envolvidas sobre a finalidade educacional ou de segurança desse teste.
