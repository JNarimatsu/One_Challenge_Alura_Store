<div align="center">
  <img 
    alt="Alura_store" 
    height="250" 
    width="250" 
    src="https://github.com/JNarimatsu/assets/raw/main/Alura_Store.png"
  >
</div>

# One_Challenge_Alura_Store
## Alura Store Brasil

### Technologies

<div style="display: inline_block"><br>
  <img align="center" alt="Python" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
  <img align="center" alt="Pandas" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg"/>
  <img align="center" alt="Matplotlib" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg"/>
        
 </div>

 ## Conjunto de dados
O projeto conta com uma análise exploratória de quatro conjuntos de dados de quatro lojas. Os conjuntos de dados contam com informações sobre de faturamento, categorias de produtos, produtos vendidos nas lojas e valores de frete. Estamos analisando os bancos de dados das lojas 01, 02, 03 e 04 pertencente ao senhor João que deseja verificar alguns KPIs para decidir qual loja deve ser vendida. Realizamos uma análise exploratória nos dados comparando os resultados de cada loja. Criamos gráficos para facilitar as visualizações dessas análises.

### Comparação de faturamento:
A loja 01 um tem maior faturamente, seguida pelas lojas 2 e 3, com diferença de 24.434,03 reais. Com menor faturamento temos a loja 4 com uma diferença de 150.011,54 reais comparada a loja 1.
![Faturamento](https://github.com/JNarimatsu/assets/raw/main/Faturamento_01.png)
### Vendas por categoria
As categorias Móveis e eletrônicos são as mais vendidas, seguido por brinquedos em todas as lojas. Nas lojas 1, 2 e 3 utilidades domésticas é a menos vendida, mas na loja 4 temos instrumentos musicais como a menos vendida.
![Vendas_categoria](https://github.com/JNarimatsu/assets/raw/main/Venda_cat_02.png)
### Média de avaliação das lojas
A média das avaliações tem poucas variações, mas é possível verificar que as lojas 2 e 3 (variação de 0,01 entre elas) são as mais bem avaliadas. A diferença entre a avaliação da loja 01 e a loja 03 são de 0,07. Entre as lojas 03 e 04 tem diferença de 0,05.
![Avaliacao_media](https://github.com/JNarimatsu/assets/raw/main/Avaliacao_03.png)

### Produtos mais e menos vendidos


![Mais_vendidos](https://github.com/JNarimatsu/assets/raw/main/Produtos_vendidos04.png)
#### Mais vendidos
Loja 01: Microondas, Tv Led UHD 4K e Guarda-Roupas (60), Secadora de roupas e Blocos de montar;

Loja 02: Livro - Iniciando em programação, Microondas, Batedeira, Pandeiro e Violão;

Loja 03: kit baquetas, Mesa de jantar, Cama King (56), Cômoda e Jogo de panelas(55);

Loja 04: Cama box, Faqueiro, Cama king e Livro - Dashboards com Power BI(56) e Carrinho de controle remoto;



![Menos_vendidos](https://github.com/JNarimatsu/assets/raw/main/Produto_vendidos04_menos.png)
#### Menos Vendidos
Loja 01: Celular ABXY, Headset(33), Panela de pressão, Pandeiro e Livro - Ciências de dados com Python;

Loja 02: Jogo de tabuleiro, Mesa de jantar, Impressora, Poltrona e Fone de ouvido;

Loja 03: Blocos de montar, Jogo de copos, Micro-ondas, Mochila e Copo Térmico;

Loja 04: Guitarra, Guarda-Roupas, Violão, Geladeira e Livro - Ciências de dados com Python(38);

### Frete médio por loja
![Frete](https://github.com/JNarimatsu/assets/raw/main/Frete_medio.png)


Loja 01 tem frete médio com valor mais elevado enquanto a loja 04 tem valor de frete médio mais baixo, Lojas 02 e 03 tem frete médio semelhantes.

### Análise de Desempenho Geográfico

![Desempenho_geografico](https://github.com/JNarimatsu/assets/raw/main/Concentracao_06.png)

#### Loja 1:
  • Vendas: 2359
  • Área coberta: 1072.456800°
  • Densidade: 2.20 vendas/°²
  • Dispersão: 9.5536
  • Score eficiência: 0.23

#### Loja 2:
  • Vendas: 2359
  • Área coberta: 1092.153600°
  • Densidade: 2.16 vendas/°²
  • Dispersão: 9.4881
  • Score eficiência: 0.23

#### Loja 3:
  • Vendas: 2359
  • Área coberta: 1092.153600°
  • Densidade: 2.16 vendas/°²
  • Dispersão: 9.6610
  • Score eficiência: 0.22

#### Loja 4:
  • Vendas: 2358
  • Área coberta: 900.345800°
  • Densidade: 2.62 vendas/°²
  • Dispersão: 9.5902
  • Score eficiência: 0.27

**Loja 4 tem a estratégia mais eficiente. Pois apresenta alta densidade de vendas com boa concentração geográfica**

## Conclusão
Apesar de observamos o menor faturamento, a loja 04 se destaca com Alta densidade de vendas e boa concentração geográfica, suas avaliações não são baixas em comparação com as demais notas e temos uma valor de frete médio abaixo das demais lojas analisadas, a loja quatro apresenta o Score de eficiência mais elevados também. Quando observamos as outras três lojas, todas apresentam perfil de vendas similiar, isso em conjunto com a área de atuação proxima. Com isso em mente, podemos verificar que as lojas um e dois tem o mesmo Score de eficiência, enquanto a loja três tem uma diferença um pouco menor. As lojas três e dois apresentam as melhores avaliações de vendas e o valor do frete médio são similares. Já na loja um temos uma cenário um pouco diferente, a loja um conta com a avaliação mais baixa e o frete mais elevado. Podemos observar muitas semelhanças entre as lojas três e dois, sua área de atuação, produtos e categorias similares de venda, esses fatores me mostram um forte potencial de canibalização entre essas duas lojas, visto que a loja dois tem tem faturamento e o scrore de eficiência um pouco mais elevado que a loja três, **eu indicaria a loja três para venda.** Isso manteria o alto faturamento da loja um, a alta densidade e boa concentração de vendas da loja quatro e além do faturamento e boa relação com os cliente que temos na loja dois.
