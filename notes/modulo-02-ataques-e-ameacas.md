# Módulo 2 — Ataques e Agentes de Ameaças

**Curso:** Google Cybersecurity Certificate
**Tipo de material:** Anotações de estudo
**Idioma:** Português

## 1. Ataques anteriores de segurança cibernética

* **Vírus de computador:** código malicioso que pode se anexar a arquivos ou programas e se espalhar quando eles são executados. Pode causar danos aos dados e ao software.
* **Phishing:** uso de comunicações fraudulentas para enganar pessoas e induzi-las a revelar informações confidenciais, acessar links maliciosos ou executar ações prejudiciais.
* **Malware:** termo geral para softwares criados com a intenção de causar danos, comprometer dispositivos ou obter acesso indevido a sistemas e dados.

## 2. Os oito domínios do CISSP

O CISSP (*Certified Information Systems Security Professional*) é uma certificação profissional da área de segurança da informação. Seu conhecimento é organizado em oito domínios:

1. **Gerenciamento de segurança e riscos:** políticas, conformidade, gestão de riscos, continuidade dos negócios e aspectos legais.
2. **Segurança de ativos:** classificação, proteção, armazenamento, manutenção, retenção e descarte de dados e outros ativos.
3. **Arquitetura e engenharia de segurança:** aplicação de princípios e soluções técnicas para projetar sistemas seguros.
4. **Comunicação e segurança de redes:** proteção das redes, dos protocolos e das comunicações.
5. **Gerenciamento de identidade e acesso:** gerenciamento de identidades, autenticação, autorização e permissões.
6. **Avaliação e teste de segurança:** avaliação de controles, testes de segurança, auditorias e análise de resultados.
7. **Operações de segurança:** monitoramento, investigação, resposta a incidentes e aplicação de medidas preventivas.
8. **Segurança no desenvolvimento de software:** incorporação de práticas seguras ao desenvolvimento, teste e manutenção de aplicações.

Esses domínios são áreas de conhecimento que ajudam a organizar as diferentes responsabilidades da segurança da informação.

## 3. Tipos de ataques cibernéticos

### 3.1 Quebra de senha

É uma tentativa de descobrir ou obter uma senha para acessar dispositivos, sistemas, redes ou dados protegidos.

Técnicas estudadas incluem:

* **Força bruta:** tentativa de combinações de senhas até encontrar uma que funcione.
* **Ataque com tabela arco-íris:** uso de tabelas pré-computadas de hashes para tentar identificar senhas correspondentes, em determinadas condições.

A quebra de senhas pode envolver diferentes áreas de segurança, especialmente o controle de acesso e a proteção de sistemas e redes.

### 3.2 Engenharia social

É uma técnica de manipulação que explora o comportamento humano para obter informações, acesso ou outros benefícios indevidos.

Principais modalidades:

* **Phishing:** mensagens fraudulentas enviadas para enganar vítimas.
* **Smishing:** phishing realizado por SMS ou mensagens de texto.
* **Vishing:** fraude por chamadas telefônicas ou comunicação de voz.
* **Spear phishing:** ataque direcionado a uma pessoa ou grupo específico.
* **Whaling:** ataque direcionado a executivos ou outras pessoas de alto nível.
* **Phishing em redes sociais:** uso de perfis, mensagens ou informações dessas plataformas para enganar vítimas.
* **Comprometimento de e-mail comercial (BEC):** fraude em que o atacante se passa por alguém de confiança em um contexto empresarial para induzir ações, como transferências financeiras.
* **Ataque watering hole:** comprometimento de um site frequentado pelo grupo que o atacante deseja atingir.
* **USB baiting:** deixar um dispositivo USB estrategicamente para induzir alguém a conectá-lo ao computador.
* **Engenharia social física:** fingir ser funcionário, cliente ou fornecedor para conseguir acesso não autorizado a um local.

### 3.3 Ataques físicos

São incidentes que exploram o ambiente físico para comprometer dispositivos, instalações ou informações.

Exemplos:

* Cabos USB maliciosos.
* Unidades flash USB que contêm malware.
* Clonagem de cartões.
* *Skimming*, técnica de captura indevida de dados de cartões.

### 3.4 Inteligência artificial adversária

Refere-se ao uso de técnicas que exploram vulnerabilidades ou limitações de sistemas de inteligência artificial e aprendizado de máquina para manipular seus resultados ou apoiar ataques.

Os riscos dependem do sistema e do contexto. Por exemplo, entradas cuidadosamente manipuladas podem levar um modelo a produzir classificações incorretas.

### 3.5 Ataques à cadeia de suprimentos

Acontecem quando um atacante compromete um fornecedor, componente, sistema, aplicativo ou processo utilizado por outra organização para atingir o alvo final.

Esses ataques podem afetar várias organizações ao mesmo tempo, dependendo da quantidade de clientes ou sistemas que dependem do componente comprometido.

### 3.6 Ataques criptográficos

São ataques que exploram fraquezas em algoritmos, protocolos, implementações ou no uso da criptografia.

Exemplos:

* **Ataque de aniversário:** explora probabilidades estatísticas relacionadas a colisões de hash.
* **Ataque de colisão:** procura entradas diferentes que produzam o mesmo valor de hash.
* **Ataque de downgrade:** tenta fazer uma comunicação utilizar uma versão ou configuração de segurança mais fraca.

## 4. Tipos de agentes de ameaças

Um agente de ameaça é uma pessoa ou grupo capaz de realizar ações que colocam sistemas, dados ou organizações em risco. Suas motivações e capacidades variam.

### 4.1 Ameaças persistentes avançadas (APTs)

APTs (*Advanced Persistent Threats*) são operações de ameaça caracterizadas por capacidade técnica, planejamento e persistência. Podem envolver grupos que buscam permanecer por longos períodos em redes comprometidas sem serem detectados.

Possíveis objetivos incluem:

* Espionagem.
* Roubo de propriedade intelectual e segredos comerciais.
* Obtenção de informações estratégicas.
* Comprometimento de infraestrutura crítica.

### 4.2 Ameaças internas

São riscos associados a pessoas que possuem ou possuíram acesso legítimo a uma organização, como funcionários, ex-funcionários, fornecedores ou parceiros.

Exemplos de ações prejudiciais:

* Sabotagem.
* Espionagem.
* Divulgação não autorizada de informações.
* Uso indevido de dados ou privilégios de acesso.

Nem toda ameaça interna age intencionalmente: erros e negligência também podem causar incidentes.

### 4.3 Hacktivistas

São agentes que utilizam ações digitais para promover uma causa política, social ou ideológica.

Suas ações podem incluir campanhas de propaganda, divulgação de informações e ataques contra organizações que consideram contrárias aos seus objetivos.

### 4.4 Categorias de hackers

O termo *hacker* pode descrever pessoas com diferentes níveis de conhecimento e motivações. Uma distinção comum considera a autorização para realizar as atividades.

* **Hackers éticos (*white hat*):** atuam com autorização para avaliar sistemas, identificar vulnerabilidades e ajudar a melhorar a segurança.
* **Hackers não autorizados ou mal-intencionados (*black hat*):** acessam ou comprometem sistemas sem permissão para obter benefícios, causar danos ou realizar outras ações indevidas.
* **Hackers de chapéu cinza (*gray hat*):** podem identificar vulnerabilidades sem autorização prévia, mas suas motivações e ações variam. Encontrar uma falha não lhes concede permissão para explorá-la.

Outras pessoas podem agir por curiosidade, busca de reconhecimento, vingança, ganho financeiro ou mediante contratação. A motivação, por si só, não determina se uma atividade é autorizada ou legal.

## 5. Glossário do módulo

* **CISSP:** certificação profissional de segurança da informação conhecida como *Certified Information Systems Security Professional*.
* **Malware:** software malicioso desenvolvido para comprometer dispositivos, sistemas, redes ou dados.
* **Vírus:** tipo de malware que pode se anexar a arquivos ou programas e se espalhar por meio de sua execução.
* **Quebra de senha:** tentativa de descobrir ou obter credenciais protegidas por senha.
* **Engenharia social:** manipulação de pessoas para obter informações, acesso ou outros benefícios.
* **Phishing:** fraude que utiliza comunicações enganosas para induzir vítimas a revelar dados ou executar ações.
* **BEC:** comprometimento de e-mail comercial (*Business Email Compromise*), uma fraude que explora a confiança em comunicações empresariais.
* **Ataque à cadeia de suprimentos:** comprometimento de um fornecedor, componente ou processo para atingir outros alvos.
* **Ataque criptográfico:** tentativa de explorar fraquezas em mecanismos ou implementações criptográficas.
* **Engenharia social física:** manipulação de pessoas para obter acesso indevido a instalações.
* **USB baiting:** indução de alguém a conectar um dispositivo USB potencialmente malicioso.
* **Vishing:** fraude que utiliza comunicação de voz.
* **Watering hole:** ataque que compromete um site frequentado pelo grupo que o atacante deseja atingir.
* **Inteligência artificial adversária:** estudo e uso de técnicas que exploram vulnerabilidades ou limitações de sistemas de IA.

## 6. Revisão do módulo

Use estas perguntas para verificar sua compreensão:

* [ ] Qual é a diferença entre vírus e malware?
* [ ] Quais são os oito domínios do CISSP?
* [ ] Qual é a diferença entre phishing, smishing e vishing?
* [ ] Como um ataque à cadeia de suprimentos pode afetar várias organizações?
* [ ] Qual é a diferença entre uma ameaça interna e um agente externo?
* [ ] Como diferenciar hackers éticos, não autorizados e de chapéu cinza?
* [ ] O que caracteriza um ataque criptográfico?

---

*Anotações pessoais de estudo organizadas a partir dos temas estudados no Google Cybersecurity Certificate.*
