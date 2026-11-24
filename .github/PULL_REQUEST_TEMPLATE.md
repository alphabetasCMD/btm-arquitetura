# Defesa de Arquitetura de Software — Pull Request

## Autor do PR
- **Nome do Estudante:** [Seu Nome Completo]
- **Artefato(s) de Responsabilidade:** [ex: C4 Nível 3, Diagrama de Sequência e ADR 0001]

## O que este PR introduz na Documentação Viva?
- [ ] **Visão Funcional / Estrutural:** Diagrama de Casos de Uso ou Diagrama de Classes e Interfaces.
- [ ] **Visão Comportamental:** Diagrama de Sequência, Atividades ou Máquina de Estados.
- [ ] **Visão Arquitetural Macro:** Modelo C4 (L1, L2 ou L3).
- [ ] **Governança:** Registros de Decisão Arquitetural (ADR).

## Defesa das Decisões de Design (Justificativa Técnica)
1. **Escolha de Abstrações e Desacoplamento:** Por que as interfaces, visibilidades e relacionamentos foram desenhados dessa forma?
2. **Dinâmica e Resiliência:** Como os fluxos alternativos (`alt/else`), mensagens assíncronas ou guardas de estado tratam falhas?
3. **Trade-offs:** Quais prós e contras foram considerados?

## Consistência Cross-Diagramas (Checklist de Autoverificação)
- [ ] Os nomes de métodos chamados no Diagrama de Sequência existem nas interfaces do Diagrama de Classes.
- [ ] Os contêineres e componentes citados correspondem à nomenclatura do Modelo C4 L2/L3.
- [ ] As transições de estado refletem os gatilhos disparados pelas atividades da aplicação.

## Validação da Sintaxe Diagrams-as-Code / Models-as-Code
- **Ferramenta de Renderização Utilizada:** [ex: Mermaid, PlantUML, D2]
- **Status da Compilação:** [ ] Código limpo e sem erros de sintaxe ao renderizar.