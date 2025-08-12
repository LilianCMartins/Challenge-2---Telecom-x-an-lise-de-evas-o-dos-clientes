# Challenge Telecom X : Análise de evasão dos clientes 📊

Análise de Dados para Redução de Churn na TelecomX

Este projeto foi desenvolvido como parte do programa Oracle Next Education - G8 em parceria com a Alura, com foco em analisar dados de uma empresa de telecomunicações fictícia para identificar padrões de churn e desenvolver estratégias de retenção de clientes.

- Perfil dos clientes: idade, gênero, status de parceiro, dependentes, tempo de contrato, serviços contratados, forma de pagamento, entre outros.
- Métricas financeiras: `charges_monthly` (cobrança mensal), `charges_total` (cobrança total), `contas_diarias` (contas diárias), `quantidade_servicos` (quantidade de serviços contratados).

## Objetivos da Análise

- Identificar fatores associados ao churn.
- Comparar comportamentos entre clientes ativos e cancelados.
- Gerar visualizações para suporte à tomada de decisão.
- Desenvolver estratégias de retenção.

## Principais Descobertas

- **Taxa geral de churn**: 26,5% dos clientes.
- **Clientes idosos**: apresentam maior taxa de churn (41,7%).
- **Clientes sem parceiro**: têm maior propensão a cancelar (32,9%).
- **Contratos mensais**: possuem taxa de churn significativamente maior (42,7%).
- **Ausência de serviços adicionais**: aumenta o risco de churn.
- **Pagamento por cheque eletrônico**: apresenta maior taxa de churn (45,3%).

## Análise Estatística Descritiva

| Métrica             | Valor Médio |
|---------------------|-------------|
| `charges_monthly`   | 64.80       |
| `charges_total`     | 2283.30     |
| `contas_diarias`    | 2.16        |
| `quantidade_servicos` | 0.29     |

## Matriz de Correlação

A matriz de correlação entre as variáveis numéricas revela relações importantes:

- **`charges_monthly` e `charges_total`**: correlação de 0.65, indicando que o valor mensal está fortemente relacionado ao total cobrado.
- **`charges_monthly` e `contas_diarias`**: correlação de 0.99, sugerindo que o número de contas diárias impacta diretamente na cobrança mensal.

- 
**Linguagem**: Python
- **Ambiente**: Jupyter Notebook
- **Bibliotecas**:
- `pandas`: manipulação de dados.
- `matplotlib` e `seaborn`: visualização de dados.
- `scikit-learn`: construção e avaliação de modelos de machine learning.

## Ambientes Recomendados
- Google Colab (sem necessidade de instalação local)
- Jupyter Notebook via:
- VSCode
- Anaconda
- Ambiente virtual Python

  ## Autora

  Lilian Martins
  
