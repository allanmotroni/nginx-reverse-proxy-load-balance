# nginx com proxy reverso e load balance

Adicionar no hosts os seguintes endereços

127.0.0.1   labs.com.br
127.0.0.1   blue.labs.com.br
127.0.0.1   green.labs.com.br

Subir a stack

docker-compose up -d

Digitar no navegador

http://labs.com.br/
http://labs.com.br/blue
http://labs.com.br/green

http://blue.labs.com.br/

http://green.labs.com.br/
