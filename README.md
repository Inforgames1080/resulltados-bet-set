⚙️ Etapas principais do código

Criação do DataFrame
Os dados das apostas são estruturados em um pandas.DataFrame, com colunas como:

Jogo → Nome das equipes (ex: Atalanta vs Club Brugge)

Data/Hora → Data e hora da partida

Lucro (R$) → Valor ganho ou perdido (números positivos ou negativos)

Limpeza e conversão de dados

Os valores monetários (como "R$40,22") são convertidos para números (float), facilitando cálculos.

Datas e horas são convertidas para o formato datetime do pandas.

Linhas com “Subtotal” são ignoradas.

Cálculos e indicadores
O código calcula:

Lucro total (soma geral dos ganhos e perdas)

Número total de apostas

Lucro médio por aposta

Taxa de acertos (se houver classificação positiva/negativa)

Visualização dos resultados (gráficos)
Usando Plotly Express, o script cria:

📈 Gráfico de linha mostrando a evolução do lucro ao longo do tempo

📊 Gráfico de barras com os maiores ganhos e perdas por partida

🥧 Gráfico de pizza (opcional) mostrando proporção de apostas positivas x negativas

Exportação (opcional)
Pode salvar os dados tratados em um arquivo CSV para futuras análises (ex: no Excel ou Power BI).

📊 Em resumo

👉 O código transforma o histórico bruto de apostas em um dashboard analítico — permitindo visualizar lucros, prejuízos e tendências ao longo do tempo de forma automática e profissional.
