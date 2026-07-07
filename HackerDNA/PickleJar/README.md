HackerDNA - Pickle Jar Write-up
Descrição

Este repositório apresenta o write-up do laboratório Pickle Jar, disponibilizado pela plataforma HackerDNA.

O desafio simula o comprometimento de uma aplicação web desenvolvida em Python, explorando uma vulnerabilidade de desserialização insegura através do módulo pickle, permitindo a obtenção de Remote Code Execution (RCE). Após o acesso inicial, o laboratório exige a enumeração do ambiente, identificação de uma configuração insegura do sudo e a exploração dessa falha para obtenção de privilégios administrativos.

O objetivo deste trabalho foi documentar toda a metodologia utilizada durante a exploração, demonstrando não apenas os passos executados, mas também os conceitos técnicos envolvidos em cada fase do ataque.

Tópicos abordados
Reconhecimento e enumeração utilizando Nmap;
Identificação de vulnerabilidades em aplicações Python;
Exploração de Insecure Deserialization;
Execução Remota de Código (RCE);
Enumeração pós-exploração em ambientes Linux;
Identificação de configurações inseguras do sudo;
Escalação de privilégios até root;
Captura das User e Root Flags.
Tecnologias e Ferramentas
Kali Linux
Python 3
Nmap
Linux
Pickle
Subprocess
Bash
Sudo
Conhecimentos demonstrados

Este laboratório permitiu praticar conceitos importantes relacionados à segurança ofensiva, incluindo:

Vulnerabilidades de desserialização insegura;
Desenvolvimento de payloads em Python;
Execução arbitrária de comandos;
Enumeração de sistemas Linux;
Análise de permissões privilegiadas;
Exploração de configurações incorretas do sudo;
Metodologia de exploração utilizada em testes de intrusão.
