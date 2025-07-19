# Análise de Churn de Clientes - TelecomX

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-orange?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-red?style=flat&logo=matplotlib)
![Seaborn](https://img.shields.io/badge/Seaborn-purple?style=flat&logo=seaborn)

## 📄 Descrição do Projeto

Este repositório contém uma análise exploratória de dados (EDA) focada na identificação dos principais fatores que levam clientes da **TelecomX** a cancelar seus serviços (Churn). O objetivo é transformar dados brutos em insights acionáveis que a empresa possa usar para desenvolver estratégias eficazes de retenção de clientes, reduzir perdas de receita e otimizar custos de aquisição.

O problema do Churn é crítico para empresas de serviços por assinatura, impactando diretamente a receita recorrente, os custos de aquisição de novos clientes e a reputação da marca. Esta análise busca mitigar esses riscos através de um entendimento aprofundado dos padrões de evasão.

## 🚀 Como Executar o Projeto

Para replicar a análise e os gráficos gerados neste projeto, siga os passos abaixo:

### Pré-requisitos

Certifique-se de ter o Python instalado em sua máquina (versão 3.9 ou superior é recomendada).

### Dependências

As bibliotecas Python necessárias para este projeto podem ser instaladas via `pip`. Você pode instalá-las de uma vez usando o comando:

```bash
pip install pandas matplotlib seaborn jupyter
```
- pandas: Para manipulação e análise de dados.

- matplotlib: Para criação de gráficos estáticos.

- seaborn: Para visualizações estatísticas de dados.

- jupyter: Para executar o notebook interativo (.ipynb).

## Estrutura do Repositório
```
TelecomX_BR/
├── TelecomX_BR.ipynb         # O notebook Jupyter com toda a análise
├── TelecomX_data_tratados.json # Conjunto de dados tratado e utilizado na análise
├── TelecomX_Data.json        # Conjunto de dados original (se houver)
├── TelecomX_data_tratados.csv # Conjunto de dados tratado em formato CSV (se houver)
└── readme.md                 # Este arquivo README
```
## Passos para Execução
1. Clone o Repositório: 
- git clone [https://github.com/SeuUsuario/TelecomX_BR.git](https://github.com/SeuUsuario/TelecomX_BR.git)
- cd TelecomX_BR

2. Abra o Notebook Jupyter:
```bash
jupyter notebook TelecomX_BR.ipynb
```
3. Execute as Células:
- Dentro do navegador, o ambiente Jupyter será aberto. Execute as células do notebook sequencialmente. O notebook está estruturado para guiar você através das etapas de:

- Limpeza e Tratamento de Dados: Carregamento do TelecomX_Data.json, tratamento de valores ausentes e transformação da variável alvo (Cancelou).

- Análise Exploratória de Dados: Geração e interpretação de gráficos sobre a influência do tipo de contrato, meses de permanência, cobrança mensal e método de pagamento no Churn.

- Conclusões e Recomendações: Resumo dos insights obtidos e sugestões de ações estratégicas.

## 💡 Insights e Conclusões Principais
- A análise revelou um perfil claro do cliente com alto risco de Churn:

- Contrato Mensal: Clientes com esse tipo de contrato apresentam as maiores taxas de cancelamento.

- Baixo Tempo de Permanência: A maioria dos cancelamentos ocorre nos primeiros meses de serviço.

- Cobrança Mensal Elevada: Clientes com contas mais altas têm maior propensão a cancelar.

- Método de Pagamento "Cheque Eletrônico": Associado a uma taxa de Churn significativamente superior.

- Perfil Demográfico Específico: Clientes idosos e que não possuem dependentes ou cônjuge também mostraram maior propensão ao Churn.

- Ausência de Serviços Adicionais: Clientes que não contratam serviços de valor agregado (ex: Segurança Online, Suporte Técnico) tendem a cancelar mais.

## 📈 Recomendações
Com base nos insights, as seguintes recomendações são sugeridas para a TelecomX:

Campanhas de Migração de Contrato: Incentivar clientes de planos mensais a migrarem para contratos de maior duração (1 ou 2 anos) com ofertas atrativas.

1. Programa de Onboarding e Engajamento Inicial: Desenvolver um acompanhamento dedicado para novos clientes nos primeiros 3 a 6 meses para garantir uma experiência positiva e fortalecer o relacionamento.

2. Ações de Retenção para Clientes de Alto Valor: Monitorar e engajar proativamente clientes com faturas mensais elevadas, oferecendo revisões de plano ou benefícios de fidelidade.

3. Revisão do Método de Pagamento "Cheque Eletrônico": Investigar as causas da alta taxa de Churn associada a este método e buscar soluções ou incentivar a migração para métodos mais estáveis (débito automático, cartão de crédito).

4. Atenção e Adaptação para o Público Idoso: Avaliar a usabilidade dos serviços e a qualidade do suporte técnico para esse segmento, buscando canais de comunicação simplificados e atendimento mais paciente.

## 🤝 Contribuições
Contribuições são bem-vindas! Se você tiver sugestões, melhorias ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou enviar um pull request.
