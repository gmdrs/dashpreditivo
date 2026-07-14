# Dashboard de Acompanhamento - Controle de Locação de Veículos

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)


Este repositório contém um dashboard interativo desenvolvido no Power BI com foco no controle gerencial, análise preditiva e métricas operacionais para um negócio de *Locação de Veículos*. 
O objetivo do painel é transformar dados brutos de frota e contratos em insights estratégicos para otimização de faturamento e gestão de clientes.

## Conteúdo do Repositório

- **`DashboardPreditivo_Vendas.pbix`**: Arquivo original contendo toda a modelagem de dados, tratamento de tabelas e os visuais do Power BI.
- **`dashboard preditivo BI.mp4`**: Vídeo demonstrativo simples detalhando o funcionamento dos filtros e a alternância de telas.

## Estrutura e Páginas do Dashboard

O projeto é dividido em três visões principais, acessíveis de forma dinâmica:

### 1. Capa / Menu Inicial
*   Interface limpa e profissional com atalhos intuitivos direcionados para os módulos internos (*Controle de Clientes*, *Modelos/Faturamento*, *Análise Preditiva e Médias*).

### 2. Visão Operacional e Comercial
*   **KPIs principais:** Total de clientes únicos ativos (ex: 30), média geral de quilômetros rodados (ex: 1357,2 km) e faturamento total acumulado (ex: R$ 81.434,00).
*   **Análise Temporal:** Gráficos de linha e barra demonstrando a evolução do *Faturamento Anual* e o *Faturamento Anual em %*.
*   **Sazonalidade:** Gráfico descritivo com o faturamento quebrado por *Dia da Semana*.
*   **Detalhamento da Frota:** Tabela analítica completa contendo *ID, Marca, Modelo, Placa, Ano/Data, Dia da Semana, Situação (Ativo/Inativo) e Valor da Venda*.
*   **Filtros Rápidos:** Segmentação completa por *Situação, Ano, Modelo e Dia*.

### 3. Visão Preditiva (Clientes Cadastrados vs. Não Cadastrados)
*   **Controle e Classificação:** Gráficos de rosca separando a frota por categoria (*Luxo, Popular e Modelo não regulamentado*) e controle de cadastro.
*   **Listas Dinâmicas de Cruzamento:** Painéis comparativos imediatos separando os dados de *Clientes Não Cadastrados* contra *Clientes Cadastrados*, permitindo ações rápidas de CRM e regularização de contratos.


## 🛠️ Tecnologias e Técnicas Aplicadas

*   **Power BI Desktop** — Construção do layout, visuais e engenharia de dados.
*   **Linguagem M / Power Query** — Limpeza e tratamento de inconsistências (como registros marcados como "Modelo Não Registrado").
*   **Linguagem DAX** — Modelagem e criação de medidas calculadas para faturamentos acumulados e médias ponderadas por quilometragem.

---

Nota: Este projeto foi desenvolvido para fins de portfólio demonstrando a aplicação de Business Intelligence na gestão de frotas e logística.
