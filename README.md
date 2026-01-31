# 📈 Otimização de Marketing - Y.Afisha (LTV, CAC e ROI)

## 📋 Sobre o Projeto
Este projeto consiste na análise de dados da **Y.Afisha**, uma empresa fictícia, com o objetivo de otimizar os investimentos em marketing. O foco principal foi analisar os logs do servidor e o histórico de pedidos para entender o comportamento do usuário e a rentabilidade das campanhas publicitárias.

O desafio era responder à pergunta crucial: **"Os investimentos em marketing estão valendo a pena?"**

## 🎯 Objetivos de Negócio
A diretoria precisava entender a eficiência de cada canal de aquisição. Para isso, o projeto focou em:
* Calcular métricas de produto (**DAU, WAU, MAU** e Sticky Factor).
* Analisar o funil de vendas e tempo de conversão.
* Calcular o **LTV (Lifetime Value)** por coortes.
* Calcular o **CAC (Custo de Aquisição de Cliente)** por origem.
* Determinar o **ROI (Retorno sobre Investimento)** para indicar onde alocar a verba.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas & Numpy:** Manipulação e limpeza de dados.
* **Matplotlib & Seaborn:** Visualização de dados (Heatmaps, Gráficos de Barras).
* **Jupyter Notebook:** Ambiente de desenvolvimento.

## 📊 Principais Descobertas (Insights)

### 1. Análise de Dispositivos 📱 vs 💻
Identificamos que, embora os dispositivos móveis (**Touch**) gerem um volume alto de visitas, a conversão real acontece majoritariamente no **Desktop**.
* **Ação:** Manter campanhas mobile para awareness, mas focar a conversão no Desktop.

### 2. A "Armadilha" do Canal 3 📉
O **Canal (Source) 3** recebia a maior parte do orçamento de marketing. No entanto, a análise de ROI revelou que ele é ineficiente: possui um CAC alto e traz clientes com LTV baixo.
* **Impacto:** Prejuízo operacional neste canal.

### 3. As Oportunidades (Canais 1 e 2) 🚀
* **Source 1:** Apresentou o melhor ROI geral. É o canal "Estrela".
* **Source 2:** Embora tenha um custo de aquisição (CAC) alto, ele traz clientes "Premium" que gastam muito mais ao longo do tempo, justificando o investimento.

## 💡 Conclusão e Recomendação Estratégica
Com base na análise de dados, a recomendação final para a equipe de marketing é realizar uma **realocação de orçamento**:

1.  **Cortar** imediatamente o investimento no **Source 3** (ineficiente).
2.  **Reinvestir** a verba economizada nos **Sources 1 e 2**, que provaram ser lucrativos.
3.  Monitorar os **Sources 5, 9 e 10**, que apresentam baixo custo e potencial de escala.

> *"A estratégia sugerida é parar de 'comprar visitas caras' no Canal 3 e passar a 'investir em clientes lucrativos' nos Canais 1 e 2."*

---
**Autor:** Marco
[Meu LinkedIn](https://www.linkedin.com/in/marcositta) | [Meu E-mail](mailto:msitta@gmail.com)
