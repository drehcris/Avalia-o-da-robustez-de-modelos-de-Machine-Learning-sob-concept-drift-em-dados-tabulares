```markdown
Título provisório

Robustez de modelos de Machine Learning sob Concept Drift: comparação entre mudanças naturais eartificialmente
induzidas em dados temporais

Pergunta de pesquisa

Como diferentes tipos de concept drift, naturais e artificialmente induzidos, afetam o desempenho de modelos de Machine Learning e
a eficácia de diferentes estratégias de adaptação?

Estrutura:
```text
        
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
