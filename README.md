# Otimização de Rotas e Atendimento em Unidades Básicas de Saúde (UBS) - Guarulhos

Aplicação desenvolvida em **Python** focada em **Teoria dos Grafos** e **Estruturas de Dados** avançadas para modelagem, otimização de rotas geográficas e gestão de fluxo de atendimento em Unidades Básicas de Saúde (UBS) no município de Guarulhos.

---

## 🚀 Sobre o Projeto

Este projeto de cariz académico e de engenharia de software aplica conceitos fundamentais de Ciência da Computação para resolver um problema real de logística de saúde pública:
* **Modelagem de Rede:** Representação das UBSs e vias urbanas como um grafo ponderado (vértices e arestas com pesos baseados em distâncias e tempos estimados).
* **Cálculo de Caminhos Mínimos:** Implementação de algoritmos clássicos de grafos para encontrar as rotas mais eficientes entre pontos de atendimento.
* **Análise de Estruturas:** Avaliação de conectividade, gargalos e acessibilidade da rede de saúde.

---

## 🛠️ Stack Tecnológica

* **Linguagem:** Python
* **Algoritmos & Estruturas de Dados:** Teoria dos Grafos, Algoritmo de Dijkstra / Busca de Caminhos Mínimos
* **Manipulação de Dados:** Estruturas nativas otimizadas para representação de listas/matrizes de adjacência
* **Visualização (Opcional):* NetworkX / Matplotlib (para representação gráfica da malha)

---

## 📊 Arquitetura e Decisões Técnicas

1. **Representação em Grafo:** O sistema constrói dinamicamente um grafo onde cada nó representa uma UBS ou interseção chave, e as arestas armazenam custos métricos.
2. **Eficiência de Pesquisa:** Emprego de algoritmos de otimização de caminhos para assegurar complexidade computacional reduzida, mesmo com o aumento do volume de nós da rede urbana de Guarulhos.

---

## ⚙️ Como Executar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/Lucas-IudiCG/Grafos-Usbs-Guarulhos.git](https://github.com/Lucas-IudiCG/Grafos-Usbs-Guarulhos.git)
   cd Grafos-Usbs-Guarulhos
