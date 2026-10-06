//Pensei em aplicar sobre o drif natural x artificial, ficaria assim:
Robustez de modelos de Machine Learning diante de Concept Drift: uma avaliação experimental com mudanças 
naturais e induzidas em dados temporais

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
