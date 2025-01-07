# Simulação de Phishing com Kali Linux e SEToolkit

Este projeto apresenta um guia detalhado para configurar e executar uma simulação de phishing usando Kali Linux e a ferramenta SEToolkit. **Este material é exclusivamente educacional e deve ser utilizado dentro de um ambiente legal e ético.**

## Objetivo

Demonstrar técnicas de phishing para fins educativos, permitindo que profissionais de segurança compreendam e desenvolvam métodos de proteção eficazes contra ataques de engenharia social.

## Ferramentas Necessárias

- **Kali Linux**: Sistema operacional especializado em segurança cibernética.
- **SEToolkit (Social-Engineer Toolkit)**: Ferramenta para simulação de ataques de engenharia social.

## Passo a Passo

1. **Obtenha Acesso de Root**  
Abra o terminal e use o comando:
   ```bash
   sudo su
2. **Inicie o SEToolkit**  
Execute o comando:
   ```bash
   setoolkit
3. **Escolha o Tipo de Ataque**  
 Na interface do SEToolkit, selecione:
   ```bash
    1) Social-Engineering Attacks
    2) Web Site Attack Vectors
    3) Credential Harvester Attack Method
    2) Site Cloner
4. **Configure a Rede**  
Identifique o endereço IP da máquina para usar como host. Utilize o comando:
   ```bash
   ifconfig
5. **Clone o Site-Alvo**  
Insira o endereço do site que deseja simular. Por exemplo:
   ```bash
    http://www.facebook.com
6. **Colete Resultados**  
As credenciais inseridas na página clonada aparecerão no console do terminal onde o SEToolkit está rodando.
![Alt text](./passwd.png "Optional title")  
# Aviso Legal

**Este projeto deve ser usado apenas para fins educacionais e em ambientes de teste controlados.**  
Atividades ilegais relacionadas ao uso desta técnica podem resultar em consequências legais severas.

---

## Objetivo Educacional

Este guia foi criado para:

- Demonstrar táticas usadas em ataques de phishing.
- Promover a conscientização sobre segurança da informação.
- Treinar profissionais para implementar medidas eficazes de proteção.

---

## Boas Práticas de Prevenção

- **Educação**: Treine usuários finais para identificar tentativas de phishing.
- **Autenticação Multifator (MFA)**: Reduza os impactos de credenciais comprometidas.
- **Monitoramento Contínuo**: Analise o tráfego de rede para identificar atividades suspeitas.

---

**Nota**: Sempre garanta que você tem autorização para realizar esse tipo de simulação em qualquer ambiente.  
Use este conhecimento para construir um ciberespaço mais seguro.
