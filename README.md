# SPRINT DE GESTÃO ÁGIL DE PROJETOS E PRODUTOS
## FERRAMENTAS UTILIZADAS NO MVP
Miro: desenvolvimento de uma lean inception para idealização e delimitação do escopo do MVP  
Visual Studio: desenvolvimento de protótipos e produto final  
Jira: gestão do backlog do produto e do projeto 

## LEAN INCEPTION
### KICKOFF
Esse MVP tem como escopo a idealização e planejamento do software de monitoramento SISTEMA SUPERVISÒRIO.

A empresa cliente é dona de um conjunto de equipamentos de pistões hidráulicos de alta precisão para movimento de cargas de até 300ton e realiza serviços na área da engenharia civil. Cada conjunto de quatro equipamentos é controlado por um painel de automação contendo um CLP (Controlador Lógico Programável) e é acionado por um sistema manual por operadores distintos.

O objetivo deste projeto é o desenvolvimento de uma aplicação em .NET Framework para gerenciamento, controle e monitoramento em tempo real dos dispositivos e processos do cliente.

### EQUIPE
* PO: Rafael
* Scrum Master: Rafael
* Desenvolvedor Backend: Rafael
* Desenvolvedor Frontend: Rafael

### VISION
* PARA responsáveis pela operação dos equipamentos sendo cliente e cliente final (Operadores Especializados e Engenheiros)
* QUE estejam realizando obras em grande escala com componentes de alta carga. ex: Estádios e pontes. 
* O SISTEMA SUPERVISÒRIO
* É um aplicativo desktop em C# .NET Framework.
* QUE gerencia processos, controla a movimentação de equipamentos e monitora o estado do sistema em tempo real.
* DIFERENTE de sistemas que possuem apenas controles manuais o nosso sistema possui automação de processos, acompanhamento em tempo real do sistema e pose ser conectado via rede com o painel do controlador possibilitando mobilidade ao operador 
* NOSSO PRODUTO oferece uma solução integrada e automatizada para o gerenciamento, controle e monitoramento de múltiplos equipamentos buscando assim maior dinamismo na operação e melhor visibilidade no controle de processos.

### IS - IS NOT - DOES - DOES NOT DO
### IS
* Um aplicativo desktop para monitoramento e controle dos equipamentos utilizados nas obras de grande escala do cliente.
* Plataforma que fornece informações em tempo real sobre o estado e funcionamento dos equipamentos.
### IS NOT
* Um sistema para controle financeiro ou de custos relacionados às obras.
* Um aplicativo de gestão de pessoal ou alocação de recursos humanos.
### DOES
* Gerenciamento de equipamentos conectados ao painel de automação.
* Monitoramento em tempo real dos dispositivos, incluindo alertas de falhas ou mau funcionamento.
* Registro e histórico de operações realizadas pelos operadores.
* Controle automatizado de processos previamente manuais.

### DOES NOT DO
* Planejamento de cronogramas de obras ou atividades.
* Gestão de materiais ou estoque relacionado às operações do cliente.
* Controle financeiro das operações realizadas.

### GOALS
* Aumentar a eficiência operacional:
    * Reduzir a necessidade de intervenção manual nos processos de movimentação e monitoramento.
    * Permitir maior mobilidade e autonomia para os operadores através da integração com o painel do controlador via rede.
* Melhorar a segurança:
    * Monitoramento em tempo real para identificar possíveis falhas antes de ocorrerem acidentes.
    * Registro das operações para auditorias e melhoria contínua.
* Aprimorar a visibilidade dos processos:
    * Disponibilizar informações detalhadas e em tempo real para enge7nheiros e operadores.
    * Possibilitar geração de relatórios analíticos para avaliação e planejamento de melhorias.

### PERSONAS
* João, "o operador"
    * 45 anos; técnico mecânico com vasta experiência prática.
    * Responsável pela operação direta dos pistões hidráulicos no local da obra.
    * Precisa de um sistema simples e confiável que permita monitorar os equipamentos de forma remota e segura.

* Carla, "a engenheira responsável"
    * 38 anos; engenheira civil especializada em grandes obras.
    * Supervisiona o andamento das operações e precisa de informações atualizadas sobre o status dos equipamentos para tomar decisões estratégicas.
    * Necessita de um sistema que facilite a geração de relatórios e permita acompanhar remotamente os equipamentos.

* Lucas, "o técnico de automação"
    * 29 anos; especialista em CLP's e automação industrial.
    * Realiza a manutenção dos equipamentos e configurações do sistema.
    * Necessita de uma interface que facilite a análise de falhas e ajuste de parâmetros técnicos.

### USER JOURNEYS
* João, "o operador"
    * Acessa o sistema SUPERVISÓRIO ao iniciar sua jornada de trabalho.
    * Visualiza o status dos equipamentos atribuídos à sua operação.
    * Durante a operação, recebe alertas em tempo real sobre anomalias e solicita manutenção, se necessário.

* Carla, "a engenheira responsável"
   * Acessa o sistema diariamente para acompanhar o progresso das operações.
   * Verifica relatórios de desempenho e identifica possíveis melhorias no processo.
   * Usa as informações para planejar manutenções preventivas e ajustar a alocação de recursos.

* Lucas, "o técnico de automação"
   * Recebe um alerta do sistema indicando a necessidade de manutenção.
   * Conecta-se ao sistema para analisar o log de falhas e determinar a causa.
   * Realiza ajustes ou repara os equipamentos, atualizando o status no sistema.

### FEATURE BRAINSTORMING
* Interface intuitiva com dashboards para análise de resultado de processo.
* Registro e histórico de operações realizadas pelos operadores.
* Geração automática de relatórios de desempenho e alertas.
* Módulo para análise de falhas e suporte à manutenção preditiva.
* Escalabilidade para suportar múltiplos conjuntos de equipamentos.
* Possibilidade de exportação de relatórios em formatos como PDF e Excel.
* Integração futura com dispositivos móveis para operadores em campo.

