# Quanto vale a paz no trabalho?

Este projeto analisa a relação entre **insegurança no trabalho** e **satisfação com a vida** em países membros da OCDE, utilizando dados do *Better Life Index*. O objetivo é explorar visualmente se existe uma tendência entre ambientes profissionais instáveis e a qualidade de vida relatada pelas populações.

## 📌 Sobre os dados

Os dados utilizados foram extraídos da plataforma oficial da OCDE (Organização para a Cooperação e Desenvolvimento Econômico), através do portal Data Explorer:

🔗 Fonte oficial: [OECD Data Explorer - Better Life Index](https://data-explorer.oecd.org/vis?tenant=archive&df[ds]=DisseminateArchiveDMZ&df[id]=DF_BLI&df[ag]=OECD&dq=.JE_LMIS%2BSW_LIFS..&to[TIME]=false)

**Conjunto de dados utilizado:**
- Dataset: Better Life Index
- Indicadores selecionados: 
  - `Life satisfaction` (Satisfação com a vida)
  - `Labour market insecurity` (Insegurança no mercado de trabalho)
- Última atualização: **11 de março de 2024**
- Total de dados brutos disponíveis: **2369**
- Total de pontos utilizados: **243**

A OECD (Organização para a Cooperação e Desenvolvimento Econômico) é uma entidade internacional que reúne 38 países e fornece dados confiáveis sobre políticas públicas, economia e bem-estar social. O Better Life Index é uma das ferramentas que mede a qualidade de vida a partir de múltiplos indicadores sociais e econômicos.

## 📈 Resultados encontrados

A análise revelou uma **tendência negativa**: países com maior insegurança no mercado de trabalho geralmente apresentam menores níveis médios de satisfação com a vida. Embora essa correlação não prove causalidade, ela ilustra um padrão relevante e digno de reflexão.

Foram geradas visualizações como:
- Gráfico de dispersão entre os indicadores
- Linha de tendência ajustada (via regressão linear com `numpy`)
- Gráfico de barras com os países mais e menos satisfeitos

## 🧪 Ferramentas utilizadas

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Numpy

## 🧑‍💻 Autor

**Daniel Azevedo de Oliveira Maia**  
Desenvolvedor e analista de dados focado em clareza, dados públicos e storytelling com visualizações.

---

> Projeto com finalidade educacional e exploratória. Dados abertos e extraídos diretamente do portal oficial da OCDE.
