# Laboratório de Brute Force com Medusa

Neste desafio, montei um laboratório utilizando Kali Linux e Metasploitable 2 no VirtualBox para praticar alguns testes de força bruta.
A ideia foi entender como esse tipo de ataque funciona na prática, identificar os serviços disponíveis e testar o Medusa em diferentes situações.

## Ferramentas utilizadas

- Kali Linux
- Metasploitable 2
- VirtualBox
- Medusa
- DVWA

## Configuração do laboratório

Configurei as máquinas virtuais utilizando uma rede Host-only no VirtualBox, permitindo a comunicação entre elas sem precisar expor o laboratório à rede externa.
As evidências da configuração estão na pasta `vbox`.

## Testes realizados

**1. FTP**
Realizei o teste de força bruta no serviço FTP da máquina Metasploitable 2 utilizando o Medusa.
Evidências na pasta `ftp`.

**2. Login Web (DVWA)**
Também realizei testes na página de login do DVWA, utilizando o Medusa para verificar as tentativas de autenticação.
Evidências na pasta `web login`.

**3. SMB**
Por último, fiz os testes no serviço SMB, observando o funcionamento das tentativas de autenticação.
Evidências na pasta `smb`.

## O que aprendi
Com a prática, consegui entender melhor como funciona um ataque de força bruta, como utilizar o Medusa e como identificar alguns serviços que podem ser alvos desse tipo de tentativa.
Também ficou mais claro como senhas fracas e falta de proteção nas tentativas de login podem representar riscos para um sistema.

## Conclusão
Foi uma boa oportunidade para colocar em prática o conteúdo estudado e conhecer melhor algumas ferramentas utilizadas na área de segurança da informação.
Todos os testes foram realizados em ambiente controlado, utilizando máquinas virtuais para fins de aprendizado.
