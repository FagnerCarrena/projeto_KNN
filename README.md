# Análise de Influenciadores no Instagram com k-Nearest Neighbors (kNN)

## Descrição do Projeto
Este projeto utiliza o algoritmo k-Nearest Neighbors (kNN) para realizar uma análise de influenciadores no Instagram, explorando padrões de engajamento e influência. O objetivo é fornecer insights sobre o comportamento das contas influentes na plataforma, considerando variáveis como número de seguidores, média de curtidas e taxa de engajamento.

## Estrutura do Projeto
- **Análise Exploratória**: Análise inicial dos dados com gráficos de dispersão e histogramas para identificar padrões de engajamento.
- **Implementação do kNN**: Configuração e ajuste do algoritmo kNN com diferentes valores de k e métricas de distância.
- **Validação e Ajuste de Hiperparâmetros**: Uso de validação cruzada e otimização com GridSearchCV para encontrar a melhor configuração.
- **Avaliação do Modelo**: Cálculo das métricas de erro (MAE, MSE e RMSE) para avaliar a performance do modelo.

## Estrutura dos Dados
O conjunto de dados inclui as seguintes variáveis principais:
- `followers`: Número de seguidores.
- `avg_likes`: Média de curtidas por postagem.
- `60_day_eng_rate`: Taxa de engajamento dos últimos 60 dias.
- `influence_score`: Pontuação de influência atribuída a cada conta.
- `country`: País de origem do influenciador.

Os dados foram transformados e categorizados, incluindo a criação da variável `country_numeric` para agrupar os países por continentes.

## Instalação e Requisitos
Certifique-se de ter as seguintes bibliotecas instaladas:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

##Como executar o Projeto
clone esse repositorio
git clone https://github.com/SeuNomeDeUsuario/projeto_KNN.git

##navegue ate o diretorio

cd projeto_KNN

##execute o script principal para carregar os dados, realizar a analise explratoria e treinar o modelo KNN:
python main.py



