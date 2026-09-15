# ROV-OT-Cybersecurity-Framework
Framework prático e guia de cibersegurança industrial (OT/ICS) aplicada a ROVs e operações submarinas offshore.
# ⚓ ROV & Subsea OT Cybersecurity Framework

Este repositório contém um guia completo e prático sobre a aplicação de **Cibersegurança Industrial (OT/ICS)** em **Veículos Operados Remotamente (ROV)** e infraestruturas tecnológicas no setor de Óleo & Gás / Offshore.

---

## 📌 Visão Geral do Projeto

A tecnologia subsea moderna conecta robôs submarinos a uma vasta infraestrutura de redes industriais, switches, conversores, telemetria via fibra óptica e sistemas de controle. Este framework aborda como proteger esses ambientes operacionais contra ameaças cibernéticas sem comprometer a segurança da navegação e das operações subsea.

---

## 📚 Estrutura da Série (5 Módulos)

A documentação completa e os materiais de apresentação (slides em PDF) estão disponíveis na pasta [`/docs`](./docs/):

### 1. [Parte 1 — Introdução & IT vs OT](./docs/carrossel_rov_parte1.pdf)
- Conceituação do ecossistema de ROV como ambiente de OT/ICS.
- Diferenças fundamentais entre segurança de IT e OT no contexto marítimo.
- Mapeamento dos principais vetores de risco em embarcações e vans de controle.

### 2. [Parte 2 — Aprofundamento Técnico](./docs/carrossel_rov_parte2.pdf)
- Protocolos industriais submarinos (Modbus TCP/RTU, NMEA, EtherNet/IP).
- Hardening de estações de pilotagem e controle de aplicação (Whitelisting).
- Gestão e sanitização de mídias físicas/USB em ambientes isolados (Air-Gapped).
- Modelo Purdue aplicado à arquitetura de conectividade do ROV.

### 3. [Parte 3 — Governança & Compliance Marítimo](./docs/carrossel_rov_parte3.pdf)
- Alinhamento com regulamentações internacionais: **IMO MSC.428(98)**, **IEC 62443** e **NIST SP 800-82**.
- Estratégias de Gestão de Patches em alto-mar via satélite (VSAT/Starlink).
- Criptografia em camada física/enlace (MACsec) no cabo umbilical de fibra óptica.
- Gestão de credenciais OT (PAM) e auditoria técnica de fornecedores/terceiros.

### 4. [Parte 4 — Resiliência Operacional & Autonomia](./docs/carrossel_rov_parte4.pdf)
- Arquitetura **Zero Trust Subsea** e microsegmentação de atuadores/thrusters.
- Mitigação de ataques de **Sensor Spoofing** (falsificação de dados de sonar, altímetro e DVL).
- Operações de pilotagem remota de terra via **USV (Unmanned Surface Vessels)** e Centros de Controle (ROC).
- Especificações de hardware reforçado (*Hardened Switches*, Módulos TPM 2.0 e sensores Anti-Tamper).

### 5. [Parte 5 — Playbook de Excelência & Execução](./docs/carrossel_rov_parte5.pdf)
- Matriz **RACI** de responsabilidades cibernéticas a bordo e em terra.
- Indicadores-chave de desempenho (KPIs de Cibersegurança OT).
- Separação entre sistemas de **Safety (SIL)** e comandos lógicos (Interlocks de Hardware).
- Plano de ação prático de **30 dias** para onboarding e blindagem em vans de ROV.

---

## 🛠️ Tecnologias e Padrões Citados
- **Padrões & Frameworks:** IMO MSC.428(98), IEC 62443, NIST SP 800-82, NIST SP 800-88.
- **Protocolos industriais:** Modbus TCP/RTU, EtherNet/IP, NMEA 0183/2000, UDP.
- **Segurança de Rede:** Modelo Purdue, MACsec, IPsec, SPAN Port Monitoring, PAM (Privileged Access Management).

---

## 📂 Arquivos do Repositório
- [`/docs`](./docs/): Apresentações completas em formato PDF (utilizadas nos carrosséis do LinkedIn).
- [`/src`](./src/): Arquivos HTML/CSS base utilizados para gerar os slides.

---
*Desenvolvido como contribuição técnica para as comunidades de Cibersegurança Industrial, Engenharia Submarina e Operações Offshore.*
