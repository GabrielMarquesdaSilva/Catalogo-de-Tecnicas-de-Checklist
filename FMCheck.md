# FMCheck

## Apresentação

A técnica foi desenvolvida com foco na Linha de
Produtos de Software (LPS). O FMCheck é abordado em [de Mello et al., 2012] e [de Mello et al., 2014], mas com diferentes perspectivas. 

## Características 

No primeiro artigo, a (FMCheck) foi projetada para ser configurada de acordo com a notação utilizada na LPS. Para sua utilização, o usuário não necessita
28 de total conhecimento sobre o que será inspecionado, mas espera-se que haja uma descrição
textual do modelo de feature que será avaliado. No segundo artigo, foi realizada uma quase revisão sistemática, que indicou a falta de tecnologias voltadas para apoiar inspeção de artefatos
de uma LPS, não sendo possível a identificação de nenhuma técnica de inspeção que apoie a
leitura de Modelos de Recursos (FMs)

## Avaliações

 A técnica foi utilizada para
inspeções individuais em processos de software. Isso consiste em 3 atividades: preenchimento
de um questionário de caracterização do modelo feito pelo analista ou designer de domínio;
configuração da lista de verificação, realizada pelo moderador da inspeção; realização de uma
ou mais inspeções individuais, produzindo um ou mais relatórios de discrepâncias. Ambos os
estudos avaliaram a viabilidade por meio da aplicação de uma prova de conceito e um estudo
experimental.

## Resultados

No geral, o teste com FMCheck foi bem sucedido, visto que, encontrou 118
erros diferentes, enquanto Ad-hoc encontrou apenas 76 defeitos. Vale ressaltar também que,
o FMCheck encontrou 53 defeitos diferentes que não foram detectados pela inspeção Ad-hoc,
enquanto as inspeções Ad-hoc encontraram somente 11 defeitos distintos que não foram detectados pelo FMCheck.

## Parte do Checklist desenvolvido 

![image](https://user-images.githubusercontent.com/49456679/184937036-7c0216d5-abff-4909-8133-43ab3ca4a5ae.png)


## Artigos apresentados

de Mello, R. M., Teixeira, E. N., Schots, M., Werner, C. M., and Travassos, G. H. (2012).
Checklist-based inspection technique for feature models review. In 2012 Sixth Brazilian
Symposium on Software Components, Architectures and Reuse, pages 140–149. IEEE.

de Mello, R. M., Nogueira, E., Schots, M., Werner, C. M. L., and Travassos, G. H. (2014). Verification of software product line artefacts: A checklist to support feature model inspections.
J. Univers. Comput. Sci., 20(5):720–745.


