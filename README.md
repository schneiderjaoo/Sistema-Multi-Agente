# Sistema Multi Agente - Startup de Moda Sustentável

Este repositório contém um sistema multiagente projetado para analisar o mercado de moda sustentável em São Paulo. O sistema utiliza agentes de inteligência artificial para realizar tarefas específicas, coletar informações e gerar relatórios úteis para startups do setor de moda sustentável.

## Estrutura do Código

O código é dividido em várias seções principais, incluindo a definição de agentes, tarefas e a inicialização do processo. Os principais componentes do sistema são:

1. **Agentes**:
   - **Pesquisador de Mercado Sênior**: Realiza uma análise detalhada do mercado, incluindo uma análise SWOT (Forças, Fraquezas, Oportunidades, Ameaças) e fornece dados sobre concorrência, tamanho de mercado e tendências de consumo.
   - **Especialista em Sustentabilidade**: Avalia a viabilidade sustentável do modelo de negócios proposto, garantindo que o negócio esteja alinhado com as melhores práticas ambientais e fornece recomendações para melhorar o impacto ambiental.
   - **Empreendedor**: Cria um plano de negócios e um plano de marketing para o serviço de assinatura de roupas sustentáveis com base nas informações fornecidas pelos outros agentes.

2. **Ferramenta de Pesquisa**:
   - O sistema utiliza a ferramenta `SerperDevTool` para realizar pesquisas de mercado e obter informações relevantes.

3. **Tarefas**:
   - Cada agente é atribuído a tarefas específicas, onde são definidos os objetivos e os resultados esperados.

4. **Execução**:
   - O processo é iniciado com uma ideia de negócio, e os agentes trabalham em conjunto para gerar um relatório final.

## Como Funciona

1. **Carregamento de Variáveis de Ambiente**: O sistema utiliza o arquivo `.env` para carregar configurações e credenciais necessárias.
2. **Definição de Agentes e Tarefas**: Os agentes e suas respectivas tarefas são definidos com base nos objetivos do projeto.
3. **Execução do Processo**: O sistema é executado, e os agentes trabalham em conjunto para realizar análises e gerar resultados.
4. **Geração de Relatório**: Os resultados são salvos em um arquivo `startup_analysis.md`.

## Saídas do Sistema

- O sistema gera um relatório detalhado que inclui:
  - Análise SWOT do mercado de moda sustentável em São Paulo.
  - Dados sobre concorrência e tamanho do mercado.
  - Tendências de consumo e viabilidade sustentável do modelo de negócios.
  - Plano de negócios e plano de marketing para o serviço de assinatura de roupas sustentáveis.

## Pré-requisitos

- Python 3.x
- Bibliotecas necessárias:
  - `dotenv`
  - `crewai`
  - `langchain_groq`
  - `litellm`
  - `crewai_tools`

## Execução do Sistema

Para executar o sistema multiagente que analisa o mercado de moda sustentável, siga os passos detalhados abaixo:

### Passo 1: Clonando o Repositório

Primeiro, clone o repositório em seu ambiente local usando o seguinte comando:

```bash
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>

pip install -r requirements.txt

#https://console.groq.com/keys
GROQ_API_KEY =s eu_api_key_aqui
#https://serper.dev/api-key
SERPER_API_KEY = seu_api_key_aqui

python seu_script.py



