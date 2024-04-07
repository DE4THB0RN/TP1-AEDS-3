# TP1-AEDS-3
Trabalho feito por Pedro Augusto de Paula,Loïcia Ribeiro e Léa Tronel

O método que o grupo usou para reaproveitar os espaços foi criado observando os métodos de update e leitura e a forma como lidam com registros deletados
Fazendo o caminho inverso deles e lendo os deletados em vez dos excluídos, depois são feitas as comparações e operações
Esse método não é otimizado e existem muitos outros possíveis bem melhores para aproveitar espaço em registros maiores
Por causa da forma que é feito o aproveitamento, o método delete não foi alterado

O que você considerou como perda aceitável para o reuso de espaços vazios, isto é, quais são os critérios para a gestão dos espaços vazios?
Uma diferença máxima de 6 bytes entre o registro deletado e o novo

O código do CRUD com arquivos de tipos genéricos está funcionando corretamente?
Sim

O CRUD tem um índice direto implementado com a tabela hash extensível?
Não

A operação de inclusão busca o espaço vazio mais adequado para o novo registro antes de acrescentá-lo ao fim do arquivo?
Sim

A operação de alteração busca o espaço vazio mais adequado para o registro quando ele cresce de tamanho antes de acrescentá-lo ao fim do arquivo?
Sim
As operações de alteração (quando for o caso) e de exclusão estão gerenciando os espaços vazios para que possam ser reaproveitados?
Nesse quesito elas não foram alteradas

O trabalho está funcionando corretamente?
Sim

O trabalho está completo?
Sim

O trabalho é original e não a cópia de um trabalho de um colega?
Sim,é original
