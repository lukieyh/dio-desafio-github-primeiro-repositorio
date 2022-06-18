# Introdução à programação para internet

### O que é Internet

PRIMEIRO DOMINIO CRIADO → **symbolics.com**

**PRIMEIRO BLOG CRIADO** → Open Diary, novembro 1994.

**Primeira compra feita na internet** → CD do cantor Sting, em 11 de agosto de 1994.

1. Redes
2. Backbone
3. Provedor de acesso
4. Provedor de serviço
5. Usuário final

~~*Provedor de serviço*~~

- Dial-up
- ADSL (banda larga)
- Fibra ótica
- Rádio
- Satélite
- Móvel
- P2P* (peer to peer)

~~*Caminho inverso*~~

- WWW
- DNS
- IP
- Classes de redes
- 127.0.01 *(localhost)*

**Exercicio Final**

ping [web.dio.me](http://web.dio.me/)

Pinging [d9xvcm3ctqqhv.cloudfront.net](http://d9xvcm3ctqqhv.cloudfront.net/) [13.227.126.55] with 32 bytes of data:
Reply from 13.227.126.55: bytes=32 time=36ms TTL=246

---

### TCP/IP, portas. roteadores, switches, modems

 

1. TCP/IP
2. Portas
3. Roteadores, switches, modems

**TCP** → Transmission Control Protocol

- 4 camadas
1. Física (ex.: placa de rede )
2. Rede (ex.: IP)
3. Transporte (ex.: TCP, UDP)
4. Aplicação (ex.: FTP, SMTP, HTTP)
- Protocolos de comunicação entre computadores
em rede
- Transmission Control Protocol - Protocolo de
Controle de Transmissão
- Internet Protocol - Protocolo de Internet
- Modelo de camadas

- UDP
    - Rápido
    - Não confiável
    - Carro do ovo
    - Livestream

- TCP
    - Voltado à conexão
    - Handshake
    - Integridade, ordem dos dados
    - Aplicativo de mensagens de texto
    
    **Portas (do Inglês: ports)**
    
- As “portinhas” por onde dados sairão e chegarão
- 20:FIP
- 22:SSH
- 25: SMIP
- 53: DNS â
- 80: HTTP X
- 443: HTTIPS

**MODEM**

- **Mo**dulator-**dem**odulator
- Hardware que converte dados em um formato que
possa ser transmitido de um computador para outro
e lido por outro

**ROTEADOR**

- Distribui internet para um ou mais dispositivos de
uma rede
- Pode fazer a comunicação entre redes
- Pode ser “burro”

**Switches**

- Distribui internet para um ou mais dispositivos de
uma rede
- Criado para ser “inteligente”"

---

### Celular, internet e outros dispositivos

1. Dados móveis
2. Wi-Fi
3. Bluetooth

 **SMS**

- Quanto custa, para uma operadora de telefonia
móvel, enviar um SMS?
- O. Nada. Vazio. null.
- O celular troca, naturalmente, alguns bits com as
torres de comunicação
- “Você está aí?” “Estou” “Você está aí?” “Estou”
“Você está aí?” “Estou” “Você está aí?” “Estou”

**MMS**

- Transmissão de mensagens multimídia (áudio, vídeo) por meio de uma espécie de conexão de dados primitiva.

**Conexões Móveis**

- 1G (analógico): 10Kbps
- 2G (digital) (GSM (Global System for Mobile
Communication)): 97 kbps
- GPRS (General Packet Radio Service) / “2,5G":
- 32-80Kbps — dados + voz
- EDGE (Enhanced Data Rates for GSM Evolution) /
“2,75G": 128-236 Kbps !
- 3G (7Mbps), 4G (22,1Mbps), 5G (10Gbps)

**Wi-Fi**

- IEEE 802.11: 2,4 GHz, 2Mbps
- IEEE 802.11a: 5 GHz, 54Mbps
- IEEE 802.11b: 24 GHz, 11 Mbps (diminuição de
interferência)
- IEEE 802.11g: 24 GHz, 54Mbps
- IEEE 802.11nN: 2,4 GHz/5GHz, 150-600Mbps

**Segurança**

- WEP: chaves de 64 bits e de 128 bits
- WPA: chave trocada periodicamente
- WPA2(AES) (802.11i)
- +segurança
- +processamento

**Bluetooth**

---

### Browser, sites, aplicativos e webserver

[**Browser**](https://archive.org/web/)

**Site**

- Página da Internet
- Diversos propósitos
- Podem ser feitas em diversas LP
- D/XHTML caindo em desuso

**Aplicativo**

- Um software que é executado no navegador
- Um aplicativo de celular, muitas vezes, nada mais é
do que uma espécie de navegador
- Hoje em dia, já quase não existe diferença entre site e aplicativo, e o primeiro está em declínio
- Outra diferença terminológica que está sumindo é
entre programa/software e aplicativo

  E-commerce

- “e”, assim como em “e-mail”, significa “electronic”
- Comércio eletrônico
- Site de compra e venda com sistema de pagamento
- O sistema de pagamento pode ser exterior ao site
- PicPay, Boleto, PagSeguro, PayPal, Mercado Pago

**Web-server**

- Existem 2 tipos: estático e dinâmico
- O estático é um servidor físico onde são
armazenados arquivos, softwares e/ou banco de
dados
- O dinâmico se refere aos sofwares que estão
presentes no servidor físico

**Web-server dinâmico**

- Arquivos (file server)
- Aplicações (appication server)
- Banco de dados (database)
- Tudo junto e misturado
- Um site, ou aplicativo, precisa estar hospedado em
um servidor para pode ser acessado
- Os dados de um site precisam estar em um servidor
- O banco de dados de um site ou aplicativo precisa
estar em um servidor

**Web-service**

- Interface disponível para fazer requisições e consultas em bancos de dados inacessíveis (Correios, Governo)

---

### Stacks

1. O que é
2. Front-end, back-end, full stack
3. Exemplos
- Pilhas de tecnologia
- Conjunto de softwares necessários e suficientes para executar um aplicativo/programa
- Linguagens de programação
- Ambientes e ferramentas de interação com o
app/sw
- Capacidade e limitação de performance
- Pontos fortes e fracos do app/sw

**Importancia** 

- Os líderes de projetos precisam das informações das
equipes de desenvolvimento
- Os desenvolvedores precisam saber as limitações e
capacidades das ferramentas e ambientes que têm
disponíveis
- Sistemas, bancos de dados, linguagens de
programação, protocolos de Comunicação
- Estratégias de negócios
- Maturidado
- Contratações, planos de mitigação de riscos, aumento de capacidade, uso dos dados

---

### Definição de Front-end, Back-end e Fullstack

**Front-end**

- “Parte da frente”
- Site, software, aplicativo, web service
- Interface, UI, UX
- Lógica de programação, HTML, CSS,
jQuery/JS/AJAX, PHP, Bootstrap/outros frameworks

**Back-end**

- “Parte de trás”
- Servidores, bancos de dados
- “meio-de-campo” entre interface e banco de dados, regras de negócios, validações
- MySQL, Oracle, protocolos de comunicação, PHP, Java, node.js

**Full stack**

- Profissional que sabe trabalhar em todas as camadas das tecnologias de desenvolvimento/execução de um app/sw

---

### LPs e termos

1. Principais linguagens
2. Termos comuns

**Principais linguagens**

- HTML
- CSS
- JavasScript (jQuery,
AJAX, diversas libs)
- PHP
- NET
- ASP
- Java
- Ruby (on Rails)
- Python
- Perl
- C/C++/C#

**Termos comuns**

- 404
- Algoritmo
- ALT
- API
- Aplicação
- Back-end
- Biblioteca/dll
- Bootstrap
- Breakpoints
- Browser/navegador
- Bug
- Cache
- Código
- Controle de versão
- Cookies
- Debug
- Deploy
- Design adaptativo/responsivo
- DNS
- Documentação
- Domínio
- DPI
- Editor de texto
- Estrutura de dados
- Favicon
- Fontes
- Framework
- Front-end
- FTP
- Full-stack
- Git/SVN/CVS
- HTTP (S)
- IP
- Linguagem
- Meta tags
- Método ágil
- Mobile
- MVC
- MVP
- MySQL
- Pixel
- Resolução
- Servidor
- Sistema operacional/SO
- Solução
- SSL
- UI
- UX
- Versão
- WYSIWYG *"What You See Is What You Get”*

**~~JQuery~~**

**[W3School](https://www.w3schools.com/)**