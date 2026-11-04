# 🐾 Pet Family

**Jornada Contínua do Responsável pelo Pet**  
*Challenge CLYVO VET 2026 – FIAP | 2TDSPG*

---

## Sobre o projeto

O **Pet Family** é uma solução digital desenvolvida em resposta ao **Challenge CLYVO VET 2026**, proposto pela FIAP em parceria com a CLYVO.

O mercado pet brasileiro tem alto potencial de recorrência — mas enfrenta um gap crítico: o responsável só aciona a clínica em situações de urgência ou gatilhos óbvios, como vacinação. Isso gera baixa recorrência, menor LTV para clínicas e um vínculo fraco entre tutor, pet e veterinário.

O **Pet Family** resolve esse problema criando um ecossistema de cuidado contínuo que conecta tutores, pets e clínicas veterinárias, promovendo acompanhamento preventivo, personalização por perfil clínico e recorrência de consultas.

---

## O Problema

| Sintoma | Impacto |
|---|---|
| Baixa recorrência | Consultas e exames preventivos são esquecidos ou negligenciados |
| Menor LTV | Oportunidades de check-up, retorno e acompanhamento são perdidas |
| Vínculo fraco | Sem histórico longitudinal estruturado entre clínica e tutor |

---

## A Solução

O Pet Family cobre quatro grandes pilares de cuidado ao longo da vida do animal:

- **Preventivo** — vacinas, vermífugo, check-up e protocolos por espécie e raça
- **Terapêutico** — adesão medicamentosa e acompanhamento crônico
- **Bem-estar** — nutrição, comportamento e saúde por fase de vida
- **IA** — personalização, priorização e contato clínico via assistente conversacional veterinário

---

## Tecnologias utilizadas

| Área | Tecnologias |
|---|---|
| Back-end (API principal) | Java 17, Spring Boot 3.2.5, Spring Data JPA, Swagger/OpenAPI, H2 |
| Back-end (API secundária) | C# .NET 9, ASP.NET Core, Entity Framework Core, Oracle |
| DevOps / Cloud | Docker, Azure, Clean Architecture |
| Mobile | React Native, Expo, TypeScript, AsyncStorage |
| IoT | ESP32, Arduino (C++), DHT22, Servo SG90, LCD I2C, Wokwi |
| IA | Python, Google Gemini 1.5 Flash |
| QA | Azure Boards (Scrum), Selenium IDE, Katalon Studio, Postman, JMeter |

---

## Repositórios do projeto

| Módulo | Repositório | Linguagem | Disciplina |
|---|---|---|---|
| App Mobile | [PET-FAMILY-MOBILE](https://github.com/PET-FAMILYY/PET-FAMILY-MOBILE) | TypeScript | Mobile Development |
| API Java | [PET--FAMILY-JAVA](https://github.com/PET-FAMILYY/PET--FAMILY-JAVA) | Java | Java Advanced |
| API .NET | [PET-FAMILY-.NET](https://github.com/PET-FAMILYY/PET-FAMILY-.NET) | C# | .NET |
| Cloud / DevOps | [PET-FAMILY-CLOUD](https://github.com/PET-FAMILYY/PET-FAMILY-CLOUD) | — | DevOps Tools & Cloud Computing |
| IoT (Smart Feeder) | [PET-FAMILY-IOT](https://github.com/PET-FAMILYY/PET-FAMILY-IOT) | C++ | Disruptive Architectures: IoT, IoB & Generative IA |
| IA (Assistente Veterinário) | [PET-FAMILY-IA](https://github.com/PET-FAMILYY/PET-FAMILY-IA) | Python | Disruptive Architectures: IoT, IoB & Generative IA |

---

## Destaque por módulo

### 📱 Mobile
App com 7 telas: Home, Meu Pet, Assistente IA (chat estilo WhatsApp), Agenda de cuidados, Agendamento de consultas, Dashboard clínico e Sobre. Assistente integrado ao Gemini 1.5 Flash na Sprint 4, com system prompt dinâmico usando dados do pet e status em tempo real do ESP32.

▶ [Vídeo Sprint 1-2](https://youtu.be/lMNOv6BkaOI?si=jpeyoyVkqabfCm6J)

### 🔌 IoT — Pet Family Smart Feeder
Alimentador automático controlado por ESP32 com dashboard web embarcado (sem backend externo). Alimentação por intervalo ou horário fixo via NTP, monitoramento de temperatura e umidade (DHT22), alerta sonoro, controle manual e log de eventos. Simulação via Wokwi for VS Code.

▶ [Vídeo Sprint 1-2](https://youtu.be/u72wM5YJbO0)

### 🤖 IA — Assistente Veterinário
Assistente conversacional veterinário com Gemini 1.5 Flash integrado ao app mobile. Histórico de conversa, quick replies contextuais (Vacina, Vermífugo, Check-up, Sintomas) e personalização com dados do pet via AsyncStorage.

📐 [Diagrama de Arquitetura](https://pet-familyy.github.io/PET-FAMILY-IA/docs/architecture-diagram.html)

---

## Status das Sprints

| Sprint | Semestre | Status | Entregas |
|---|---|---|---|
| Sprint 1 | 1º | ✅ Entregue | Protótipo Mobile · APIs Java e .NET · Alimentador IoT |
| Sprint 2 | 1º | ✅ Entregue | Evolução Mobile e APIs · Cloud/DevOps · IoT refinado |
| Sprint 3 | 2º | ✅ Entregue | Arquitetura IA documentada · Backlog QA no Azure Boards |
| Sprint 4 | 2º | ✅ Em andamento | Integração Gemini ao app · Testes automatizados |

---

## Como acompanhar

Este repositório é o ponto de entrada da organização.  
Os códigos, documentações e instruções de execução estão nos repositórios listados acima.

---

## Equipe

| Nome | RM | Turma |
|---|---|---|
| Felipe Kirschner Modesto | RM561810 | 2TDSPG |
| João Victor Luiz de Oliveira Resende | RM565139 | 2TDSPG |
| Pedro Henrique Vaz Ferreira | RM566551 | 2TDSPG |
| Vitor Dias dos Santos | RM565422 | 2TDSPG |

> *A equipe é responsável por todas as entregas das disciplinas: Java Advanced, .NET, DevOps Tools & Cloud Computing, Mobile Development, Disruptive Architectures (IoT, IoB & Generative IA) e Compliance, Quality Assurance & Tests.*

---

*Projeto desenvolvido para o Challenge FIAP 2026 – CLYVO VET.*
