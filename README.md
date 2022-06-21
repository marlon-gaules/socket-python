# Socket Python

<p>Esse laboratório foi criado para demonstrar a comunicação entre os Sockets Client/Server na Camada de Transporte (L4), após transferencia de pacotes http na Camada de Aplicação (L7). Para isso foi ultilizado biblioteca Socket Python</p>

# Informações técnicas server.py
<p>python3 -> meu interpretador</p>
<p>import socket -> importando a biblioteca para conseguir usar dentro do meu código</p>
<p>AF_INET -> familia do socket (socket de rede)</p>
<p>SOCK_STREAM -> informando que a conexão é TCP</p>
<p>.bind -> endereço de comunicação com server</p>
<p>socket.accept -> mantém a conexão aberta após vários pacotes enviados</p>
<p>.recv -> método que vai receber o dado e o tamanho da mensagem</p>
<p>.decode -> desempacota a mensagem em bytes</p>

# Informações técnicas client.py
<p>python3 -> meu interpretador</p>
<p>import socket -> importando a biblioteca para conseguir usar dentro do meu código</p>
<p>AF_INET -> familia do socket (socket de rede)</p>
<p>SOCK_STREAM -> informando que a conexão é TCP</p>
<p>.bind -> endereço de comunicação com server</p>
<p>.encode -> empacota a mensagem em bits</p>

# Execução
<p>No diretório root executar ./server.py depois ./client.py, após isso o server irá printar as mensagens enviadas pelo client, com endereço (ip:porta)</p>