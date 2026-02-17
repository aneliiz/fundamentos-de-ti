
## **O que são Redes de Computadores?**

São conjuntos de dispositivos (computadores, servidores, smartphones, impressoras) interconectados por meios físicos (cabos) ou sem fio (Wi-Fi), capazes de trocar dados e compartilhar recursos entre si. Utilizando regras chamadas protocolos, elas conectam sistemas para facilitar comunicação, armazenamento e colaboração. 


### - *Aplicações de redes*

* **Comunicação:** E-mails,videoconferências, redes sociais
* **Compartilhamento de Recursos:** Impressoras, arquivos, aplicativos.
* **Serviço na Nuvem:** Armazenamento, Software como serviço (SaaS)
* **Internet das Coisas (IoT):** Dispositivos conectados para automação residencial e industrial.


### - *Componentes*

* **Dispositivos:** Computadores, servidores, roteadores, switches, etc.
* **Meios de Transmissão:** Cabos (Fibra ótica e cabo de Ethernet) e meios sem fio (Wi-Fi, Bluetooth)
* **Protocolos:** Conjunto de Regras que governam a comunicação (ex: TCP, IP).


### - *Tipos de Redes*

* **PAN (Personal Area Network):** Rede pessoal, como dispositivos conectados via Bluetooth.
* **LAN (Local Area Network):** Rede local, como uma casa ou escritório.
* **MAN (Metropolitan Area Network):** Rede que cobre uma cidade ou região.
* **WAN (Wide Area Network):** Rede de longa distância, como a Internet.


### - *Topologias de Redes*

* **Estrela:** Dispositivos conectados a um ponto central.
* **Barramento:** Todos os dispositivos compartilham um único meio de comunicação.
* **Anel:** Dispositivos conectados em um loop fechado.
* **Malha:** Cada dispositivo conectado a vários outros, garantindo múltiplos caminhos para os dados.


##

## **Internet, Web, HTTP e HTTPS**

### *1. O que é a Internet?*

A Internet é uma rede mundial de computadores interconectados que se comunicam por meio de protocolos padronizados.
Ela permite que dispositivos (computadores, celulares, servidores, IoT) troquem informações entre si.

*como funciona?*

* Endereço IP → Identificação de cada dispositivo na rede
* Protocolo TCP/IP → Conjunto de regras para transmissão de dados
* DNS (Domain Name System) → Traduz nomes de domínio (google.com) para IP

Ex:

1. Quando você digita www.google.com
2. O DNS descobre o IP do servidor
3. Seu dispositivo envia uma requisição
4. O servidor responde com os dados solicitados
  

  ##

  ### *2. O que é a Web?*

  A Web (World Wide Web) é um dos serviços que funcionam sobre a Internet.

  * Internet → Infraestrutura global
* Web → Sistema de páginas e aplicações acessadas via navegador

*A Web funciona com:*
- Navegadores (Chrome, Firefox)
- Servidores web
- Protocolo HTTP/HTTPS'   
- Linguagens como HTML, CSS e JavaScript


##


### *3. O que é HTTP?*

HTTP (HyperText Transfer Protocol) é o protocolo responsável pela comunicação entre cliente (browser) e servidor.

*Ele define:*

* Como a requisição é enviada
* Como a resposta é estruturada
* Quais métodos podem ser usados

*Principais métodos HTTP:*

* GET → Buscar dados
* POST → Enviar dados
* PUT → Atualizar dados
* DELETE → Remover dados

*Funcionamento:*

1. Cliente envia uma requisição HTTP
2. Servidor processa
3. Servidor envia uma resposta (status + dados)


*Exemplo de resposta:*

* 200 → OK
* 404 → Não encontrado
* 500 → Erro interno


##


### *4. O que é HTTPS?*

HTTPS (HyperText Transfer Protocol Secure) é a versão segura do HTTP.

*A diferença principal é que o HTTPS utiliza:*

* SSL/TLS para criptografia
* Certificado digital
* Comunicação segura entre cliente e servidor


*O que muda na prática?*

**No HTTP:**
Os dados trafegam em texto simples e podem ser interceptados.

**No HTTPS:**

Osados são criptografados e informações como senhas e cartões ficam protegidos.

##


### *Diferença entre elas:*

| Conceito  | O que é                          | Função                         |
|-----------|----------------------------------|--------------------------------|
| Internet  | Infraestrutura global            | Conectar dispositivos          |
| Web       | Serviço que roda na internet     | Exibir páginas e aplicações    |
| HTTP      | Protocolo de comunicação         | Transferência de dados         |
| HTTPS     | HTTP com segurança (SSL/TLS)     | Comunicação criptografada      |
