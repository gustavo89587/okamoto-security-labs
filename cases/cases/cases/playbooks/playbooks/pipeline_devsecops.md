# Pipeline básico DevSecOps

1. Harden de Dockerfile (user não-root, COPY seguro)  
2. Secrets armazenados em `.env` protegido (não versionar)  
3. CI/CD com steps de lint + testes de segurança (bandit, semgrep)  
4. Deploy com rollback configurado  
5. Monitoramento contínuo de logs e métricas de segurança  
