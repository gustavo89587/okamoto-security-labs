# Case: Brute force controlado em endpoint de login

🔎 **Contexto**  
API de login exposta sem rate limiting adequado.  

⚡ **Problema**  
Permitia tentativas sucessivas de senha sem bloqueio progressivo.  

🛠 **Diagnóstico**  
1. Mapeamento do fluxo de autenticação  
2. Simulação controlada de múltiplas tentativas  
3. Monitoramento do tempo de resposta  

✅ **Solução recomendada**  
- Implementar bloqueio progressivo após X tentativas  
- Adicionar alertas no SIEM (Wazuh)  
- Aumentar logging e correlação em tentativas falhas  

🚀 **Resultado esperado/impacto**  
Redução do risco de credential stuffing e brute force.  
