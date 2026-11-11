# Rastreabilidade — Grupo S44

Esta matriz relaciona as histórias de usuário cadastradas como Issues aos requisitos funcionais e casos de uso utilizados no SRS do Grupo S44.

| História | RFs relacionados | Casos de uso | MVP |
|---|---|---|---|
| [S44-US01](https://github.com/TeoZ08/engenharia-requisitos-s44/issues/1) | RF01 | UC01 | Sim |
| [S44-US02](https://github.com/TeoZ08/engenharia-requisitos-s44/issues/2) | RF02, RF03, RF04 | UC01 | Sim |
| [S44-US03](https://github.com/TeoZ08/engenharia-requisitos-s44/issues/3) | RF06, RF07, RF08 | UC02 | Sim |
| [S44-US04](https://github.com/TeoZ08/engenharia-requisitos-s44/issues/4) | RF05, RF07, RF09 | UC04, UC09 | Sim |
| [S44-US05](https://github.com/TeoZ08/engenharia-requisitos-s44/issues/5) | RF10 | UC05 | Sim |
| [S44-US06](https://github.com/TeoZ08/engenharia-requisitos-s44/issues/6) | RF12 | UC06 | Não |
| [S44-US07](https://github.com/TeoZ08/engenharia-requisitos-s44/issues/7) | RF13 | UC07 | Não |
| [S44-US08](https://github.com/TeoZ08/engenharia-requisitos-s44/issues/8) | RF14 | UC08 | Não |
| [S44-US09](https://github.com/TeoZ08/engenharia-requisitos-s44/issues/9) | RF11 | UC03 | Não |

## Observação

As relações acima foram mantidas em coerência com o SRS v0.95 e devem continuar alinhadas com a numeração adotada na versão final. Caso um requisito ou caso de uso seja renumerado ou alterado, esta matriz e as Issues correspondentes também devem ser atualizadas.
## Cobertura dos requisitos não funcionais

O requisito **RF11** (escalonamento ao supervisor) está ligado a **UC03**, à história **S44-US09** e à jornada **J02**.

| RNF | Casos de uso relacionados | Histórias que contribuem |
|---|---|---|
| RNF01 | UC01, UC02, UC04, UC08 | US01, US03, US04, US08 |
| RNF02 | UC03, UC04, UC07, UC08, UC09 | US04, US07, US08, US09 |
| RNF03 | UC01 | US02 |
| RNF04 | UC02, UC04, UC09 | US04 |
| RNF05 | UC01, UC02, UC04 | US01, US03, US04 |
| RNF06 | UC01, UC02 | US01, US03 |
| RNF07 | UC01, UC02, UC04 | US01, US03, US04 |
| RNF08 | UC05, UC08 | US05, US08 |
| RNF09 | UC06, UC08 | US06, US08 |
| RNF10 | UC06 | US06 |
| RNF11 | UC01, UC02 | US01, US02, US03 |
| RNF12 | UC01, UC05, UC07 | US02, US05, US07 |

As relações completas de **RF01–RF14 e RNF01–RNF12** aparecem na matriz do SRS (seção 4.8), incluindo objetivos, regras e jornadas.
