# exp-dio-projeto
Projeto da dio com azure machine learning

**Designer job das previsões e desempenho**
![Imagem job designer](https://live.staticflickr.com/65535/54506746790_64f979bf4c_o.png)
![Imagem job designer](https://live.staticflickr.com/65535/54506779665_5945c3d1cd_o.png)
![Imagem job designer](https://live.staticflickr.com/65535/54506669158_42f863598d_o.png)
Dados avaliados:

* **MAE (Erro Absoluto Médio)**: **7,47**
  Em média, o modelo erra por cerca de 7,5 unidades nas previsões.

* **RMSE (Raiz do Erro Quadrático Médio)**: **9,03**
  Penaliza mais os erros grandes; mostra que há alguma variação considerável nos erros.

* **R² (Coeficiente de Determinação)**: **0,681**
  O modelo explica aproximadamente **68,1% da variabilidade** nos dados de vendas, o que é **razoável**, mas ainda há espaço para melhoria.

**Modelos do ML automatizado**
![Imagem job designer](https://live.staticflickr.com/65535/54505529287_d893bea933_o.png)
**Melhor modelo gerado**
![Imagem job designer](https://live.staticflickr.com/65535/54505529117_1a3ec8b9bc_o.png)



# 📊 Relatório de Análise de Vendas de Sorvete com Base na Temperatura

## 1. Visão Geral dos Dados
O conjunto de dados analisado contém registros de vendas de sorvete, onde cada entrada inclui:
- Temperatura (°C)
- Vendas reais (quantidade)
- Vendas previstas por um modelo de machine learning

As temperaturas variam de **25°C a 36°C**, e as vendas de **92 a 159 unidades**.

---

## 2. Desempenho do Modelo

Com base na avaliação entre as vendas previstas e reais, obtivemos as seguintes métricas:

| Métrica | Valor | Interpretação |
|--------|-------|-------------------------------|
| MAE (Erro Absoluto Médio) | 7,47 | O modelo erra em média 7,5 unidades |
| RMSE (Raiz do Erro Quadrático Médio) | 9,03 | Penaliza mais os erros grandes |
| R² (Coeficiente de Determinação) | 0,681 | Modelo explica 68,1% da variação nos dados |

✅ As previsões são razoavelmente boas considerando que **só a temperatura** foi usada como preditora.

---

## 3. Insights e Tendências

- Dias com temperaturas mais altas (acima de 33°C) tendem a ter **vendas acima de 140 unidades**
- Em dias com temperaturas mais amenas (25°C a 27°C), as vendas caem para **100 unidades ou menos**
- Há uma **correlação positiva clara** entre temperatura e vendas

---

## 4. Potencial de Uso do Modelo

- **Previsão de estoque e produção** com base na previsão do tempo
- **Ajuste de campanhas promocionais** em dias mais frios
- **Otimização logística** com base em previsão de demanda

---

## 5. Conclusão

O modelo atual apresenta **bom desempenho inicial** com apenas uma variável de entrada. Com mais dados e ajustes, poderá se tornar uma ferramenta estratégica poderosa para **prever e otimizar vendas de sorvete**.
