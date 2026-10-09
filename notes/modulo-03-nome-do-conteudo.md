# Módulo 3 — Frameworks, Ética e Conformidade

**Curso:** Google Cybersecurity Certificate
**Tipo de material:** Anotações de estudo
**Idioma:** Português

## 1. Estruturas de segurança cibernética

Frameworks de segurança cibernética são conjuntos de diretrizes, práticas recomendadas e processos que ajudam as organizações a identificar, avaliar e reduzir riscos relacionados à segurança da informação e à privacidade dos dados.

Eles ajudam a organizar as atividades de segurança e a estabelecer objetivos, responsabilidades e formas de acompanhar os resultados.

### 1.1 Etapas de uma estrutura de segurança

1. **Identificar e documentar as metas de segurança:** definir o que a organização precisa proteger.
2. **Definir diretrizes para atingir as metas:** estabelecer políticas, procedimentos e controles.
3. **Implementar processos robustos de segurança:** colocar as medidas de proteção em prática.
4. **Monitorar e comunicar os resultados:** avaliar a eficácia dos controles e comunicar riscos, falhas e melhorias necessárias.

### 1.2 Conceitos relacionados

* **Arquitetura de segurança:** estrutura composta por ferramentas, processos, tecnologias e outros componentes utilizados para proteger uma organização.
* **Governança de segurança:** práticas que orientam, definem e supervisionam os esforços de segurança da organização.
* **Controles de segurança:** salvaguardas projetadas para reduzir riscos específicos.
* **Ativo:** item que possui valor para uma organização, como dados, sistemas, equipamentos ou informações de clientes.

## 2. Tríade CIA

A tríade CIA é um modelo fundamental da segurança da informação. A sigla vem de *Confidentiality, Integrity and Availability*.

### 2.1 Confidencialidade (*Confidentiality*)

Garante que somente pessoas ou sistemas autorizados possam acessar determinadas informações.

**Exemplo:** utilizar permissões de acesso para impedir que pessoas não autorizadas visualizem dados confidenciais.

### 2.2 Integridade (*Integrity*)

Garante que os dados permaneçam corretos, completos e confiáveis, evitando alterações indevidas.

**Exemplo:** utilizar mecanismos de verificação para identificar se um arquivo foi modificado sem autorização.

### 2.3 Disponibilidade (*Availability*)

Garante que dados, sistemas e recursos estejam acessíveis quando necessários às pessoas autorizadas.

**Exemplo:** manter backups e mecanismos de recuperação para restaurar serviços após uma falha.

A tríade CIA ajuda as organizações a avaliar riscos e definir controles de segurança adequados.

## 3. Agentes de ameaça e riscos internos

Agentes de ameaça são pessoas, grupos ou outras entidades capazes de realizar ações que comprometam sistemas, dados ou operações.

Eles podem atuar em diferentes regiões do mundo e possuir motivações variadas. Equipes de segurança com diferentes experiências e perspectivas podem ajudar as organizações a compreender melhor as ameaças e seus possíveis impactos.

### Ameaças internas (*Insider Threats*)

Uma ameaça interna pode envolver funcionários, prestadores de serviço, fornecedores ou outras pessoas com acesso legítimo aos recursos de uma organização.

Uma pessoa insatisfeita pode representar um risco quando utiliza esse acesso para realizar ações prejudiciais. Entretanto, ameaças internas também podem surgir de erros, negligência ou credenciais comprometidas.

Exemplos:

* Divulgação indevida de informações.
* Sabotagem de sistemas.
* Uso inadequado de privilégios de acesso.
* Exposição acidental de dados confidenciais.

## 4. Conformidade e padrões de segurança

**Conformidade (*compliance*)** é o cumprimento de leis, regulamentos, normas e padrões aplicáveis a uma organização.

Ela pode envolver requisitos legais obrigatórios ou padrões adotados voluntariamente. A conformidade ajuda a orientar as práticas de segurança, mas não garante, sozinha, que todos os riscos estejam eliminados.

### 4.1 FERC e NERC

* **FERC (*Federal Energy Regulatory Commission*):** agência federal dos Estados Unidos que regula determinados aspectos do setor de energia.
* **NERC (*North American Electric Reliability Corporation*):** organização responsável por desenvolver e fiscalizar padrões de confiabilidade do sistema elétrico norte-americano, incluindo requisitos de segurança cibernética aplicáveis.

Essas entidades e os padrões relacionados contribuem para a preparação, mitigação e comunicação de incidentes que possam afetar a confiabilidade do sistema elétrico.

### 4.2 FedRAMP

O *Federal Risk and Authorization Management Program* é um programa do governo federal dos Estados Unidos que padroniza a avaliação, autorização e o monitoramento de serviços de computação em nuvem utilizados por agências federais.

Seu objetivo inclui promover uma abordagem consistente para avaliar a segurança desses serviços.

### 4.3 CIS

O *Center for Internet Security* (CIS) é uma organização que desenvolve recursos e recomendações para melhorar a segurança cibernética.

Entre seus recursos estão os **CIS Controls**, um conjunto de medidas priorizadas que ajudam as organizações a fortalecer suas defesas.

### 4.4 GDPR

O GDPR (*General Data Protection Regulation*), conhecido em português como Regulamento Geral sobre a Proteção de Dados da União Europeia, estabelece regras para o tratamento de dados pessoais.

Ele protege os direitos das pessoas e pode se aplicar a organizações situadas fora da União Europeia quando as condições previstas no regulamento são atendidas.

### 4.5 PCI DSS

O *Payment Card Industry Data Security Standard* é um padrão de segurança voltado à proteção de dados de cartões de pagamento.

Aplica-se às organizações abrangidas que armazenam, processam ou transmitem esses dados, além de outras entidades relevantes conforme os requisitos do padrão.

### 4.6 HIPAA

A *Health Insurance Portability and Accountability Act* é uma lei federal dos Estados Unidos, promulgada em 1996, que inclui disposições sobre a proteção de determinadas informações de saúde.

Entre suas regras estão:

* **Regra de Privacidade (*Privacy Rule*):** estabelece requisitos para o uso e a divulgação de informações de saúde protegidas.
* **Regra de Segurança (*Security Rule*):** estabelece salvaguardas para proteger informações de saúde protegidas em formato eletrônico.
* **Regra de Notificação de Violação (*Breach Notification Rule*):** estabelece requisitos de notificação em determinadas situações de violação de informações protegidas.

A HIPAA não proíbe toda divulgação de informações de saúde: determinados usos e divulgações são permitidos ou exigidos pelas regras aplicáveis.

### 4.7 ISO

A *International Organization for Standardization* (ISO) desenvolve normas internacionais para diferentes setores, incluindo tecnologia, segurança da informação, fabricação e gestão.

Na área de segurança da informação, a família ISO/IEC 27000 inclui normas e orientações relacionadas a sistemas de gestão da segurança da informação.

### 4.8 Relatórios SOC 1 e SOC 2

Os relatórios SOC (*System and Organization Controls*) são utilizados para avaliar controles de organizações prestadoras de serviços.

* **SOC 1:** concentra-se nos controles de uma organização de serviços que podem ser relevantes para os controles internos sobre relatórios financeiros de seus clientes.
* **SOC 2:** avalia controles relacionados aos critérios de serviços de confiança, como segurança, disponibilidade, integridade de processamento, confidencialidade e privacidade, conforme o escopo do relatório.

Os relatórios SOC não são simplesmente relatórios sobre permissões de usuários: seu escopo depende do tipo de relatório e dos controles avaliados.

### 4.9 NIST Cybersecurity Framework (CSF)

O *Cybersecurity Framework* do *National Institute of Standards and Technology* (NIST) fornece orientações para que as organizações compreendam, avaliem, priorizem e gerenciem riscos de segurança cibernética.

É um framework que pode ser adaptado a diferentes organizações e contextos.

## 5. Ética e segurança cibernética

A ética em segurança cibernética envolve princípios que orientam decisões e comportamentos profissionais responsáveis.

Profissionais de segurança podem ter acesso a informações confidenciais e sistemas críticos. Por isso, devem agir com responsabilidade e respeitar os limites legais e éticos de suas atividades.

### 5.1 Confidencialidade

É o dever de proteger informações confidenciais e impedir que sejam acessadas ou divulgadas sem autorização.

### 5.2 Proteção da privacidade

Consiste em proteger informações pessoais contra acesso, uso, compartilhamento ou tratamento não autorizado.

### 5.3 Legalidade

As atividades de segurança devem respeitar as leis, os regulamentos e as autorizações aplicáveis. Ter conhecimento técnico não significa ter permissão para acessar ou testar qualquer sistema.

### 5.4 Boas práticas éticas

Um profissional de segurança deve:

* Agir de maneira honesta, imparcial e responsável.
* Respeitar a legislação e as autorizações recebidas.
* Ser transparente sobre os métodos utilizados e os resultados encontrados.
* Basear suas conclusões em evidências.
* Proteger as informações obtidas durante o trabalho.
* Manter-se atualizado e aprimorar continuamente suas habilidades.
* Comunicar riscos e problemas de maneira responsável.

## 6. Contra-ataques e vigilantismo digital

No contexto da segurança cibernética, *vigilantismo digital* pode se referir a tentativas de indivíduos ou organizações de realizar ações por conta própria contra supostos atacantes, sem a devida autoridade legal.

Nos Estados Unidos, acessar sistemas de terceiros, danificar equipamentos ou interferir em redes como forma de retaliação pode gerar consequências legais, mesmo quando a intenção declarada é se defender.

O International Committee of the Red Cross (ICRC), conhecido em português como Comitê Internacional da Cruz Vermelha, utiliza o termo ICJ em algumas referências em inglês para o *International Committee of the Red Cross*. A sigla correta em inglês é ICRC.

É importante distinguir a discussão sobre princípios humanitários aplicáveis a operações cibernéticas em conflitos armados da legislação que se aplica a uma pessoa comum. Esses princípios não concedem, por si só, autorização geral para realizar contra-ataques.

**Princípio prático:** diante de um incidente, priorize proteger os próprios sistemas, preservar evidências, comunicar o ocorrido e recorrer às equipes responsáveis ou às autoridades competentes. Não tente invadir ou danificar sistemas de terceiros em retaliação.

## 7. Glossário do módulo

* **Ativo (*asset*):** item que possui valor para uma organização.
* **Disponibilidade (*availability*):** propriedade que garante acesso aos dados e recursos quando necessário às pessoas autorizadas.
* **Confidencialidade (*confidentiality*):** proteção contra acesso ou divulgação não autorizados.
* **Integridade (*integrity*):** preservação da correção, autenticidade e confiabilidade dos dados.
* **Conformidade (*compliance*):** cumprimento de requisitos legais, regulatórios, normativos ou internos aplicáveis.
* **Tríade CIA:** modelo baseado em confidencialidade, integridade e disponibilidade.
* **CSF do NIST:** framework de orientação para gerenciar riscos de segurança cibernética.
* **Controles de segurança:** medidas destinadas a reduzir riscos.
* **Arquitetura de segurança:** organização dos componentes e processos utilizados para proteger sistemas e informações.
* **Governança de segurança:** práticas de direção, supervisão e orientação das atividades de segurança.
* **Hacktivista:** pessoa que utiliza atividades de hacking para promover uma causa política ou ideológica.
* **HIPAA:** lei federal dos Estados Unidos que inclui regras para a proteção de determinadas informações de saúde.
* **PHI (*Protected Health Information*):** informações de saúde protegidas conforme a legislação norte-americana aplicável.
* **PII (*Personally Identifiable Information*):** informações que podem identificar uma pessoa, direta ou indiretamente, conforme o contexto.
* **SPII (*Sensitive Personally Identifiable Information*):** informações pessoais identificáveis consideradas sensíveis e sujeitas a cuidados reforçados em determinados contextos.
* **Ética de segurança:** princípios que orientam decisões profissionais responsáveis em segurança cibernética.
* **Framework de segurança:** conjunto organizado de diretrizes e práticas para gerenciar riscos.

## 8. Revisão do módulo

* [ ] Quais são os três pilares da tríade CIA?
* [ ] Qual é a diferença entre um framework e um controle de segurança?
* [ ] O que significa conformidade?
* [ ] Qual é a finalidade do GDPR?
* [ ] Qual é a diferença entre os relatórios SOC 1 e SOC 2?
* [ ] Quais são as principais regras da HIPAA abordadas neste módulo?
* [ ] Por que uma ameaça interna pode ser intencional ou acidental?
* [ ] Quais princípios éticos devem orientar um profissional de segurança?
* [ ] Por que o contra-ataque digital pode trazer riscos legais?

---

*Anotações pessoais de estudo organizadas a partir dos temas estudados no Google Cybersecurity Certificate.*
