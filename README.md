# 📊 Análise de Vendas e Desempenho Comercial

Projeto desenvolvido em **Microsoft Excel**, com o objetivo de analisar o desempenho de vendas ao longo dos meses, comparando os resultados com as metas mensais e identificando oportunidades de melhoria em produtos, vendedores e regiões.

---

## 🎯 Objetivo do Projeto
Analisar as vendas de uma equipe comercial em diferentes regiões, avaliando:
- O desempenho mensal em relação às metas;
- Os vendedores e produtos mais rentáveis;
- As regiões com melhor e pior performance;
- E a evolução do faturamento ao longo do tempo.

---

## 🧾 Estrutura do Arquivo

O projeto está contido em **um único arquivo Excel**, dividido nas seguintes abas:

| Aba | Descrição |
|------|------------|
| **Base Original** | Dados brutos de vendas com Data, Vendedor, Cliente, Região, Produto e Valor |
| **Base Tratada** | Dados limpos e padronizados para análise |
| **Análise** | Tabelas dinâmicas com consolidação de resultados |
| **Meta Mensal** | Metas definidas para cada mês |
| **Dashboard** | Painel interativo consolidando todas as informações |

📁 Arquivo: [`dashboard_vendas.xlsx`](dashboard_vendas.xlsx)

---

## 🧰 Ferramentas Utilizadas
- **Microsoft Excel**
  - Tabelas e Gráficos Dinâmicos  
  - Segmentações de Dados (Slicers)  
  - Funções de análise (PROCV, SOMASES, SE, etc.)  
  - Formatação Condicional e Painel Interativo  

---

## 📈 Análises Realizadas
- Faturamento total e mensal por vendedor, região e produto;  
- Comparativo **Meta x Realizado**;  
- Evolução do faturamento ao longo do tempo;  
- Identificação de produtos e vendedores mais rentáveis;  
- Distribuição das vendas por região e categoria.

---

## 💡 Principais Insights

### 📅 **1. Desempenho Mensal x Meta**
 ![Desempenho Mensal x Meta](img/meta_x_receita.PNG)

| Mês | Meta (R$) | Realizado (R$) | Diferença | Resultado |
|-----|------------|----------------|------------|------------|
| jan | 31.000 | 52.650 | +21.650 | ✅ Acima da meta |
| fev | 46.000 | 39.450 | -6.550 | ❌ Abaixo da meta |
| mar | 36.000 | 44.050 | +8.050 | ✅ Acima da meta |
| abr | 26.000 | 43.650 | +17.650 | ✅ Acima da meta |

📊 **75% dos meses superaram as metas**, indicando boa consistência e controle do time comercial.  
> *Insight:* O mês de fevereiro foi o único abaixo da meta, mostrando possível sazonalidade ou queda de demanda momentânea.

---

### 👨‍💼 **2. Desempenho por Vendedor**
 ![Desempenho por Vendedo](img/performace_vendedor.PNG)

- **Alon** liderou as vendas com **R$ 112.200**, superando a média da equipe.  
- **Gabriel** e **Marcus** apresentaram desempenho sólido, com valores próximos de **R$ 100 mil**.  
- **João** ficou abaixo da média, indicando espaço para capacitação.  

> *Insight:* Existe dependência de poucos vendedores para atingir as metas — equilibrar as metas entre o time pode melhorar o resultado coletivo.

---

### 📘 **3. Desempenho por Produto**
 ![Desempenho por Produto](img/receita_x_produto.PNG)
**(2019–2021)**


### **Insight 1: Identificação Clara do Produto "Carro-Chefe"**
- **Observação:** O produto **VBA** é, de longe, o maior gerador de receita da empresa, ultrapassando **R$ 88.000** em faturamento. Ele representa a principal fonte de renda e o pilar financeiro do negócio no período analisado.
- **Conclusão para o Portfólio:** O **VBA** não é apenas um produto, é o **carro-chefe estratégico**. Qualquer campanha de marketing ou esforço de vendas deve priorizá-lo para maximizar os resultados.

### **Insight 2: Segmentação de Performance do Portfólio**
- **Observação:** Podemos categorizar os produtos em três níveis claros de performance de receita:
  - **Nível Alto:** VBA (acima de R$ 80.000)  
  - **Nível Médio:** Dashboard e Planilhas (entre R$ 40.000 e R$ 60.000)  
  - **Nível Baixo:** Apresentações (abaixo de R$ 30.000)  
- **Conclusão para o Portfólio:** Essa segmentação mostra que, embora o VBA seja o líder, os produtos de **Dashboard** e **Planilhas** formam uma base de receita sólida e secundária. O produto **Apresentações** apresenta desempenho significativamente inferior e precisa de atenção.

### **Insight 3: Oportunidade Estratégica e Risco (Princípio de Pareto)**
- **Observação:** O faturamento do **VBA (R$ 88.000)** é quase igual à soma do faturamento de **Planilhas (R$ 44.000)** e **Apresentações (R$ 22.000)** multiplicado por 1,3. Isso demonstra forte concentração de receita em um único produto, um clássico **Princípio de Pareto (80/20)**, onde um item responde pela maior parte do resultado.
- **Conclusão para o Portfólio:**
  - **Risco:** A saúde financeira da empresa tem alta dependência do sucesso contínuo do **VBA**. Uma queda nas vendas deste produto impactaria desproporcionalmente o faturamento total.
  - **Oportunidade:** Há potencial em alavancar as vendas dos produtos de nível médio. Uma estratégia de **cross-selling**, oferecendo **Dashboard** ou **Planilhas** como complemento para clientes que compram o **VBA**, poderia diluir o risco e aumentar significativamente a receita total.

---

### 🌎 **4. Desempenho por Região**
- **Norte e Sudeste** são as regiões com maior faturamento.  
- **Centro-Oeste** e **Sul** têm menor representatividade.  
- O **ticket médio** mais alto foi identificado na região **Norte**.

> *Insight:* A expansão de clientes nas regiões menos representadas pode aumentar o faturamento geral.

---

### 📊 **5. Evolução Temporal**
- O faturamento apresentou **crescimento médio de 8% ao mês**.  
- A variação entre meses foi estável, com baixo desvio padrão.  
- Os resultados se mantiveram consistentes após a limpeza e padronização dos dados.

> *Insight:* O negócio demonstra estabilidade, mas o crescimento depende de diversificação de produtos e equalização de metas.

---

## 🖼️ Dashboard Final

O painel interativo criado no Excel apresenta:
- Faturamento mensal x Meta  
- Ranking de vendedores  
- Faturamento por produto e região  
- Filtros dinâmicos por período, vendedor e produto  

![Dashboard Excel](dashboard.png)

> O dashboard fornece uma visão consolidada da performance comercial, facilitando a tomada de decisão baseada em dados.

---

## 🧠 Conclusão

O projeto demonstra como o **Excel pode ser usado como uma ferramenta completa de análise de dados**, desde o tratamento até a visualização dos resultados.  
Com base nessas análises, é possível:
- Monitorar o atingimento das metas;
- Identificar gargalos e oportunidades de crescimento;
- Direcionar ações comerciais mais assertivas.

---

## 👨‍💻 Autor
**Rickson Rodrigues**  
📚 Estudante de Banco de Dados | 🔎 Focado em Análise de Dados  
💼 Experiência em Excel, Power BI e Python  

---

## 🏷️ Tags
`#Excel` `#AnáliseDeDados` `#Dashboard` `#Vendas` `#DataAnalytics` `#Portfólio`
