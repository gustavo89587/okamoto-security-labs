# Okamoto Security Labs 🔒⚡

[![CyberSecurity](https://img.shields.io/badge/Focus-CyberSecurity-blue?style=for-the-badge&logo=datadog)]()  
[![DevSecOps](https://img.shields.io/badge/DevSecOps-orange?style=for-the-badge&logo=docker)]()  
[![Wazuh](https://img.shields.io/badge/SIEM-Wazuh-green?style=for-the-badge&logo=elastic)]()  
[![Next.js](https://img.shields.io/badge/Frontend-Next.js-black?style=for-the-badge&logo=next.js)]()  
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-teal?style=for-the-badge&logo=python)]()  
[![Supabase](https://img.shields.io/badge/DB/SaaS-Supabase-3ECF8E?style=for-the-badge&logo=supabase)]()  
[![AI Automation](https://img.shields.io/badge/AI-Automation-purple?style=for-the-badge&logo=openai)]()  

---

## 🚀 Sobre
Este é meu laboratório pessoal de **cibersegurança e DevSecOps**, onde documento:  
- Casos de estudo (*case studies*)  
- Playbooks de triagem  
- Pipelines e simulações em ambientes controlados  

Meu objetivo é mostrar conhecimento prático em **segurança ofensiva, defensiva e automação com IA**.  

---

## 🔎 Casos de Estudo

### Case 1 — Triagem em API pública: mitigação em 48h
- **Contexto**: análise em ambiente exposto  
- **Problema**: ausência de validação adequada  
- **Diagnóstico**: autenticação básica, POC controlado, análise de fluxo  
- **Solução**: autenticação robusta, rate limiting, revisão de CORS/headers  
- **Impacto esperado**: redução da superfície de ataque em 48h  

---

### Case 2 — Brute force controlado em endpoint de login
- **Contexto**: API de login sem rate limit  
- **Diagnóstico**: simulação de múltiplas tentativas em ambiente controlado  
- **Solução**: bloqueio progressivo, monitoramento, alertas via SIEM  
- **Impacto esperado**: redução do risco de credential stuffing  

---

### Case 3 — Integração Wazuh + Docker
- **Setup**: manager, indexer e dashboard em containers  
- **Teste**: ingestão de logs simulados (Apache, Nginx, API REST)  
- **Resultado**: dashboard customizado para detecção em tempo real  

---

## 🛠 Playbooks & Checklists

### Checklist de triagem rápida em APIs
- 🔐 Autenticação?  
- ⏱ Rate limiting?  
- 🌐 CORS bem definido?  
- 📑 Headers de segurança?  
- 📊 Logs ativos e monitorados?  

---

### Pipeline DevSecOps básico
1. Harden de Dockerfile  
2. Secrets no `.env` seguro  
3. CI/CD com lint + testes de segurança  
4. Deploy com rollback configurado  

---

## 📂 Estrutura do Repositório
