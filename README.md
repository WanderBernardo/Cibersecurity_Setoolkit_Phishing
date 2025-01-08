# Phishing para capturar senha de uma pagina da internet
Usaremos o site do ``` Facebook ``` como exemplo. 

### Ferramentas utilizadas:

- Kali Linux (https://www.kali.org/)
- Setoolkit (Ferramenta pré-instalada no Kali Linux)

### Pontos Importantes:
 - Caso esteja usando uma VM, certifique-se que a configuração da rede esteja no modo: Bridged Adapter(Inglês) ou Placa de modo Bridge(Português).
 - Funcionará para os dispositivos na mesma rede.
 - Ao clonar a pagina deve ser clonado a pagina onde se digita a login e senha.

### Resumo (Passo-a-passo): Configuração da ferramenta setoolkit para construção do Phishing no Kali Linux

01 - Acesso root no modo administrador: aplicar o comando ``` sudo su ```, em seguida vai pedir para digitar a senha do administrador.


02 - Iniciando o setoolkit: ``` setoolkit ```

03 - Tipo de ataque: ``` Social-Engineering Attacks ```

04 - Vetor de ataque: ``` Web Site Attack Vectors ```

05 - Método de ataque: ```Credential Harvester Attack Method ```

06 - Método de ataque: ``` Site Cloner ```

07 - Obtendo o endereço da máquina: ``` ifconfig ```

08 - URL para clone: http://www.facebook.com

### Resutados

![Alt text](./passwd.png "Optional title")
