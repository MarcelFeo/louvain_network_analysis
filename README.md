# Estudo da Biblioteca NetworkX

Este projeto utiliza o NetworkX e o algoritmo de Louvain para realizar a detecção de comunidades em redes complexas, aplicando análises de grafos e visualizações interativas. É um estudo prático das propriedades estruturais de redes e de como identificar grupos ou clusters de elementos interconectados.

## Motivação
Redes complexas aparecem em diversas áreas, como:

Redes sociais: Identificar grupos de amigos ou comunidades.
Redes biológicas: Mapear interações entre genes ou proteínas.
Redes de transporte: Detectar zonas densamente conectadas.
Redes de colaboração: Encontrar grupos em sistemas acadêmicos ou artísticos.
Este projeto visa explorar e entender as propriedades estruturais das redes, oferecendo um pipeline claro e replicável para análises.

## Funcionalidades
- Cálculo de métricas de grafos:
  - Centralidade de grau.
  - Centralidade de intermediação.
  - Densidade e diâmetro.
  - Detecção de comunidades com o algoritmo de Louvain.
  - Visualização interativa de grafos com comunidades destacadas.
  - Geração de relatórios com métricas de nós e comunidades.

## Tecnologias Utilizadas
- Linguagem: Python 3.8+
- Bibliotecas:
    - networkx - Construção e análise de grafos.
    - community-louvain - Detecção de comunidades.
    - matplotlib - Visualizações básicas.
    - plotly - Visualizações interativas.
    - pandas - Manipulação de dados e geração de relatórios.
