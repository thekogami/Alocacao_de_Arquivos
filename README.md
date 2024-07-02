# Alocação de Arquivos – Simulação

Criar em Python 2.7 um simulador que ilustre a alocação de
arquivos em um SO.
Utilize listas (vetor ou matriz) para simular a quantidade de
blocos necessários para alocação de arquivos em um disco.
• Ignore problemas como crescimento de arquivos -
encontre apenas o encaixe para seu tamanho inicial;
• Utilize listas (vetor ou matriz) em Python 2.7 para simular
o disco;
• A apresentação da execução do algoritmo deverá ser feita
em tempo real, respeitando a aleatoriedade exigida para
cada execução.


Fase 1 – Alocação Sequencial

• Crie um disco com 100 blocos
• Adicione 30 arquivos que utilizem entre 2 e 6 blocos cada,
aleatoriamente/randomicamente.
• Cada bloco deverá ser nomeado pelo nome do arquivo o
contém.
• Ex: O arquivo “J.txt” deve estar impresso nos blocos 21 a
25, caso esteja alocados nestes blocos.
• Quando não for possível alocar um arquivo, o sistema deve
mostrar uma mensagem avisando que NÃO HÁ ESPAÇO
SUFICIENTE! - salve o nome destes arquivos e a
necessidade de alocação de cada um.
• Imprima o disco.
• Informe o nome e a quantidade de arquivos que não
puderam ser alocados.

Fase 2 – Fragmentação Externa

• Remova, aleatoriamente, 10 arquivos salvos no disco (talvez
você precise criar uma tabela FAT na Fase 1)
• Imprima o disco e mostre sua fragmentação externa.

Fase 3 – Arquivos não alocados na Fase 1

• Percorra o disco e tente alocar os arquivos que não
puderam ser alocados na Fase 1 – (FIFO)
• escolha um espaço contíguo para alocar cada
arquivo.
• Percorra o disco e tente realocar os arquivos que foram
removidos (FIFO)
• escolha um espaço contíguo para alocar cada
arquivo.
• Mostre a lista dos arquivos que não puderam ser alocados
devido ao número de blocos insuficientes.
• Imprima o disco

Fase 4 – Desfragmentação

• Realize a desfragmentação do disco – explique qual a
estratégia utilizada
• Imprima o disco desfragmentado
• Tente alocar novamente os arquivos que não puderam ser
alocados na Fase 3.
• Imprima o disco
• Informe a quantidade e quais arquivos não puderam ser
alocados após a desfragmentação – explique o motivo.

Fase 5 – Conclusão

• Explique a estratégia utilizada para cada fase;
• Quais as maiores dificuldades para construir o algoritmo;
• A equipe construiu uma Tabela de Alocação de Arquivos -
FAT? Por que?
• Quais as conclusões da equipe sobre o processo de
alocação de arquivos em disco?
