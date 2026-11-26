# Radar de Nichos

Ferramenta local para transformar um público e um problema observado em hipóteses de oportunidade de negócio que podem ser investigadas com clientes.

## O que faz

- Gera ideias em saúde e bem-estar, educação e carreira, alimentação, pequenos negócios, casa e comunidade, sustentabilidade e tecnologia.
- Combina o setor, o público, o problema, seus recursos, a região, o modelo de oferta e o capital inicial.
- Atribui uma nota heurística a cada hipótese e mostra sinais de urgência, disposição para pagar, acesso ao público, aderência às suas habilidades e lacunas nas alternativas atuais.
- Sugere um primeiro teste e um risco que merece ser verificado.
- Permite comparar até três ideias, imprimir os resultados ou baixar uma análise em texto.

## Como usar

1. Abra `index.html` em um navegador moderno. Não é necessário instalar dependências nem iniciar um servidor.
2. Escolha uma área ou selecione **Explorar várias áreas**.
3. Informe, se souber, o público, o problema, sua vantagem ou experiência e a região que pretende atender.
4. Escolha um formato de oferta e uma faixa de capital inicial.
5. Avalie de 1 a 5 os sinais que já observou e clique em **Gerar oportunidades**.
6. Compare as ideias mais promissoras e use o teste sugerido para conversar com potenciais compradores.

Os campos sobre público, problema, experiência e região podem ficar em branco. Nesse caso, a ferramenta usa exemplos de cada área.

## Como as notas são calculadas

A nota é uma prioridade inicial para investigação, não uma previsão de vendas:

- 62% vêm das avaliações informadas pela pessoa usuária.
- 38% vêm de valores-base heurísticos associados ao tipo de oportunidade.
- As avaliações usam estes pesos: urgência e frequência (24%), disposição para pagar (22%), facilidade de encontrar o público (18%), aderência às habilidades e acesso (20%) e lacuna nas alternativas atuais (16%).
- A ferramenta ajusta a nota de acordo com a compatibilidade entre o modelo de oferta escolhido, o capital disponível e o investimento típico da hipótese.

Os valores-base e os ajustes são regras simples para organizar ideias. Não foram calculados a partir de pesquisas, tendências, preços, concorrentes ou dados de vendas.

## Validação recomendada

Use as hipóteses como ponto de partida. Converse com pessoas do público sobre situações recentes, custos e soluções que já tentaram. Depois, apresente uma oferta específica e procure um compromisso real, como um piloto pago ou uma pré-venda. Elogios e respostas hipotéticas não confirmam demanda.

Algumas oportunidades podem exigir formação profissional, autorização, cuidados com dados pessoais ou cumprimento de regras específicas. Verifique os requisitos aplicáveis antes de oferecer serviços nessas áreas.

## Privacidade e funcionamento

O Radar executa no navegador e não consulta APIs externas. As informações preenchidas não são enviadas a um servidor pelo aplicativo. O relatório é gerado localmente como arquivo de texto.

## Publicar com GitHub Pages

Para disponibilizar a página como site:

1. Abra **Settings → Pages** neste repositório.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch **main** e a pasta **/(root)** e salve.
4. Aguarde o endereço do site aparecer na seção Pages.

