# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux
- Kali Linux iniciado através do Virtual Box;
- Após carregar o sistema, na tela de login foi inserido as credenciais de acesso;
- Terminal foi aberto e inserido a seguinte sequência de comandos:
    - Como eu não estava como “root” no terminal, digitei o comando ```sudo su```
    - Depois digitei o comando ```setoolkit```
    - Digitei o número correspondente no menu para Social-Engineering Attacks: ```1```
    - Digitei o número correspondente no menu para  Website Attack Vectors: ```2```
    - Digitei o número correspondente no menu para Credential Harvester Attack Method : ```3```
    - Digitei o número correspondente no menu para Site Cloner: ```2```
    - O sistema sugeriu o IP do computador.
    - Digitei o seu site ```http://www.facebook.com/```
    - Aguardei a clonagem
    - Acessei o IP identificado no terminal em meu navegador no mode anônimo, porém tive problemas para visualizar o resultado esperado. Por isso segui uma sugestão de acessar o Internet Explorer contido no Windows 7 instalado em VM, com isso obtive o resultado esperado.
    - A tela fictícia do Facebook para login/senha apareceu, e inseri os dados:
![Image](https://github.com/user-attachments/assets/bf2fd401-a8fe-44b8-bb0d-21929a70c373)

    - Obtive o seguinte resultado:
![Image](https://github.com/user-attachments/assets/9bc420c6-47d7-47cf-99da-6c2f5d797700)
