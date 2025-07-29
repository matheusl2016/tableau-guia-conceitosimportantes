GUIA PRÁTICO DE USO DO TABLEAU – CRIAÇÃO DE DASHBOARD OLÍMPICO
1. Preparação Inicial
Baixe e instale o Tableau Public (se ainda não o fez).

Crie sua conta gratuita no Tableau Public.

Baixe a planilha com os dados das Olimpíadas (arquivo Excel).

No Tableau, clique em Arquivo > Abrir e selecione a planilha Excel como fonte de dados.

2. Criação das Planilhas (Visualizações Individuais)
🔹 Planilha 001 – Exploração Inicial
Arraste dimensões e medidas para “Linhas” e “Colunas” para testar diferentes gráficos.

Utilize o painel de Marcas para personalizar: cor, forma, rótulo etc.

Troque entre gráfico de linha, barras verticais e horizontais, gráfico de área, etc.

Nomeie a planilha como Planilha 001.

🔹 Planilha 002 – Barras por Tipo de Medalha
Crie um gráfico de barras horizontais com Medalha no eixo e Número de Medalhas como medida.

Adicione País em Linhas para criar uma quebra.

Classifique por soma de medalhas (decrescente).

Aplique filtro Top N (ex: Top 5 países).

Salve como Planilha 002.

🔹 Planilha 003 – Usando o “Show Me”
Explore o botão “Show Me” para visualizar sugestões automáticas de gráficos.

Teste gráfico de pizza, barras empilhadas, mapa de árvore (treemap).

Entenda o que o Tableau sugere conforme os campos selecionados.
[MedalhasOlimpicas.xlsx](https://github.com/user-attachments/files/21489934/MedalhasOlimpicas.xlsx)

Salve como Planilha 003.

3. Conceitos do Tableau: Planilha, Dashboard, História e Livro
Planilha: visualização individual.

Dashboard: agrupamento de planilhas em uma única interface.

História: sequência de visualizações (como um slideshow).

Livro: o arquivo .twbx com tudo isso salvo.

4. Criação de Visualizações para o Dashboard Final
📌 Planilha: Medalhas por Ano
Eixo X: Ano (modo Discreto).

Eixo Y: Número de Medalhas.

Tipo de gráfico: barra vertical.

Use Ajustar largura para ocupar todo o espaço.

📌 Planilha: Medalhas por Gênero
Gênero + Número de Medalhas.

Gráfico de pizza, ajustando o tamanho da visualização.

Mostre porcentagens ou total se quiser enriquecer.

📌 Planilha: Medalhas por País
País + Número de Medalhas.

Use Show Me para exibir em mapa de árvore.

Mostre áreas proporcionais por medalha.

📌 Planilha: Filtro de Medalhas com Ícones
Campo: Medalha em Marcas.

Tipo de marca: Forma.

Adicione imagens customizadas de ouro, prata e bronze.

Copie as imagens para: Documentos > Meu Repositório do Tableau > Formas.
