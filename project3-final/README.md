# Projeto Redes de Regulação Gênica na Plasticidade Fenotípica de _Apis mellifera_
## Project Gene Regulatory Networks in the Phenotypic Plasticity of _Apis mellifera_

# Equipe
|Nome  | RA | Especialização|
|--|--|--|
| Arimã Batista  | 194347  | Computação |
| Diego Monego  | 291074  | Computação |
| Jaqueline Aguilar | 298311  | Computação |
| Sarah Calado | 29582  | Biologia |
| Vitor Klipel | 289610  | Biologia |
| Victor Machado| 299880  | Computação |

# Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação [*Ciência e Visualização de Dados em Saúde*](https://github.com/datasci4health), oferecida no segundo semestre de 2025, na Unicamp.

# Descrição Resumida do Projeto

A diferenciação entre rainhas e operárias em _Apis mellifera_ é influenciada por fatores nutricionais, genéticos e epigenéticos, que moldam padrões distintos de expressão gênica durante o desenvolvimento larval. Entre esses fatores, destaca-se o papel da alimentação, que direciona o desenvolvimento das castas e resulta em diferenças estruturais e funcionais, como o número e a atividade dos ovaríolos. Durante esse processo, mais de duzentos genes e diversas vias de sinalização são modulados, acompanhados por alterações epigenéticas que contribuem para a formação dos programas de desenvolvimento específicos.

Este projeto investigou possíveis relações entre os genes expressos exclusivamente nos ovários larvais de operárias e seu potencial de ativação ovariana na fase adulta, especialmente na ausência da rainha. A motivação central foi compreender como esses genes podem estar associados à plasticidade fenotípica das células e à capacidade de diferenciação.

A análise integrou técnicas de ciência de redes, enriquecimento funcional e mineração de textos científicos. Os dados foram estruturados e filtrados por meio de workflows no Orange Data Mining, enriquecidos com ferramentas como DAVID, OrthoDB e KEGG, e utilizados para construção e visualização de redes gênicas no Cytoscape. A literatura consultada ajudou a contextualizar os achados, especialmente em relação ao citocromo P450.

Os resultados destacaram a presença do gene CYP6AQ1 e do composto quercetina, ambos já relacionados na literatura à diferenciação e ativação das gônadas e à modulação da inibição ovariana pelo feromônio mandibular da rainha. Esses elementos mostraram-se consistentes com as redes construídas e com os padrões observados ao longo das análises.

De forma geral, o projeto estruturou um fluxo integrado para explorar mecanismos associados à plasticidade fenotípica em Apis mellifera, combinando dados biológicos, redes gênicas e evidências textuais para apoiar a interpretação das possíveis funções dos genes exclusivos das operárias.

# Slides
[Link para slides da apresentação final](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project3-final/assets/slides/Bees%20-%20Apresentação%20Final.pdf)

# Fundamentação Teórica

Na natureza, existe uma ampla diversidade social no grupo das abelhas, que inclui tanto espécies solitárias quanto espécies altamente sociais (eussociais), como a abelha _Apis melífera_ (REHAN et al., 2018). Essa elevada sociabilidade resulta em uma organização complexa das colônias, caracterizada pela divisão do trabalho, cuidado cooperativo da prole e sobreposição de gerações, com rainhas responsáveis pela reprodução e operárias desempenhando tarefas dentro e fora do ninho (WILSON, 1971).

Em _Apis mellifera_, a diferença entre rainhas e operárias é determinada pela alimentação larval: larvas que recebem geleia real durante todo o desenvolvimento tornam-se rainhas, enquanto as demais, alimentadas com uma mistura de mel, pólen e geleia real, desenvolvem-se como operárias (HOOVER et al, 2003). Essa diferença nutricional gera o dimorfismo entre as castas: rainhas são férteis e possuem centenas de ovaríolos, enquanto operárias apresentam poucos e geralmente inativos (HARTFELDER et al., 2018).

A diferenciação ocorre ainda no período larval, quando grandes diferenças na expressão gênica se estabelecem entre rainhas e operárias, envolvendo mais de duzentos genes e diversas vias de sinalização sensíveis ao estado nutricional (VOJVODIC et al., 2015). Além disso, alterações epigenéticas, como metilação do DNA e modificações da cromatina, também participam da regulação dos programas de desenvolvimento de cada casta (FORET et al., 2012).

Assim, a formação de rainhas e operárias em _Apis mellifera_ é um processo complexo, determinado pela interação entre fatores nutricionais, genéticos e epigenéticos. Nesse contexto, este trabalho pode contribuir para o estudo dos mecanismos de plasticidade fenotípica e para o avanço do conhecimento sobre a biologia das abelhas, o que é essencial para fortalecer ações de preservação e incentivar programas de manejo e manutenção das espécies, considerando sua grande importância ecológica, econômica e ambiental.

# Perguntas de Pesquisa

O presente trabalho buscou identificar possíveis relações entre os genes expressos exclusivamente nos ovários larvais das operárias e seu potencial de ativar os ovários quando adulta e na ausência da rainha, relacionando-os com a plasticidade fenotípica das células e sua capacidade de se diferenciar.

Com o desenvolvimento das atividades, foi possível encontrar a presença de um tipo de citocromo P450 (CYP6AQ1) e o flavonóide quercetina. Estes já foram descritos anteriormente na diferenciação e ativação das gônadas das abelhas e como regulador da inibição dos ovários provocada pelo ferormônio mandibular da rainha.

# Metodologia

Este projeto adota uma abordagem baseada em técnicas de Ciência de Redes para analisar a estrutura, dinâmica e padrões emergentes da rede biológica em estudo. A metodologia compreende desde a construção e pré-processamento das redes até a aplicação de métricas específicas. Cada técnica é escolhida para responder a questões específicas relacionadas à organização e funcionalidade dos genes expressos durante o desenvolvimento larval tardio de _Apis mellifera_, com ênfase na diferenciação entre ovários de operárias e rainhas.

Para identificar os genes expressos exclusivamente nos ovários de operárias nesse estágio, foi desenvolvido um workflow na ferramenta Orange Data Mining, que possibilita o pré-processamento e a integração dos dados genômicos. Complementarmente, utilizaram-se ferramentas especializadas, como DAVID, OrthoDB e KEGG, para análise de enriquecimento funcional dos genes, permitindo identificar processos biológicos relevantes associados aos conjuntos gênicos selecionados.

Com os dados estruturados, a ferramenta Cytoscape foi empregada para a geração e visualização das redes gênicas. A análise combinada dessas redes evidenciou vias metabólicas e proteínas de alto valor funcional, integrando ainda a análise e mineração de textos científicos para melhor compreensão da biologia molecular da espécie.

## Bases de Dados e Evolução

As bases de dados iniciais utilizadas neste estudo foram originadas da tese intitulada "Reconstrução das Redes Cis-Reguladoras do Desenvolvimento de Ovários de Operárias e Rainhas de Abelhas Melíferas", de autoria de Izabella Cristina Silva, e cedidas pelo grupo de pesquisa (Laboratório de Genômica Comparativa do Desenvolvimento). Os dados foram disponibilizados em formato de planilhas eletrônicas.

Base de Dados | Resumo descritivo
----- |  -----
genes_exclusivos_ov_operarias.txt | Lista contendo 3.449 genes exclusivos das operárias, ausentes na expressão ovariana das rainhas.
int-targets-fts-worker.csv | Breve resumo (duas ou três linhas) sobre a base.

A base *genes_exclusivos_ov_operarias.txt* apresentou uma listagem de 3.449 genes exclusivos das operárias, ou seja, genes ausentes na expressão ovariana das rainhas. Durante a análise, identificou-se que alguns símbolos genéticos possuíam o sufixo “LOC”, o que dificultava a comparação entre bases. Por esse motivo, procedeu-se à remoção desses sufixos para uniformizar os símbolos gênicos entre as bases.

A base *int-targets-fts-worker.csv*, com seus 1.463 registros, apresentou múltiplas entradas para diferentes símbolos genéticos. Cada registro contém o identificador do gene (Gene ID), símbolo (Gene Symbol), motivos (motifs), módulos associados (identificados por meio do pacote WGCNA) e a presença de sítios de ligação para fatores de transcrição (TFBSs), detectados pelos algoritmos HOMER denovo e HOMER compare.

A partir da lista da base *genes_exclusivos_ov_operarias.txt*, foi realizada a filtragem dos genes exclusivos das operárias presentes na base *int-targets-fts-worker.csv*, resultando na criação de três bases derivadas para análises específicas:

Base de Dados | Lolização | Resumo descritivo
----- | ----- | -----
motivos-genes-total.csv | [2025/project2/](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project2/motivos-genes-total.csv) | 76 registros estruturados em Genes symbol e motivo (motif).
motivos-genes.csv | [2025/project2/](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project2/motivos-genes.csv) | 21 registros com Genes symbol e motivo (motif) com TFBs identificados.
geneID_david.csv | [2025/project2/](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project2/geneID_david.csv) | Lista com 15 Gene IDs para enriquecimento via DAVID.

## Modelo Lógico

O modelo lógico apresentado ilustra o fluxo completo desenvolvido ao longo do estudo, destacando as etapas e ferramentas utilizadas durante o processo.

![Modelo Lógico de Estudo](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project3-final/assets/images/modelo-logico-estudo.jpg)

Foram geradas duas redes gênicas distintas: a primeira composta por 76 interações entre genes exclusivos das operárias e seus respectivos motivos (motifs); e a segunda contendo somente as interações para genes em que foi possível identificar fatores de transcrição (TFBs) relacionados.

O modelo lógico apresentado a seguir demonstra como esses dados foram organizados para a construção das redes, estruturadas como grafos direcionados.

Nessa representação, os nós ovais correspondem aos genes (identificados pelo geneID) e aos motivos associados a eles, representados por retângulos. Por meio da ferramenta Cytoscape, esses nós foram enriquecidos com os arquivos estruturados e gerados durante o estudo, otimizando o processo de análise das redes.

![Modelo Lógico de Grafos](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project3-final/assets/images/modelo-logico-grafos.jpg)

## Integração entre Bases

A integração das bases de dados neste estudo apresentou diversos desafios, principalmente relacionados à uniformização de nomenclaturas e registros entre as fontes distintas. Para superar essas questões, foram desenvolvidos algoritmos específicos de filtragem, implementados por meio da ferramenta Orange Data Mining, além de processos manuais para identificação e correção de inconsistências nos dados.

O workflow [data-structure.ows](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project2/data-structure.ows) documenta detalhadamente o processo de estruturação dos dados iniciais, incluindo a identificação dos genes exclusivos das operárias e a organização para a criação das redes gênicas. Este workflow também incorpora os dados provenientes da ferramenta DAVID, utilizados para o enriquecimento funcional da rede gênica.

Adicionalmente, o workflow [paper-analysis.ows](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project3-final/pipelines/workflows/paper-analysis.ows) resume o processo de estruturação e aplicação de técnicas para o reconhecimento de padrões para análise e mineração de texto em artigos científicos. Essa etapa teve o objetivo de validar as descobertas da análise de redes, consolidando os resultados obtidos.

## Análises Realizadas e Evolução do Projeto

Inicialmente, o estudo focava exclusivamente na criação de modelos lógicos e no seu enriquecimento por meio de anotações extraídas com a ferramenta DAVID. Contudo, durante o desenvolvimento, verificou-se que alguns genes não foram identificados pela ferramenta, e outros não puderam ser caracterizados adequadamente. Essa limitação no mapeamento e enriquecimento poderia comprometer a abrangência das interações relevantes para as análises.

Para contornar essa dificuldade, foi realizado um mapeamento manual dos ortólogos humanos para os 15 genes de _Apis mellifera_ identificados. A busca desses ortólogos foi efetuada na ferramenta OrthoDB, empregando os gene IDs como parâmetro. Os ortólogos humanos identificados foram posteriormente submetidos à análise na ferramenta KEGG, com o objetivo de identificar as vias biológicas associadas, gerando o arquivo [orthoDB_gene.csv](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project2/orthoDB_gene.csv) para enriquecimento das redes gênicas.

Além disso, foi implementada uma etapa de análise e mineração de textos científicos focada em artigos que abordam a atividade do citocromo P450, uma proteína destacada nos modelos gerados e relacionada à diferenciação de castas e estágios de desenvolvimento em _Apis mellifera_. Ao todo, oito artigos foram selecionados após análise criteriosa. O workflow [paper-analysis.ows](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project3-final/pipelines/workflows/paper-analysis.ows) sintetiza o processo de estruturação e aplicação das técnicas para reconhecimento de padrões e geração dos resultados.

O objetivo dessa etapa foi estabelecer um paralelo entre o conhecimento presente na literatura científica e as descobertas obtidas pela equipe de pesquisa, fortalecendo a validação dos resultados.

# Ferramentas

O desenvolvimento do projeto envolveu um conjunto diversificado de ferramentas voltadas à mineração de dados, análise de redes biológicas, enriquecimento funcional e consulta de bases especializadas em biologia molecular. Cada ferramenta contribuiu para uma etapa específica do fluxo de trabalho, desde a preparação inicial dos dados até a contextualização biológica dos achados. A tabela abaixo sumariza as ferramentas utilizadas, juntamente com o objetivo de cada uma para o projeto.

| Ferramenta         | Categoria                       | Finalidade no Projeto                                                                                                       |
| ------------------ | ------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Orange Data Mining | Mineração de dados              | Tratamento dos dados e criação das redes.                                                                                   |
| Cytoscape          | Visualização e análise de redes | Cálculo de métricas e visualização dos grafos.                                                                              |
| DAVID              | Enriquecimento funcional        | Identificação do Processo Biológico e outros termos GO                                                                      |
| OrthoDB            | Base de ortólogos               | Extração de ortólogos humanos dos genes encontrados                                                                         |
| KEGG               | Base de vias de sinalização     | Consulta e identificação de vias metabólicas e funcionais associadas aos genes analisados                                   |
| PubMed             | Base de artigos científicos     | Consulta de literatura para identificar estudos relacionados aos genes analisados e possibilitar interpretações biológicas. |

Em conjunto, essas ferramentas permitiram estruturar, analisar e interpretar os dados de forma coerente ao longo das etapas do projeto. Enquanto o Orange e o Cytoscape estruturaram e exploraram as redes geradas, bases como DAVID, OrthoDB, KEGG e PubMed forneceram o suporte biológico necessário para contextualizar os achados e enriquecer a interpretação das relações entre os genes estudados.

# Resultados

A análise dos ortólogos humanos revelou três vias e proteínas de maior relevância: citocromos P450, receptores colinérgicos nicotínicos e dineínas axonemais. Entre essas, a família citocromo P450 apresentou os padrões mais consistentes e integrados com os demais resultados obtidos. Por esse motivo, ela foi selecionada como foco das análises subsequentes, incluindo a etapa de construção e exploração das redes de textos.

# Discussão

O citocromo P450 diz respeito à uma família de enzimas responsáveis por metabolizar substâncias endógenas, assim como xenobióticos. A partir de nossas análises, os termos CYP6AQ1 e quercetina chamaram atenção. CYP6AQ1 faz parte do citocromo P450 em abelhas, e é uma enzima do tipo monooxigenase que participa da detoxificação de xenobióticos, como o inseticida FPF. Segundo Lago et al. (2023), análises de RNA-seq combinadas com reconstrução filogenética indicam que essa enzima também pode estar envolvida em vias de sinalização relacionadas à diferenciação e ativação das gônadas das abelhas, atuando na metabolização de substratos endógenos. Já a quercetina é um flavonoide presente no néctar e no pólen, compondo parte da alimentação das abelhas. Esse composto atua como regulador da resposta ao feromônio responsável por inibir a ativação dos ovários das operárias. Em Gao et al. (2010), abelhas foram alimentadas com geleia contendo diferentes concentrações de quercetina, e observou-se que operárias expostas às maiores concentrações desenvolveram os ovários e chegaram a produzir ovos. O aumento desse composto na dieta diminui o efeito do feromônio da rainha, reduzindo a capacidade das operárias de detectá-lo por meio de seus sensores. Como consequência, ocorrem alterações comportamentais, incluindo ataques das operárias às rainhas, o que compromete o equilíbrio e a estabilidade da colônia.

# Conclusão

> Destacar as principais conclusões obtidas no desenvolvimento do projeto.
>
> Destacar os principais desafios enfrentados.
>
> Principais lições aprendidas.

# Trabalhos Futuros

> O que poderia ser melhorado se houvesse mais tempo?
> Quais possíveis desdobramentos este projeto pode ter?

# Referências Bibliográficas

REHAN et al. Conserved Genes Underlie Phenotypic Plasticity in an Incipiently Social Bee. Genome Biology and evolution, v. 10, n. 10, p. 2749. https://doi.org/10.1093/gbe/evy212

WILSON, E. O. The insect societies. The insect societies., 1971

HOOVER et al. The effect of queen pheromones on worker honey bee ovary development. Naturwissenschaften, v. 90, n. 10, p. 4773480, 18 out. 2003. DisponÌvel em: https://doi.org/10.1007/s00114-003-0462-z.

HARTFELDER et al. The ovary and its genes4developmental processes underlying the establishment and function of a highly divergent reproductive system in the female castes of the honey bee, _Apis mellifera_. Apidologie, v. 49, n. 1, p. 49370, 1 fev. 2018. DisponÌvel em: https://doi.org/10.1007/s13592-017-0548-9.

VOJVODIC et al. The transcriptomic and evolutionary signature of social interactions regulating honey bee caste development. Ecology and Evolution, v.5, n. 21, p. 4795–4807. https://doi.org/10.1002/ece3.1720. 

FORET et al. DNA methylation dynamics, metabolic fluxes, gene splicing, and alternative phenotypes in honey bees. Proceedings of the National Academy of Sciences of the United States of America, v. 109, n. 13, p. 496834973, 2012. https://doi.org/10.1073/pnas.1202392109 

LAGO et al. Positive selection in cytochrome P450 genes is associated with gonad phenotype and mating strategy in social bees. Sci. Rep. v.13, p. 5921, 2023. https://doi.org/10.1038/s41598-023-32898-6. 

GAO et al. High concentration of nectar quercetin enhances worker resistance to queen's signals in bees. Journal of Chemical Ecology, v.36, n. 11, p. 1241-3. https://doi.org/10.1007/s10886-010-9866-3
