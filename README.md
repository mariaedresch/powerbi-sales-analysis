# powerbi-sales-analysis
# Análise de Vendas – Sample Superstore (Power BI)

## Contexto
Este projeto foi desenvolvido com o objetivo de aplicar boas práticas de análise de dados, modelagem e visualização utilizando o Power BI.  
A base de dados simula um cenário real de varejo, com foco na geração de insights e no suporte à tomada de decisão.

## Objetivos
- Construir um dashboard claro, consistente e profissional
- Aplicar boas práticas de modelagem de dados
- Padronizar métricas, categorias e formatações visuais
- Desenvolver um storytelling visual coerente e orientado ao negócio

## Desafios
- Inconsistência na ordem das regiões entre os gráficos
- Divergência na formatação de valores numéricos e monetários
- Risco de poluição visual devido ao excesso de informações
- Garantir escalabilidade e manutenção do modelo de dados

## Soluções Implementadas
- Criação de uma tabela dimensão (DimRegiao) para controle da hierarquia regional
- Implementação de ordenação personalizada, evitando dependências circulares
- Padronização das unidades de medida e eixos dos gráficos
- Desenvolvimento de tooltips informativas e objetivas, preservando a clareza visual

## Tecnologias e Conceitos Utilizados
- Power BI
- DAX
- Modelagem de Dados em Esquema Estrela
- Visualização de Dados e Storytelling

## Resultado Final
O dashboard final apresenta leitura intuitiva, consistência visual e um modelo de dados organizado, permitindo análises confiáveis e escaláveis para suporte à tomada de decisão.

## Principais Aprendizados
- Importância da separação entre tabelas fato e dimensões
- Boas práticas para ordenação personalizada no Power BI
- Impacto da padronização visual na interpretação dos dados
- Equilíbrio entre profundidade técnica e clareza analítica

### Modelagem de Dados
Foi adotada uma abordagem de modelagem com separação entre tabela fato e tabelas dimensão, seguindo boas práticas de esquema estrela.
A tabela de dimensão **DimRegiao** foi criada para centralizar atributos descritivos e regras de ordenação, garantindo consistência visual entre os gráficos, evitando dependências circulares e facilitando a escalabilidade do modelo.

