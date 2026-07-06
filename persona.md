# 👥 Atividade – Criando Personas para um Projeto Digital
**📚 Disciplina:** Laboratório Web / Engenharia de Software  
**🗄️ Aluna:** Yasmin  
**🎯 Foco da Atividade:** Criar Personas relacionadas aos profissionais responsáveis pelas **infraestruturas e bancos de dados** dos sistemas de ambos os projetos (BookHub e CabanaPay).

---

## 📑 Introdução e Contexto
Como responsável pela infraestrutura, backend e banco de dados dos sistemas, as minhas personas não são apenas os usuários finais comuns, mas sim os **profissionais técnicos (usuários internos)** que precisam dar suporte, escalar, monitorar e garantir a segurança de dados de ambas as plataformas: **BookHub** (Plataforma/Comunidade literária) e **CabanaPay** (Sistema de pagamentos digitais).

---

## 🗄️ Persona 1: Sistema BookHub (Foco em Dados e Catálogos)

### 📋 Ficha Temática da Persona

| Campo | Informação |
| :--- | :--- |
| **👤 Nome** | Thiago Rocha |
| **🎂 Idade** | 29 anos |
| **💼 Profissão** | Administrador de Banco de Dados (DBA) & Engenheiro de Dados |
| **📍 Cidade** | São Paulo - SP |
| **🎓 Escolaridade** | Especialização em Engenharia de Dados e Bancos de Dados Não-Relacionais |
| **💻 Tecnologias utilizadas** | Notebook corporativo de alta performance, monitor ultra-wide, smartphone Android. Conectado mais de 10 horas por dia. Nível de informática: **Avançado (🔵)**. |
| **🎯 Objetivos** | Otimizar as buscas complexas de livros (por tags, autores, avaliações); garantir integridade relacional quando milhares de usuários atualizam resenhas ao mesmo tempo; e estruturar backups automáticos eficientes. |
| **😟 Dores** | Lentidão na indexação de novos livros; concorrência de escrita quando uma resenha viraliza; e dificuldade em lidar com dados semiestruturados vindos de APIs externas de editoras. |
| **❤️ Necessidades** | Um banco de dados bem modelado (misto: Relacional para transações e NoSQL/Elasticsearch para buscas textuais); painéis de monitoramento de queries lentas; e isolamento de ambientes de homologação e produção. |
| **💬 Frase** | *"Um banco de dados lento destrói a experiência de leitura e navegação do usuário antes mesmo de ele abrir a primeira página."* |
| **🖼️ Foto** | ![Thiago Rocha - DBA](https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&q=80&w=150&h=150) *(Imagem Ilustrativa)* |

---

## 💼 Persona 2: Sistema CabanaPay (Foco em Infraestrutura, Disponibilidade e Segurança)

### 📋 Ficha Temática da Persona

| Campo | Informação |
| :--- | :--- |
| **👤 Nome** | Fernanda Lima |
| **🎂 Idade** | 34 anos |
| **💼 Profissão** | Engenheira de DevOps e Infraestrutura em Nuvem |
| **📍 Cidade** | Belo Horizonte - MG |
| **🎓 Escolaridade** | Certificação AWS Certified Solutions Architect e Graduação em Engenharia de Software |
| **💻 Tecnologias utilizadas** | MacBook Pro, celular iOS, Smartwatch corporativo para alertas de incidentes em tempo real. Conectada 24/7 (regime de sobreaviso). Nível de informática: **Avançado (🔵)**. |
| **🎯 Objetivos** | Manter o CabanaPay com 99,99% de disponibilidade (uptime); automatizar o pipeline de deploy (CI/CD) para atualizações sem quedas; e blindar a infraestrutura contra ataques virtuais. |
| **😟 Dores** | Quedas inesperadas de microsserviços durante picos de transações; latência alta em APIs de operadoras de cartão de crédito; e falta de centralização e clareza nos logs de erros de pagamento. |
| **❤️ Necessidades** | Infraestrutura escalável como código (IaC/Terraform); uso de microsserviços e mensageria (RabbitMQ/Kafka) para tolerância a falhas; criptografia de ponta a ponta e cofres de chaves de API altamente seguros (Vault). |
| **💬 Frase** | *"Em um sistema de pagamentos, um segundo de instabilidade significa milhares de reais perdidos e a quebra total da confiança do cliente."* |
| **🖼️ Foto** | ![Fernanda Lima - DevOps](https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&q=80&w=150&h=150) *(Imagem Ilustrativa)* |

---

## 🤖 Uso de Inteligência Artificial e Documentação do Processo

* **Qual IA utilizou:** Gemini (Google).
* **O prompt utilizado:** > *"Atue como Yasmin, estudante de Engenharia de Software encarregada da parte de infraestrutura e banco de dados dos projetos BookHub e CabanaPay. Crie duas personas completas baseadas no template fornecido: uma focada na gestão de dados/catálogos do BookHub e outra focada na segurança/alta disponibilidade do CabanaPay. Siga rigorosamente os campos e formatos solicitados."*
* **O que foi modificado na resposta gerada pela IA:** Ajustei as dores de infraestrutura para que ficassem estritamente alinhadas com o modelo de negócios de cada projeto (adicionando menções específicas à indexação de resenhas no BookHub e à latência de cartões no CabanaPay) e organizei os campos dentro de tabelas Markdown limpas para postagem no GitHub. Ajustei os links de imagem para corresponder ao gênero dos personagens.
* **Como a IA contribuiu para a criação das Personas:** A IA acelerou a geração das características comportamentais, forneceu exemplos técnicos realistas de ferramentas que esses profissionais utilizam (como Elasticsearch e Terraform) e estruturou rapidamente o esqueleto do documento Markdown.

---

## 🏆 Reflexão Final

**1️⃣ Por que conhecer o usuário é importante antes de desenvolver um sistema?** Porque evita o desperdício de tempo e recursos desenvolvendo arquiteturas ou funcionalidades que não resolvem as dores reais. No caso da infraestrutura, conhecer a volumetria e o perfil de acesso do usuário dita se precisamos gastar mais com servidores robustos ou se podemos adotar soluções mais leves e baratas.

**2️⃣ Como uma Persona pode contribuir para melhorar um site ou aplicativo?** Ela serve como uma bússola para o time de desenvolvimento. Quando discutimos decisões técnicas difíceis (ex: como tratar falhas de conexão em pagamentos no CabanaPay), olhamos para a Persona para entender qual o nível de tolerância e urgência que a situação exige.

**3️⃣ O que você aprendeu durante esta atividade?** Aprendi que os sistemas não possuem apenas usuários finais leigos. Os profissionais técnicos que operam e mantêm o backend (DBAs, DevOps, SysAdmins) também são usuários cruciais que precisam de painéis intuitivos, logs bem estruturados e arquiteturas claras para trabalhar com eficiência.

**4️⃣ Como a Inteligência Artificial contribuiu para o desenvolvimento do seu trabalho?** A IA atuou como uma excelente parceira de *brainstorming*, ajudando a mapear de forma ágil as dores diárias de profissões complexas (como DBA e DevOps), aproximando o exercício acadêmico da realidade do mercado de tecnologia.
