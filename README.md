# CAIXAVERSO

# Análise Exploratória de Acidentes nas Rodovias Federais – 2024

Projeto desenvolvido no módulo **Estatística** do programa **CAIXAVERSO - Analista de Dados nível II**, com o objetivo de realizar uma análise exploratória de dados utilizando registros de acidentes de trânsito no Brasil.

## Objetivo
Explorar padrões e relações entre características dos acidentes, perfil das vítimas e gravidade dos desfechos, utilizando técnicas de estatística descritiva e visualização de dados.

## Fonte dos Dados
Os dados utilizados neste projeto foram obtidos a partir da base pública da Polícia Rodoviária Federal (PRF), referente aos acidentes ocorridos em 2024, agregados por pessoa. Podem ser obtidos acessando o drive https://drive.google.com/file/d/1-PJGRbfSe7PVjU37A3wTCls_NRXyVGRD/view

## Metodologia
- Limpeza e padronização dos dados
- Análise univariada e multivariada
- Cálculo de medidas estatísticas descritivas
- Visualização de dados por meio de gráficos

## Visualizações e Análises

### Distribuição do estado físico das vítimas

Este gráfico apresenta a distribuição proporcional do estado físico das vítimas envolvidas em acidentes nas rodovias federais brasileiras em 2025. Observa-se predominância de vítimas ilesas, seguida por vítimas com lesões leves. As categorias de lesões graves e óbitos representam parcelas menores do total, enquanto a presença da categoria “Não Informado” evidencia limitações no preenchimento de alguns registros da base de dados.

### Proporção do estado físico das vítimas por dia da semana
Este gráfico de barras empilhadas em proporção (100%) compara a distribuição do estado físico das vítimas ao longo dos dias da semana, independentemente do volume total de acidentes em cada dia. A visualização permite identificar variações na gravidade relativa dos acidentes, destacando maior participação de lesões graves e óbitos nos finais de semana, o que sugere aumento da severidade dos acidentes nesses períodos.

### Proporção de acidentes graves por tipo de veículo
Este gráfico apresenta a proporção de acidentes graves (lesões graves e óbitos) em relação ao total de ocorrências para cada tipo de veículo. A análise controla o efeito do volume total de registros e permite comparar o risco relativo entre categorias. Observa-se maior proporção de acidentes graves entre usuários mais vulneráveis, como ciclistas, ciclomotores e motociclistas, enquanto veículos de maior porte apresentam menor proporção relativa de gravidade.

## Observações
Os resultados apresentados são exploratórios e não implicam causalidade. As análises refletem associações observadas nos dados e estão sujeitas às limitações de preenchimento da base.

## Tecnologias Utilizadas
- Python
- Pandas
- Matplotlib


