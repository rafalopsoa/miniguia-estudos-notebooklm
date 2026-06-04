# miniguia-estudos-notebooklm
https://notebooklm.google.com/notebook/9dfea38e-29f9-41b3-a740-a9c9d8dfee71

Contexto e Objetivos: Fornecer Introdução aos Fundamentos e Prática do Teste de Software

Curadoria de Fontes:
https://www.zaptest.com/pt-br/testes-manuais-o-que-e-tipos-processos-abordagens-ferramentas-mais
https://bstqb.online/ctfl
https://www.youtube.com/watch?v=BMeOV1-senE
https://docente.ifsc.edu.br/joao.augusto/MaterialDidatico/2018-1/An%C3%A1lise%20e%20Projeto%20de%20Sistemas/Testes%20de%20Software

Engenharia de Prompts:

As perguntas abaixo foram feitas na guia Conversa com o objetivo de ter mais informações sobre as práticas de teste de software:

- O que diferencia um caso de teste de um cenário de teste?
- Quais são as diferenças entre teste de caixa-branca e caixa-preta?
- O que é um teste de caixa-cinzenta?
- Você como profissional de QA de Testes Manuais, explique com detalhes em que contextos usamos testes funcionais, não-funcionais, de integração, de aceitação, teste de fumaça, regressão e exploratórios. Liste em tópicos.

Miniguia de estudo:

a. Vídeo explicativo gerado no NotebookLM
https://notebooklm.google.com/notebook/9dfea38e-29f9-41b3-a740-a9c9d8dfee71/artifact/9f344d48-c6ba-4a3a-b00c-aedad2d33a58?utm_source=nlm_web_share&utm_medium=google_oo&utm_campaign=art_share_2&utm_content=&utm_smc=nlm_web_share_google_oo_art_share_2_

b. Resumo estruturado
  1. Definição e Objetivos Principais
O teste de software é muito mais do que apenas "executar o programa". É um conjunto de atividades intelectuais e técnicas que buscam avaliar artefatos de software
.
Verificação e Validação: O teste verifica se o software atende aos requisitos técnicos documentados e valida se ele realmente atende às necessidades dos usuários e stakeholders em um ambiente operacional
.
Prevenção e Deteção: Os objetivos incluem encontrar falhas e defeitos, avaliar a qualidade de produtos de trabalho (como designs e código), reduzir os níveis de risco e aumentar a confiança no sistema antes do lançamento
.
Teste vs. Depuração (Debugging): O teste é a atividade de Controle de Qualidade (QC) focada em encontrar a falha. Já a depuração é a atividade de desenvolvimento focada em diagnosticar a causa raiz, corrigir o código e eliminar o defeito
.
2. O Trio Fundamental: Erro, Defeito e Falha
Para ter uma boa base, é preciso entender a relação de causa e efeito que gera problemas no software:
Erro (Engano): É a ação humana incorreta (ex: o desenvolvedor entendeu mal a regra ou digitou algo errado por fadiga)
.
Defeito (Bug): É a consequência do erro inserida no produto de trabalho (o código ou a documentação com imperfeição)
.
Falha: Ocorre quando o código com defeito é executado e o sistema se comporta de forma inesperada, deixando de executar a função exigida
.
3. Os 7 Princípios dos Testes de Software
A prática do QA é regida por sete dogmas universais adotados pelo ISTQB
:
O teste mostra a presença de defeitos, não a sua ausência: Testar reduz a probabilidade de existirem bugs, mas não pode provar de forma absoluta que o sistema é 100% perfeito
.
Testes exaustivos são impossíveis: Testar todas as combinações de dados e cenários é inviável; foca-se o esforço analisando riscos e prioridades
.
Testes antecipados economizam tempo e dinheiro: O conceito de Shift-Left indica que testar cedo (como revisar requisitos antes do código) evita que defeitos se multipliquem em fases caras
.
O agrupamento de defeitos: Um pequeno número de módulos ou componentes geralmente concentra a maior parte dos bugs (Princípio de Pareto)
.
O Paradoxo do Pesticida (Os testes se desgastam): Repetir os mesmos testes à exaustão não revelará novos bugs. É preciso renovar os cenários de teste frequentemente
.
O teste depende do contexto: A abordagem muda conforme o sistema. Testa-se um e-commerce de forma diferente da de um software hospitalar
.
A falácia da ausência de erros: Consertar todos os bugs é inútil se o sistema construído não atender às reais necessidades de negócio e expectativas do usuário
.
4. A Prática: O Ciclo de Vida de Teste (STLC)
Na prática, o teste acompanha o Ciclo de Vida de Desenvolvimento (SDLC) passo a passo, em fases estruturadas
:
Planejamento, Monitoramento e Controle: Avaliação de riscos, criação do Plano de Teste, escopo, ferramentas, orçamentos e definição dos critérios de entrada e saída (o que autoriza o início e o fim dos testes)
.
Análise e Modelagem (Design): Identifica-se o que testar (Condições) e elaboram-se os Casos de Teste detalhados (como testar), incluindo o passo a passo, a massa de dados e o resultado esperado
.
Implementação e Execução: Configuração do ambiente e execução técnica dos casos de teste. É aqui que os resultados reais são comparados com os esperados e os defeitos são reportados aos desenvolvedores
.
Encerramento e Conclusão: Compilação de métricas, lições aprendidas e relatórios sumários atestando a qualidade final da entrega
.
5. Níveis, Tipos e Técnicas de Teste
A prática se divide em fatias e metodologias para organizar a cobertura e evitar redundâncias:
Níveis de Teste: Ocorrem conforme o software é construído, começando no Teste de Componente (Unidade) (feito por desenvolvedores no código isolado), passando para Integração, Teste de Sistema (o produto como um todo), até o Teste de Aceitação (focado no negócio e no usuário final)
.
Tipos de Teste: Podem ser Funcionais (o que o sistema deve fazer), Não-Funcionais (usabilidade, confiabilidade, segurança e performance), além de Confirmação/Reteste (validar se o bug foi realmente corrigido) e Regressão (garantir que nada em volta parou de funcionar)
.
Técnicas de Design (Derivação de Cenários):
Caixa-Preta (Funcionais): Focam na especificação, sem ver o código. Envolvem Particionamento de Equivalência, Análise de Valor Limite, Tabela de Decisão e Transição de Estados
.
Caixa-Branca (Estruturais): Focam na cobertura direta do código (instruções e ramificações)
.
Baseadas na Experiência: Baseiam-se na intuição e vivência técnica, aplicando Suposição de Erros e Testes Exploratórios
.
6. Gestão de Defeitos e Métricas
O profissional de QA atua de forma analítica com os resultados para promover correções.
Ciclo de Vida do Defeito: Um defeito possui um fluxo documentado (Novo → Atribuído → Aberto → Corrigido → Reteste → Verificado → Fechado/Reaberto) para evitar que se perca no processo
.
Priorização: Classifica-se estrategicamente a falha pela sua Severidade (o impacto técnico grave, ex: servidor travado) versus sua Prioridade (o quão urgente o negócio precisa da correção)
.
Métricas e Controle: O trabalho gera transparência usando KPIs como Cobertura de Requisitos, Taxa de Aprovação de Casos de Teste e a Eficiência de Remoção de Defeitos (DRE) — o qual mede se o QA está conseguindo capturar as falhas internamente antes do cliente achá-las em produção.

Prompts reutilizáveis:

- Você é um especialista em QA com uma excelente didática detalhada. Liste os pontos chave resumidos referentes aos fundamentos e prática dos testes de software.
- Você como profissional de QA de Testes Manuais, explique com detalhes em que contextos usamos testes funcionais, não-funcionais, de integração, de aceitação, teste de fumaça, regressão e exploratórios. Liste em tópicos.
