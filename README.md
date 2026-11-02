```markdown
Título provisório

Robustez de modelos de Machine Learning sob Concept Drift: comparação entre mudanças naturais eartificialmente
induzidas em dados temporais

Pergunta de pesquisa

Como diferentes tipos de concept drift, naturais e artificialmente induzidos, afetam o desempenho de modelos de Machine Learning e
a eficácia de diferentes estratégias de adaptação?

Estrutura:
        
                    PESQUISA
                       │
          ┌────────────┴────────────┐
          │                         │
     DADOS REAIS               DADOS CONTROLADOS
          │                         │
    drift natural             drift artificial
          │                         │
          └────────────┬────────────┘
                       │
                       ▼
                MODELOS DE ML
                       │
                       ▼
             DETECÇÃO DE DRIFT
                       │
                       ▼
              ESTRATÉGIAS DE
                 ADAPTAÇÃO
                       │
                       ▼
                 AVALIAÇÃO
                       │
          ┌────────────┴────────────┐
          ▼                         ▼
      ROBUSTEZ                  RECUPERAÇÃO
          │                         │
          └────────────┬────────────┘
                       ▼
                COMPARAÇÃO
          NATURAL × ARTIFICIAL

atualizações: 
09/10 - o resultado False indica que existe pelo menos uma posição em que uma data aparece antes de outra data menor
(tenho que investigar)
aqui já passamos pelas fases: carregamento do dataset; importação do River e carregamento do Elec2; c
onversão para DataFrame; organização das observações em uma tabela pandas; análise das dimensões e estamos na
exploração temporal


          
