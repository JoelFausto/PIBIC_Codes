# Projeto: Implicações da LGPD na Mineração de Dados Abertos Educacionais

Este repositório reúne os códigos e scripts do trabalho de pesquisa **“Implicações da Lei Geral de Proteção de Dados Pessoais na Mineração de Dados Abertos Educacionais”**.  
O projeto investiga desafios e soluções para o uso de dados abertos educacionais em conformidade com a LGPD, incluindo análises e resultados obtidos.

Todos os códigos foram desenvolvidos no **Google Colab** e estão disponíveis aqui diretamente do ambiente.

---

## Estrutura dos Códigos

### Código Complementar
- **Objetivo:** Replicar os resultados obtidos no TED utilizando inteligência artificial (IA).  
- **Descrição:** Implementa métricas de inferência de atributos baseadas em quase-identificadores, simulando ataques em que um adversário tenta adivinhar valores de atributos sensíveis.

### Experimento 1 
- **Objetivo:** Testar alternativas para replicar ataques de inferência de atributos.  
- **Abordagens:**  
  - Árvores de Decisão  
  - Random Forest  
  - Redes Neurais  

### Experimento 2 
- **Objetivo:** Avaliar diferentes formas de transformação dos quase-identificadores relacionados à **data de nascimento**.  
- **Descrição:** Explora três abordagens para modificar a granularidade dos quase-identificadores formados pela data de nascimento do aluno.

### Experimento 3 
- **Objetivo:** Avaliar o impacto da alteração de atributos sensíveis definidos no TED 8750.  
- **Mudanças analisadas:**  
  - De: `IN_FINANCIAMENTO_ESTUDANTIL` e `IN_DEFICIENCIA`  
  - Para: `IN_APOIO_BOLSA_PERMANENCIA` e `IN_RESERVA_VAGAS`  

### Experimento 4 
- **Objetivo:** Avaliar o impacto da substituição do quase-identificador `CO_CURSO` por alternativas.  
- **Quase-identificadores testados:**  
  - `CO_CINE_AREA_GERAL`  
  - `CO_MUNICIPIO`  
  - `CO_UF`  
  - `CO_IES`  
  - `TP_CATEGORIA_ADMINISTRATIVA`  

### Experimento 5 
- **Objetivo:** Avaliar métricas não exploradas no estudo original do TED.  
- **Métricas utilizadas:**  
  - Weight of Evidence (WoE) e Information Value (IV)  
- **Descrição:** Complementam a análise da relação entre variáveis e o atributo-alvo.

---

> **Observação:** Todos os códigos foram desenvolvidos e testados no **Google Colab**, sendo disponibilizados aqui diretamente do ambiente.
