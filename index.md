# 🚀 Resumo da Jornada: Alpha EdTech
## 📋 Visão Geral
Este repositório consolida os conhecimentos técnicos adquiridos sobre o funcionamento físico e lógico da internet, segurança da informação e fluxo de trabalho com versionamento de código.

---

## 🌐 Parte 1: Fundamentos e Arquitetura da Internet

A internet é uma infraestrutura física global, não uma nuvem abstrata.

### Estrutura e Modelos
* **Tipos de Redes:** LAN (Local), MAN (Metropolitana), WAN (Global) e PAN (Pessoal).
* **Modelos de Camadas:**
    * **OSI (7 camadas):** Modelo teórico detalhado.
    * **TCP/IP (4 camadas):** O modelo prático usado na internet.
* **Arquitetura Global:** A internet é hierárquica, formada por ISPs (Provedores), backbones de fibra óptica e roteamento global via **BGP**.

### O Modelo Cliente-Servidor
Toda a web funciona baseada em pedidos (Requests) e respostas (Responses).
* **Cliente:** Quem solicita (Browser, App).
* **Servidor:** Quem processa e armazena.
* **CDN (Content Delivery Network):** Servidores espalhados geograficamente para entregar conteúdo mais rápido (cache).

---

## 🔗 Parte 2: Protocolos e Conectividade

Para dispositivos conversarem, eles precisam de regras (protocolos) e endereços.

### Endereçamento e Roteamento
* **IP (Internet Protocol):** O "CPF" da máquina.
    * **IPv4 vs IPv6:** A transição do modelo antigo (esgotado) para o novo.
    * **CIDR e Subnetting:** Como dividimos redes grandes em menores.
* **NAT:** Técnica que permite vários dispositivos usarem um único IP público.
* **Portas Lógicas:** Diferenciam serviços (Ex: Porta 80 para Web, 22 para SSH).

### Protocolos de Transporte e Aplicação
1.  **TCP (Transmission Control Protocol):** Confiável, garante entrega (Ex: Bancos, E-mail).
2.  **UDP (User Datagram Protocol):** Rápido, sem verificação (Ex: Streaming, Jogos).
3.  **DNS (Domain Name System):** O "tradutor" que converte nomes (`google.com`) em IPs. Tipos de registro: A, CNAME, MX, TXT.

---

## 🛡️ Parte 3: Segurança da Informação

A segurança deve ser pensada desde a infraestrutura até o código da aplicação.

### Ameaças Comuns
* **Malware:** Vírus, Ransomware, Spyware.
* **Ataques de Rede:**
    * **DDoS:** Negar serviço por sobrecarga.
    * **MITM (Man-in-the-Middle):** Interceptação de dados.
    * **Spoofing:** Falsificação de identidade.

### Mecanismos de Defesa
* **Firewalls e IDS/IPS:** Filtram tráfego suspeito.
* **Criptografia na Web (HTTPS):** Uso de certificados SSL/TLS para garantir confidencialidade. O "Handshake" estabelece chaves seguras entre cliente e servidor.
* **VPN:** Túnel seguro para tráfego privado.

---

## 🚀 Parte 4: Tendências e Tecnologias Modernas

O futuro da infraestrutura conecta dispositivos e descentraliza dados.

* **IoT (Internet das Coisas):** Protocolos leves como MQTT e CoAP para sensores.
* **Cloud Security:** Conceitos de Zero Trust (nunca confiar, sempre verificar).
* **Blockchain:** Imutabilidade e consenso distribuído.

---

## 🐙 Parte 5: Git e GitHub (Versionamento)

Segurança e organização no desenvolvimento de software.

### Conceitos Chave
* **Versionamento:** Histórico completo de alterações (`git log`).
* **Workflow:**
    1.  **Working Directory:** Onde você edita.
    2.  **Staging Area:** Onde você prepara (`git add`).
    3.  **Repository:** Onde você salva (`git commit`).

### Guia Rápido de Comandos

| Comando | Função |
| :--- | :--- |
| `git init` | Inicia o monitoramento Git. |
| `git status` | Verifica estado dos arquivos. |
| `git add .` | Prepara tudo para o commit. |
| `git commit -m "msg"` | Salva uma versão na linha do tempo. |
| `git push` | Envia alterações para o GitHub. |
| `git pull` | Baixa alterações do GitHub. |

---
