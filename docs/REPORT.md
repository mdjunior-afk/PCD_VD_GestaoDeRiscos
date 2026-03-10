# Dashboard de Riscos: Automação e Visualização para Mineradoras

**Curso:** Ciência de Dados e Inteligência Artificial  
**Professora:** Viviane Cristina Dias

## Resumo
A Appian Capital Brazil é um fundo de investimento privado especializado no setor de mineração, focado na aquisição e otimização operacional de ativos globais. Um dos seus cases de maior sucesso é a Atlantic Nickel, adquirida em 2018. Sob a gestão da Appian, a operação de Níquel Sulfetado (NiS) recebeu implementações cruciais para a redução de custos e avanços em estudos de exploração subterrânea, culminando na entrega de um Estudo de Pré-viabilidade (PFS) em 2024. 

Além disso, a Graphcoa destaca-se pelo desenvolvimento de grafite, insumo essencial para baterias de veículos elétricos. Este investimento reforça o compromisso estratégico da Appian com a transição energética e o fornecimento de metais críticos no Brasil.  

Outro ativo relevante é a OMNIGEM Energy, plataforma voltada ao desenvolvimento de soluções energéticas sustentáveis para suportar operações industriais e minerais. A OMNIGEM atua com foco em eficiência energética, descarbonização e segurança no suprimento de energia, alinhando-se à estratégia da Appian de integrar práticas ESG e reduzir riscos operacionais e financeiros por meio de uma matriz energética mais limpa e resiliente. 

Alinhada a essa estratégia de crescimento, a Appian prioriza a mitigação de riscos financeiros e laborais em suas operações. Para solucionar a atual dificuldade de visualização e análise de dados críticos, o presente projeto desenvolveu um Data Warehouse. Esta solução centraliza informações relevantes, permitindo que os stakeholders compreendam e gerenciem os riscos de forma mais ágil, visual e amigável, garantindo maior segurança na tomada de decisão.

...

## Diagnóstico da situação-problema
Segundo a ISO 31000:2018, norma internacional que estabelece diretrizes para a gestão de riscos, o risco é caracterizado como o efeito da incerteza sobre os objetivos organizacionais, podendo se manifestar de forma positiva, negativa ou ambígua, traduzindo-se em oportunidades ou ameaças para as empresas.

Nesse contexto, a Appian Capital, gestora especializada no setor de mineração, administra uma matriz de riscos ampla e complexa em seus ativos, contemplando dimensões que variam desde a segurança e integridade dos trabalhadores até a viabilidade econômico-financeira das operações. A classificação desses riscos é realizada por meio de uma matriz 5x5, que combina critérios de probabilidade e impacto para determinar o nível de severidade associado a cada evento identificado.

Atualmente, a organização enfrenta desafios significativos relacionados à visualização, consolidação e interpretação dessas informações. Os dados de riscos são gerados por um sistema interno e posteriormente exportados para o Power BI. Entretanto, a ferramenta apresenta limitações relevantes, como a ausência de uma visualização clara dos responsáveis, dos controles existentes, do status das ações mitigadoras e de indicadores de atraso, o que dificulta a representação fiel da criticidade e da estrutura da matriz de riscos. Em decorrência dessas restrições, a equipe depende de processos majoritariamente manuais para consolidar e apresentar as informações, comprometendo a agilidade na tomada de decisão, elevando a probabilidade de inconsistências e reduzindo o potencial analítico da gestão.

Esse cenário se torna ainda mais crítico quando considerado o volume de riscos gerenciados: sendo 17 associados ao Omnigen Energy, 25 à Atlantic Nickel, 14 à Graphcoa e mais de 50 relacionados ao ambiente Underground. Além disso, os relatórios de acompanhamento são produzidos em diferentes frequências, incluindo ciclos quinzenais, mensais para a Atlantic Nickel e também sob demanda, conforme necessidades específicas de análise e monitoramento. Nesse contexto, a elaboração manual de cada relatório demanda, em média, entre 15 e 30 minutos. Considerando a quantidade de riscos monitorados e a recorrência desses relatórios, o processo torna-se repetitivo e operacionalmente oneroso, além de suscetível a falhas humanas.

Durante o processo de diagnóstico, foram identificados outros desafios operacionais relatados pela Appian Capital, entre eles a ausência de um formulário estruturado para registro de evidências de riscos e o preenchimento manual de formulários de gestão de mudanças. Contudo, optou-se por delimitar o escopo deste projeto à melhoria da visualização e interpretação da matriz de riscos, por ser o problema que melhor se alinha à proposta acadêmica de construção de um Data Warehouse. Os demais problemas identificados, embora relevantes, demandariam o desenvolvimento ou integração de ferramentas externas que extrapolam o escopo técnico definido para este trabalho.

...