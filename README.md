# Projeto-Phishing
Criar uma página falsa de login do Facebook para capturar credenciais.

Ferramenta: Social-Engineer Toolkit (SET).
Metodologia:

Configurar o SET para clonar a página do Facebook.
Capturar as credenciais da vítima ao inserir dados no formulário falso.
Armazenar os dados em um arquivo de log local.

Abra o terminal e inicie o SET:

sudo setoolkit

Escolha o módulo de engenharia social:

Digite 1 (Social-Engineering Attacks) e pressione Enter.
Selecione o Web Attack Module:

Digite 2 (Website Attack Vectors) e pressione Enter.
Escolha a opção Credential Harvester Attack:

Digite 3 (Credential Harvester Attack Method) e pressione Enter.
Selecione a técnica Site Cloner:

Digite 2 (Site Cloner) e pressione Enter.
Insira o endereço IP para receber os dados:

O SET pedirá o endereço IP da sua máquina onde os dados capturados serão enviados.
Se estiver rodando o ataque na mesma máquina, use o IP local. Para saber seu IP, execute:

ifconfig
