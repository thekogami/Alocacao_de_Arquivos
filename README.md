# Alocação de Arquivos – Simulação

Este projeto é um simulador em Python 2.7 que ilustra a alocação de arquivos em um Sistema Operacional. Utiliza listas (vetor ou matriz) para simular a quantidade de blocos necessários para alocação de arquivos em um disco.

## Requisitos
- Python 2.7

## Funcionalidades

### Fase 1 – Alocação Sequencial
1. Crie um disco com 100 blocos.
2. Adicione 30 arquivos que utilizem entre 2 e 6 blocos cada, aleatoriamente.
3. Cada bloco deverá ser nomeado pelo nome do arquivo que contém.
   - Exemplo: O arquivo “J.txt” deve estar impresso nos blocos 21 a 25, caso esteja alocado nestes blocos.
4. Quando não for possível alocar um arquivo, o sistema deve mostrar uma mensagem avisando que NÃO HÁ ESPAÇO SUFICIENTE! Salve o nome destes arquivos e a necessidade de alocação de cada um.
5. Imprima o disco.
6. Informe o nome e a quantidade de arquivos que não puderam ser alocados.

### Fase 2 – Fragmentação Externa
1. Remova, aleatoriamente, 10 arquivos salvos no disco (talvez você precise criar uma tabela FAT na Fase 1).
2. Imprima o disco e mostre sua fragmentação externa.

### Fase 3 – Arquivos não alocados na Fase 1
1. Percorra o disco e tente alocar os arquivos que não puderam ser alocados na Fase 1 – (FIFO).
2. Escolha um espaço contíguo para alocar cada arquivo.
3. Percorra o disco e tente realocar os arquivos que foram removidos (FIFO).
4. Escolha um espaço contíguo para alocar cada arquivo.
5. Mostre a lista dos arquivos que não puderam ser alocados devido ao número de blocos insuficientes.
6. Imprima o disco.

### Fase 4 – Desfragmentação
1. Realize a desfragmentação do disco – explique qual a estratégia utilizada.
2. Imprima o disco desfragmentado.
3. Tente alocar novamente os arquivos que não puderam ser alocados na Fase 3.
4. Imprima o disco.
5. Informe a quantidade e quais arquivos não puderam ser alocados após a desfragmentação – explique o motivo.

### Fase 5 – Conclusão
1. Explique a estratégia utilizada para cada fase.
2. Quais as maiores dificuldades para construir o algoritmo?
3. A equipe construiu uma Tabela de Alocação de Arquivos - FAT? Por que?
4. Quais as conclusões da equipe sobre o processo de alocação de arquivos em disco?
