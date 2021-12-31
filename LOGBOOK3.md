# CVE-2020-0787

***

## Identificação

Esta vulnerabilidade permite a elevação de privilégios usando o serviço **Windows Background Intelligent Transfer Service** (BITS) que gere incorretamente links simbólicos e desta forma, permite que o código seja executado com privilégios de administrador. As versões/sistemas operativos que estão vulneráveis são:
* Microsoft Windows 10 (versões)
    * 1079
    * 1803
    * 1809
    * 1903
    * 1909 
* Microsoft Windows 7 
* Microsoft Windows 8.1 
* Microsoft Windows RT 8.1 

Os servidores vulneráveis são: 
* Microsoft Windows Server 2008 
* Microsoft Windows Server 2008 R2
* Microsoft Windows Server 2012 
* Microsoft Windows Server 2012 R2
* Microsoft Windows Server 2016
* Microsoft Windows Server 2016 1903
* Microsoft Windows Server 2016 1909
* Microsoft Windows Server 2019

***

## Catolagação
O bug foi reportado internamente em 4 de novembro de 2019 e tem um nível de gravidade elevado (7.8 em 10)

***
## Exploit
Existe um exploit do Metasploit criado a 10 de março de 2020 que permite elevar o privilégio em Windows automatizando o uso da vulnerabilidade elevando os privilégios e tem rank **excellent**.

***
## Ataques
É usado frequentemente para atacar serviços da Microsoft, tal como servidores e computadores. Tem o potencial de causar danos catastróficos, uma vez que o atacante ganha controlo sobre o sistema como administrador.
