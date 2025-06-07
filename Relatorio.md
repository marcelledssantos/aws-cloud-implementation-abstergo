
# 🧠 RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**📅 Data de Início do Projeto:** 07/06/2025  
**🏢 Empresa:** Abstergo Industries  
**👩‍💻 Responsável:** Marcelle Santos

---

## 📌 Introdução

O presente relatório tem como objetivo descrever o plano de implementação de soluções baseadas em computação em nuvem (AWS) na empresa **Abstergo Industries**, uma distribuidora farmacêutica que atua como hub logístico entre laboratórios e redes de farmácias em todo o Brasil.

A iniciativa foi impulsionada por uma demanda direta do setor financeiro, com foco em **redução imediata de custos operacionais**, modernização da infraestrutura e preparação da empresa para uma **escala sustentável**.

---

## 🗂️ Visão Geral do Projeto

A proposta de implementação foi estruturada em **três etapas estratégicas**, cada uma representando um pilar da arquitetura em nuvem:

1. **Infraestrutura escalável e sob demanda**
2. **Armazenamento seguro e de baixo custo**
3. **Banco de dados gerenciado com alta performance**

Cada etapa está descrita a seguir com a ferramenta AWS adotada, o seu propósito, processo de implantação e os benefícios concretos esperados.

---

## 🚀 Etapa 1: Amazon EC2 – Infraestrutura Escalável

**🔧 Ferramenta:** Amazon EC2 (Elastic Compute Cloud)  
**🎯 Objetivo:** Substituir servidores físicos locais por instâncias virtuais escaláveis, reduzindo custos fixos com hardware e energia.

### 🔍 Como será implementado:

- Criação de instâncias EC2 sob demanda para hospedar aplicações internas.
- Utilização de **Auto Scaling Groups** e **Elastic Load Balancer** para distribuir tráfego e garantir disponibilidade.
- Adoção de instâncias **spot** para cargas de trabalho temporárias, com economia de até 90%.

### 💡 Principais ganhos:

- Redução significativa de gastos com infraestrutura local.
- Flexibilidade para escalar de acordo com a demanda da operação.
- Alta disponibilidade e resiliência sem investimento em datacenter próprio.

---

## 💾 Etapa 2: Amazon S3 – Armazenamento Seguro e Econômico

**🔧 Ferramenta:** Amazon S3 (Simple Storage Service)  
**🎯 Objetivo:** Centralizar o armazenamento de arquivos corporativos com segurança, alta durabilidade e custo reduzido.

### 🔍 Como será implementado:

- Criação de buckets organizados por departamento e tipo de conteúdo.
- Aplicação de **políticas de ciclo de vida** para migração automática de dados inativos para S3 Glacier.
- Implementação de versionamento e criptografia padrão (SSE).

### 💡 Principais ganhos:

- Eliminação de gastos com servidores e dispositivos físicos de backup.
- Escalabilidade ilimitada com pagamento por uso.
- Aderência a políticas de compliance e LGPD com controle de acesso e auditoria.

---

## 🧮 Etapa 3: Amazon RDS – Banco de Dados Gerenciado

**🔧 Ferramenta:** Amazon RDS (Relational Database Service)  
**🎯 Objetivo:** Migrar o banco de dados local para uma solução gerenciada, reduzindo riscos, falhas e sobrecarga de equipe técnica.

### 🔍 Como será implementado:

- Escolha do mecanismo **MySQL** por compatibilidade e custo-benefício.
- Habilitação de backups automáticos e Multi-AZ para alta disponibilidade.
- Monitoramento via Amazon CloudWatch e escalonamento vertical conforme demanda.

### 💡 Principais ganhos:

- Menor esforço operacional com gerenciamento automatizado.
- Alta disponibilidade sem necessidade de DBA full-time.
- Segurança integrada e controle de acesso refinado.

---

## ✅ Conclusão

A adoção da computação em nuvem via serviços da AWS representa um passo estratégico para a Abstergo Industries, com foco em:

- 💸 Redução de custos operacionais imediatos
- ⚙️ Aumento da eficiência técnica e operacional
- 📈 Escalabilidade conforme o crescimento do negócio

Essa implementação posiciona a empresa como **competitiva, segura e preparada** para o futuro digital do setor farmacêutico.

---

## 📎 Anexos (opcional)

- Estimativa de custos mensal com AWS
- Arquitetura em nuvem da solução
- Prints ou screenshots da implementação

---

*Este relatório foi elaborado com base em conhecimentos práticos de Cloud AWS, com foco na aplicação real em ambientes empresariais. Pode ser utilizado como referência para portfólio profissional.*
