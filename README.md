# Oi, eu sou o Bruno Bianchi

**Engenharia de Software e IA aplicada (LLMs, Speech-to-Text) · Python, SQL, TypeScript, Node.js · AWS Certified AI Practitioner · 2x 1º lugar em hackathon**

Estudante de Engenharia de Computação na [UNIFEI](https://unifei.edu.br), com previsão de formatura em jul/2028, e desenvolvedor de software com foco em IA aplicada. Moro em Jundiaí, SP. Gosto de pegar um problema real, entender a regra de negócio e entregar do banco de dados até a interface, com testes e decisões documentadas.

[Portfólio](https://brunobianchi.dev) · [LinkedIn](https://www.linkedin.com/in/brunorbianchi) · [bruno.raiadobian@gmail.com](mailto:bruno.raiadobian@gmail.com)

## O que estou fazendo agora
- **Projeto acadêmico UNIFEI x Midea (240h, time de 5):** PoC de speech-to-text para o call center, com redução de ruído, transcrição com Whisper, remoção de dados pessoais (LGPD) e análise por LLM. O projeto está em fase de testes na empresa, então ainda não tenho métricas para divulgar.
- **Comunidade:** Google Student Ambassador 2026 e AWS Student Builder Group Leader.
- **Estudo:** Linux Foundation LiFT Scholar, rumo ao CKAD.

## Como eu uso IA
Uso IA como ferramenta de engenharia, não como piloto automático. No dia a dia, trabalho com **Claude** e **Kiro**.
- **Specs antes do código:** no projeto da Midea escrevi requisitos, design e tarefas com o Kiro antes de implementar ([.kiro/specs](https://github.com/BrunoBianchi/midea-speech-to-text/tree/main/.kiro/specs/system-design)).
- **LLM dentro do produto:** chat financeiro com Llama via Groq no TechFinance, geração e pontuação de posts com prompts tipados em BAML no Portyo, análise de prompts guiada pela estratégia TCREI no BetterPrompt.
- **Validação humana:** o que a IA gera passa por testes automatizados e pela minha revisão antes de entrar no código.

## Projetos em destaque
| Projeto | O que é | Destaques de engenharia |
|---|---|---|
| [TechFinance](https://github.com/BrunoBianchi/Tech4Humans-Webapp-Financa) | 1º lugar no TechLab 2025 (Tech4Humans). App de finanças pessoais com contas, cartões, transações e assistente de IA | Fila FIFO de transações com Redis/Bull, validação em 3 camadas (front, Zod, PostgreSQL), JWT em cookie HttpOnly, rate limit, testes unitários com Jest |
| [Midea Speech-to-Text](https://github.com/BrunoBianchi/midea-speech-to-text) | PoC de transcrição e análise de ligações do call center (em andamento) | Python + FastAPI + faster-whisper, gateway Node com SSE, contratos compartilhados, specs com Kiro, Conventional Commits, semantic-release, pytest |
| [BetterPrompt](https://github.com/BrunoBianchi/BetterPrompt) | Marketplace colaborativo de prompts com teste e análise por LLM | API versionada, Google OAuth + JWT, 15 arquivos de teste (bun test) incluindo o serviço de IA |
| [Portyo](https://github.com/BrunoBianchi/Portyo) | SaaS multi-tenant de link-in-bio com domínios próprios e posts gerados por IA | Nginx catch-all + SSL por domínio, cron de agendamento, prompts em BAML, Groq (Llama 3.3 70B) |
| [Tech4Um](https://github.com/BrunoBianchi/Tech4Um-Grupo02) | 1º lugar no Hackathon Ninja Startup Job 2026, time de 3. Fórum com chat em tempo real | Socket.IO com handshake JWT, PostgreSQL, Docker Compose, validação com Zod |
| [GSA Brazil Hub](https://github.com/BrunoBianchi/Google-Students-Ambassador) | Plataforma da comunidade de Google Student Ambassadors no Brasil | React Router, Node/Bun, Google OAuth, testes de backend |

## Experiência
- **Projeto acadêmico UNIFEI x Midea:** PoC de STT + IA com um time de 5 estudantes e stakeholders da Midea.
- **Tech for Humans:** migração de funcionalidades legadas para serviços componentizados e Azure Functions.
- **Vertis Solutions (P&D UNIFEI):** pipelines em Python para detecção precoce de anomalias em redes 5G.
- **Asimov Jr.:** estruturei a área de Ciência de Dados e fui mentor de Python e R.
- **Freelancer na Fiverr desde 2022:** aplicações web, bots e landing pages.

## Stack
**Linguagens:** Python, SQL, TypeScript, JavaScript  
**Back-end:** Node.js, Express, NestJS, FastAPI  
**Front-end:** React, React Router, Angular, Tailwind  
**Dados:** PostgreSQL, MongoDB, Redis  
**Infra:** Docker, Nginx, AWS, Azure, GitHub Actions  
**Qualidade:** Jest, Vitest, bun test, pytest, ESLint, Husky, Conventional Commits  
**IA no desenvolvimento:** Claude, Kiro

## Certificações
AWS Certified AI Practitioner · MongoDB Associate Developer

## Em busca de
Estágio em engenharia de software, com interesse em produtos financeiros e IA aplicada.
