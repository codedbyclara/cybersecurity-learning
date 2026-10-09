# Módulo 4 — Ferramentas de Segurança e Evidências Digitais

**Curso:** Google Cybersecurity Certificate
**Tipo de material:** Anotações de estudo
**Idioma:** Português

## 1. Ferramentas comuns em segurança cibernética

Profissionais de segurança cibernética utilizam diferentes ferramentas para monitorar sistemas, identificar ameaças, investigar incidentes e proteger dados.

### 1.1 Registros (*Logs*)

Registros são históricos de eventos que ocorrem em sistemas, aplicativos, dispositivos e redes de uma organização.

Eles podem armazenar informações como tentativas de login, erros, alterações em arquivos e atividades de usuários.

A análise desses registros ajuda os profissionais a identificar comportamentos suspeitos, investigar incidentes e compreender o que aconteceu em um sistema.

**Geração de registros (*Logging*):** processo de registrar eventos para possibilitar seu monitoramento e sua análise.

### 1.2 SIEM

SIEM significa *Security Information and Event Management* — Gerenciamento de Informações e Eventos de Segurança.

Uma ferramenta SIEM coleta, centraliza e analisa dados de registros de diferentes fontes. Dependendo da solução e da configuração, ela pode correlacionar eventos, gerar alertas e ajudar os analistas a investigar possíveis incidentes.

Exemplo: um SIEM pode identificar várias tentativas de login malsucedidas seguidas de um acesso bem-sucedido e sinalizar a atividade para investigação.

Ferramentas estudadas:

* **Splunk:** plataforma de análise de dados que pode ser implantada em infraestrutura própria ou utilizada por meio de ofertas em nuvem.
* **Google Security Operations, anteriormente associado ao Chronicle:** plataforma de operações de segurança com recursos de análise e investigação de ameaças, oferecida como serviço em nuvem.

A forma de implantação depende do produto e da versão utilizados.

### 1.3 Playbooks

Um *playbook* é um conjunto documentado de instruções que orienta uma equipe sobre como executar determinadas tarefas ou responder a situações específicas.

Em segurança cibernética, um playbook pode definir etapas para investigar um alerta, conter um incidente, preservar evidências e comunicar os responsáveis.

Ele ajuda a padronizar procedimentos e a tornar a resposta mais consistente.

### 1.4 Analisador de protocolos de rede (*Packet Sniffer*)

É uma ferramenta utilizada para capturar e analisar pacotes de dados que trafegam por uma rede.

Pode ajudar a investigar problemas de conectividade, compreender protocolos e identificar comunicações suspeitas.

A captura de tráfego deve respeitar as autorizações e as regras de privacidade aplicáveis.

## 2. Ferramentas para proteger as operações comerciais

### 2.1 Programação

Programação é o processo de escrever instruções que um computador pode executar para realizar tarefas específicas.

Na segurança cibernética, a programação pode ser utilizada para automatizar tarefas, analisar registros, processar dados e desenvolver ferramentas de proteção.

### 2.2 Sistemas operacionais

Um sistema operacional gerencia os recursos de um computador e permite a interação entre aplicativos, hardware e usuários.

Exemplos:

* **Linux:** família de sistemas operacionais baseada no kernel Linux, com diversas distribuições de código aberto.
* **Windows:** família de sistemas operacionais desenvolvida pela Microsoft.
* **macOS:** sistema operacional desenvolvido pela Apple para computadores Mac.

Conhecer sistemas operacionais ajuda os profissionais de segurança a compreender permissões, processos, arquivos, usuários e configurações de proteção.

### 2.3 Vulnerabilidades web

Uma vulnerabilidade web é uma falha em um site, aplicativo web ou em seus componentes que pode ser explorada para comprometer a segurança.

Dependendo da falha, um atacante pode tentar acessar informações sem autorização, alterar dados, executar ações indevidas ou comprometer o funcionamento da aplicação.

A prevenção envolve práticas como desenvolvimento seguro, validação de entradas, controle de acesso, atualizações e testes de segurança.

### 2.4 Software antivírus e antimalware

É um tipo de software desenvolvido para prevenir, detectar e, quando possível, bloquear ou remover programas maliciosos.

As soluções modernas podem utilizar assinaturas, análise comportamental e outros métodos de detecção.

O antivírus é uma camada de proteção, mas não substitui atualizações, backups, controle de acesso e outras medidas de segurança.

### 2.5 Sistema de detecção de intrusão (IDS)

IDS significa *Intrusion Detection System*.

É um sistema que monitora atividades em dispositivos ou redes para identificar possíveis comportamentos maliciosos ou violações de políticas de segurança e gerar alertas.

Um IDS normalmente detecta e alerta; a prevenção ou o bloqueio automático são funções associadas a outros controles ou sistemas, como um IPS.

### 2.6 Criptografia

A criptografia utiliza técnicas matemáticas para proteger informações.

Na criptografia de dados, informações legíveis podem ser transformadas em um formato que só pode ser compreendido novamente por quem possui os meios necessários para decifrá-las, como a chave correta.

Seu uso pode contribuir para a confidencialidade. Outros mecanismos criptográficos também ajudam a verificar a integridade e a autenticidade dos dados.

### 2.7 Teste de penetração (*Penetration Testing*)

Também chamado de *pentesting*, é uma avaliação de segurança realizada por profissionais autorizados que simulam determinadas ações de um atacante para identificar e demonstrar vulnerabilidades.

O teste pode abranger sistemas, redes, sites, aplicativos e processos.

Deve ter escopo, regras e autorização definidos previamente. Seus resultados ajudam a priorizar correções e fortalecer a segurança.

## 3. Bancos de dados e SQL

### 3.1 Dados

Dados são representações de fatos, observações ou informações que podem ser armazenadas e processadas.

### 3.2 Banco de dados

Um banco de dados é uma coleção organizada de dados, estruturada para permitir armazenamento, consulta, atualização e gerenciamento.

### 3.3 SQL

SQL significa *Structured Query Language* — Linguagem de Consulta Estruturada.

É uma linguagem utilizada principalmente para definir estruturas, consultar e manipular dados em bancos de dados relacionais.

Exemplos de comandos:

* `SELECT`: consulta dados.
* `INSERT`: insere registros.
* `UPDATE`: altera registros existentes.
* `DELETE`: remove registros.
* `CREATE TABLE`: cria uma tabela.

O uso de comandos que alteram ou removem dados exige atenção às condições e às permissões aplicáveis.

## 4. Preservação de evidências digitais

Durante uma investigação de segurança, evidências digitais podem ajudar a determinar o que ocorreu, quando aconteceu e quais sistemas foram afetados.

Essas evidências precisam ser tratadas cuidadosamente para evitar alterações, perdas ou comprometimento de sua confiabilidade.

### 4.1 Proteção e preservação de evidências

É o processo de identificar, coletar, documentar, armazenar e proteger evidências digitais de forma apropriada.

Boas práticas incluem:

* Registrar quando, onde e como a evidência foi coletada.
* Restringir o acesso às pessoas autorizadas.
* Preservar os dados originais sempre que possível.
* Documentar o manuseio e as transferências da evidência.
* Utilizar mecanismos de verificação, como hashes, quando apropriado.

### 4.2 Ordem de volatilidade

A ordem de volatilidade é uma orientação para priorizar a coleta de dados conforme a rapidez com que podem desaparecer ou ser alterados.

Em geral, dados mais voláteis são coletados primeiro, quando isso é necessário e viável.

Exemplos:

* Conteúdo da memória RAM e processos em execução.
* Conexões de rede e outras informações temporárias do sistema.
* Dados armazenados em mídias persistentes, como discos.

A ordem exata depende do sistema, do incidente e dos objetivos da investigação. A coleta deve seguir os procedimentos autorizados e evitar alterações desnecessárias.

## 5. Glossário do módulo

* **Antivírus:** software utilizado para detectar, bloquear ou remover ameaças maliciosas.
* **Banco de dados:** coleção organizada de dados.
* **Dados:** representação de fatos, observações ou informações.
* **IDS:** sistema que monitora atividades para detectar possíveis intrusões e gerar alertas.
* **Linux:** família de sistemas operacionais baseada no kernel Linux.
* **Geração de registros (*logging*):** processo de registrar eventos em sistemas, aplicativos ou redes.
* **Log:** registro de um evento ocorrido em um sistema.
* **Packet sniffer:** ferramenta que captura e analisa pacotes de dados de rede.
* **Ordem de volatilidade:** sequência que orienta a priorização da coleta de dados conforme sua volatilidade.
* **Programação:** criação de instruções que computadores podem executar.
* **Preservação de evidências:** processo de proteger e documentar evidências para manter sua integridade e confiabilidade.
* **SIEM:** solução que coleta e analisa registros e eventos de segurança para apoiar o monitoramento e a investigação.
* **SQL:** linguagem utilizada para definir, consultar e manipular dados, especialmente em bancos relacionais.
* **Criptografia:** técnicas matemáticas utilizadas para proteger informações.
* **Pentesting:** avaliação autorizada que simula ações de atacantes para identificar vulnerabilidades.
* **Vulnerabilidade web:** falha de segurança em um site ou aplicativo web.
* **Playbook:** conjunto documentado de instruções para executar tarefas ou responder a situações específicas.

## 6. Revisão do módulo

* [ ] O que são logs e por que são importantes?
* [ ] Qual é a função de uma ferramenta SIEM?
* [ ] Qual é a diferença entre um IDS e um sistema de prevenção de intrusão?
* [ ] Para que serve um analisador de pacotes?
* [ ] Como a criptografia ajuda a proteger informações?
* [ ] O que é uma vulnerabilidade web?
* [ ] Qual é o objetivo de um teste de penetração?
* [ ] O que significa ordem de volatilidade?
* [ ] Por que a preservação de evidências é importante?
* [ ] Para que serve SQL?

---

*Anotações pessoais de estudo organizadas a partir dos temas estudados no Google Cybersecurity Certificate.*
