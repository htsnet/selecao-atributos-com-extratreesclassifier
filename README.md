# Seleção de Atributos com o ExtraTreesClassifier
Um estudo sobre a seleção de atributos para melhorar a performance do ExtraTreesClassifier

Um pequeno exercício de escolha de atributos para melhorar a performance de um modelo usando o ExtraTreesClassifier.

No exercício é possível ver uma melhora da acurácio do modelo (de 0.75 para 0.8375) apenas com a seleção de atributos mais importantes para a classificação.

Não foi realizada nenhuma ação com parâmtros do classificador. A redução de 4096 (64 x 64) atributos para apenas 375 produziu uma grande melhora no modelo. Ou seja, do dataset original com a dimensão (400, 4096) obteve-se um segundo dataset com uma nova dimensão (400, 375). 

O exercício foi criado no Colab Google, usando Python e diversas bibliotecas de apoio.
