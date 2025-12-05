## 📚 Mapeamento Completo de Tópicos para Aprender PySpark

### **1. Estruturas Fundamentais da Linguagem (Python Básico)**
*(Notebook : `01_Base_Python_Estruturas`)*

* **Variáveis** (Guardar valores)
* **Listas** (Vários valores)
* **Dicionário** (Estrutura `Chave: Valor`, similar a JSON)
* **Condição** (`if` para tomada de decisão)
* **Loop** (`for` para repetição de ações)
* **Função** (`def` para criar código reutilizável)

### **2. Tarefas e Aplicações Práticas com Dados**
*(Notebook : `02_Manipulacao_e_IO_Basico`)*

* **Manipulação Básica** (Tarefas que envolvem Listas e Dicionários)
* **Tratar Dados** (Lógica de limpeza e validação de informações)
* **Funções** (O ato de **usar** as funções criadas)
* **Ler/Escrever Arquivos** (Operações de I/O para carregar e salvar dados)
* **Pandas** (Uso da biblioteca para análise tabular)
* **ETL (Extrair, Transformar, Carregar)** (Processo de engenharia de dados que usa todas as ferramentas)

### **3. Estruturas de Dados do PySpark**
*(Notebook : `03_DataFrames_e_Schema`)*

* **DataFrame:** A estrutura principal (tabela distribuída) do PySpark.
* **Schema:** O dicionário que define o nome e o tipo de dados exato de cada coluna.
* **RDD:** A estrutura de dados original do Spark.
* **Column:** O objeto que representa uma coluna individual dentro de um DataFrame.

### **4. Transformações e Ações (Processamento Distribuído)**
*(Notebook : `04_Transformacoes_e_SQL_Spark`)*

* **Seleção e Projeção:** Comandos (`select`, `withColumn`) para adicionar, remover ou renomear colunas.
* **Filtragem:** Comandos (`filter`, `where`) para selecionar linhas com base em condições.
* **Agregação e Agrupamento:** Comandos (`groupBy`, `agg`) para calcular métricas.
* **Junções (`join`):** Comandos para combinar dois ou mais DataFrames.

### **5. Otimização e Escalabilidade**
*(Notebook : `05_Otimizacao_e_Fluxo_ETL`)*

* **Particionamento:** Como o Spark divide os dados para processamento paralelo eficiente.
* **Caching:** Comandos (`cache`, `persist`) para armazenar DataFrames frequentemente usados na memória.
* **Funções Definidas pelo Usuário (UDFs):** Funções personalizadas em Python que o Spark pode executar.
* **Modos de Execução (Lazy Evaluation):** O conceito de que o Spark só executa o código quando um comando de "ação" (como `show()`) é chamado.
