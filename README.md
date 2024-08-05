Aqui está um modelo de README para o seu projeto no GitHub:

---

# Análise de Grafos em Game of Thrones

Este projeto realiza uma análise de grafos utilizando dados das interações entre personagens da série "Game of Thrones". A análise foca em explorar as relações e comunidades dentro das redes sociais dos personagens, comparando a evolução dessas conexões entre a primeira e a oitava temporada.

## Índice

- [Introdução](#introdução)
- [Instalação](#instalação)
- [Uso](#uso)
- [Metodologia](#metodologia)
- [Resultados](#resultados)
- [Contribuições](#contribuições)
- [Licença](#licença)

## Introdução

Neste repositório, analisamos as conexões entre personagens de "Game of Thrones" através de técnicas de análise de grafos. Utilizamos dados das interações nas temporadas 1 e 8 para construir redes, identificar comunidades e visualizar a centralidade dos personagens ao longo da série.

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd nome-do-repositorio
   ```
3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

Para executar o projeto, basta rodar o arquivo principal que realiza as análises e gera as visualizações:

```bash
python atp_vinicius_graph.py
```

Os resultados e gráficos serão exibidos na tela e podem ser salvos para uso posterior.

## Metodologia

1. **Coleta de Dados**: Os dados foram extraídos de fontes públicas, contendo as interações entre personagens por temporada.
2. **Construção dos Grafos**: Utilizamos a biblioteca NetworkX para criar grafos a partir dos dados, representando os personagens como nós e as interações como arestas.
3. **Análise de Comunidades**: Aplicamos os algoritmos Girvan-Newman, Louvain, e Modularity para detectar comunidades dentro das redes.
4. **Visualização**: As redes foram visualizadas utilizando Matplotlib e os resultados foram analisados para interpretar a evolução das relações ao longo da série.

## Resultados

- **Evolução das Conexões**: A análise revelou uma densidade maior de interações na primeira temporada em comparação com a oitava temporada, que é mais centralizada.
- **Comunidades Identificadas**: Foram detectadas várias comunidades dentro das redes, refletindo os grupos de personagens que interagem mais fortemente entre si.
- **Análise de Graus**: Identificamos os personagens centrais em cada temporada, destacando aqueles com maior número de conexões.


