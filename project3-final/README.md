# Projeto Redes de Regulação Gênica na Plasticidade Fenotípica de Apis mellifera
# Project Gene Regulatory Networks in the Phenotypic Plasticity of Apis mellifera

> |Nome  | RA | Especialização|
> |--|--|--|
> | Arimã Batista  | 194347  | Computação |
> | Diego Monego  | 291074  | Computação |
> | Jaqueline Aguilar | 298311  | Computação |
> | Sarah Calado | 29582  | Biologia|
> | Vitor Klipel | 289610  | Biologia|
> | Victor Machado| 299880  | Computação|


# Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação [*Ciência e Visualização de Dados em Saúde*](https://github.com/datasci4health), oferecida no segundo semestre de 2025, na Unicamp.

# Descrição Resumida do Projeto

> Descrição resumida do tema do projeto. Sugestão de roteiro (cada item tipicamente tratado em uma ou poucas frases):
>
> Contextualização do projeto
>
> Caracterização do problema
>
> Motivação
>
> Relevância
>
> Trabalhos relacionados
>
> Indicação (bastante resumida) da análise proposta
>
> Indicação (bastante resumida) dos resultados alcançados

# Slides
[Link para slides da apresentação final](https://github.com/datasci4health-2025-gp2-little-bees/2025/blob/main/project3-final/assets/slides/Bees%20-%20Apresentação%20Final.pdf)

# Fundamentação Teórica

> Na natureza, existe uma ampla diversidade social no grupo das abelhas, que inclui tanto espécies solitárias quanto espécies altamente sociais (eussociais), como a abelha Apis melífera (REHAN et al., 2018). Essa elevada sociabilidade resulta em uma organização complexa das colônias, caracterizada pela divisão do trabalho, cuidado cooperativo da prole e sobreposição de gerações, com rainhas responsáveis pela reprodução e operárias desempenhando tarefas dentro e fora do ninho (WILSON, 1971). Em Apis mellifera, a diferença entre rainhas e operárias é determinada pela alimentação larval: larvas que recebem geleia real durante todo o desenvolvimento tornam-se rainhas, enquanto as demais, alimentadas com uma mistura de mel, pólen e geleia real, desenvolvem-se como operárias (HOOVER et al, 2003). Essa diferença nutricional gera o dimorfismo entre as castas: rainhas são férteis e possuem centenas de ovaríolos, enquanto operárias apresentam poucos e geralmente inativos (HARTFELDER et al., 2018). A diferenciação ocorre ainda no período larval, quando grandes diferenças na expressão gênica se estabelecem entre rainhas e operárias, envolvendo mais de duzentos genes e diversas vias de sinalização sensíveis ao estado nutricional (VOJVODIC et al., 2015). Além disso, alterações epigenéticas, como metilação do DNA e modificações da cromatina, também participam da regulação dos programas de desenvolvimento de cada casta (FORET et al., 2012). Assim, a formação de rainhas e operárias em Apis mellifera é um processo complexo, determinado pela interação entre fatores nutricionais, genéticos e epigenéticos. Nesse contexto, este trabalho pode contribuir para o estudo dos mecanismos de plasticidade fenotípica e para o avanço do conhecimento sobre a biologia das abelhas, o que é essencial para fortalecer ações de preservação e incentivar programas de manejo e manutenção das espécies, considerando sua grande importância ecológica, econômica e ambiental.

# Perguntas de Pesquisa
> Perguntas de pesquisa (revisadas e atualizadas) que o projeto responde ou hipóteses que foram avaliadas, enunciadas de maneira objetiva e verificável.
> Apresente aqui como o projeto ajudou a responder as perguntas de pesquisa.

# Metodologia
> Proposta de metodologia incluindo especificação de quais as técnicas/métricas de Ciência de Redes que estão sendo usadas no projeto,
> tais como: detecção de comunidades, análise de centralidade, predição de links, ou a combinação de uma ou mais técnicas. Descreva o que perguntas pretende endereçar com a técnica escolhida.

## Bases de Dados e Evolução

> Para cada base, coloque uma entrada na tabela no modelo a seguir e depois detalhamento sobre como ela foi analisada/usada, conforme exemplo a seguir.

> Base de Dados | Endereço na Web | Resumo descritivo
> ----- | ----- | -----
> Título da Base 1 | http://base1.org/ | Breve resumo (duas ou três linhas) sobre a base.
> Título da Base 2 | http://base2.org/ | Breve resumo (duas ou três linhas) sobre a base.

> Faça uma descrição sobre o que concluiu sobre esta base. Sugere-se que respondam perguntas ou forneçam informações indicadas a seguir:
> * O que descobriu sobre essa base?
> * Quais as transformações e tratamentos (e.g., dados faltantes e limpeza) feitos?

## Modelo Lógico

> Modelo lógico da base de grafos revisado. Para o modelo de grafos de propriedades, utilize este
> [modelo de base](https://docs.google.com/presentation/d/10RN7bDKUka_Ro2_41WyEE76Wxm4AioiJOrsh6BRY3Kk/edit?usp=sharing) para construir o seu.
> Coloque a imagem do PNG do seu modelo lógico como ilustrado abaixo (a imagem estará na pasta `image`):
>
> ![Modelo Lógico de Grafos](images/modelo-logico-grafos.png)

## Integração entre Bases

> Descreva se houve desafios de integração de fontes de dados e etapas para a mesma.

## Análises Realizadas

> Apresente aqui uma análise dos dados.
> Utilize gráficos que descrevam os aspectos principais da base que são relevantes para as perguntas de pesquisa consideradas.
>
> Nesta seção ou na seção de Resultados podem aparecer destaques de código como indicado a seguir. Note que foi usada uma técnica de highlight de código, que envolve colocar o nome da linguagem na abertura de um trecho com `~~~`, tal como `~~~python`.
>
> Os destaques de código devem ser trechos pequenos de poucas linhas, que estejam diretamente ligados a alguma explicação. Não utilize trechos extensos de código. Se algum código funcionar online (tal como um Jupyter Notebook), aqui pode haver links. No caso do Jupyter, preferencialmente para o Binder abrindo diretamente o notebook em questão.

~~~python
df = pd.read_excel("/content/drive/My Drive/Colab Notebooks/dataset.xlsx");
sns.set(color_codes=True);
sns.distplot(df.Hemoglobin);
plt.show();
~~~

## Evolução do Projeto

> Relatório de evolução, descrevendo as evoluções na modelagem do projeto, dificuldades enfrentadas, mudanças de rumo, melhorias e lições aprendidas. Referências aos diagramas, modelos e recortes de mudanças são bem-vindos.
> Podem ser apresentados destaques na evolução do modelo lógico. O modelo inicial e intermediários (quando relevantes) e explicação de refinamentos, mudanças ou evolução do projeto que fundamentaram as decisões.
> Relatar o processo para se alcançar os resultados é tão importante quanto os resultados.

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

> Esta pode ser uma seção independente ou combinada com a seção de Análises Realizadas.
>
> Descrição dos resultados mais importantes obtidos.
>
> Apresente os resultados da forma mais rica possível, com gráficos e tabelas. Mesmo que o seu código rode online em um notebook, copie para esta parte a figura estática. A referência a código e links para execução online pode ser feita aqui ou na seção de Análises Realizadas (o que for mais pertinente).
> Como resultado das análises do ortólogos humanos, 3 principais vias/proteínas surgiram: citocromo P450, receptor colinérgico nicotínico e dineína axonemal. Para as análises posteriores (redes de textos), consideramos o citocromo P450. 

# Discussão

> Discussão dos resultados. Relacionar os resultados com as perguntas de pesquisa ou hipóteses avaliadas.
>
> A discussão dos resultados também pode ser feita opcionalmente na seção de Resultados, na medida em que os resultados são apresentados. Aspectos importantes a serem discutidos: Por que seu modelo alcançou (ou não) um bom resultado? É possível tirar conclusões dos resultados? Quais? Há indicações de direções para estudo? São necessários trabalhos mais profundos?
> O citocromo P450 diz respeito à uma família de enzimas responsáveis por metabolizar substâncias endógenas, assim como xenobióticos. A partir de nossas análises, os termos CYP6AQ1 e quercetina chamaram atenção. CYP6AQ1 faz parte do citocromo P450 em abelhas, e é uma enzima do tipo monooxigenase que participa da detoxificação de xenobióticos, como o inseticida FPF. Segundo Lago et al. (2023), análises de RNA-seq combinadas com reconstrução filogenética indicam que essa enzima também pode estar envolvida em vias de sinalização relacionadas à diferenciação e ativação das gônadas das abelhas, atuando na metabolização de substratos endógenos. Já a quercetina é um flavonoide presente no néctar e no pólen, compondo parte da alimentação das abelhas. Esse composto atua como regulador da resposta ao feromônio responsável por inibir a ativação dos ovários das operárias. Em Gao et al. (2010), abelhas foram alimentadas com geleia contendo diferentes concentrações de quercetina, e observou-se que operárias expostas às maiores concentrações desenvolveram os ovários e chegaram a produzir ovos. O aumento desse composto na dieta diminui o efeito do feromônio da rainha, reduzindo a capacidade das operárias de detectá-lo por meio de seus sensores. Como consequência, ocorrem alterações comportamentais, incluindo ataques das operárias às rainhas, o que compromete o equilíbrio e a estabilidade da colônia.

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

> REHAN et al. Conserved Genes Underlie Phenotypic Plasticity in an Incipiently Social Bee. Genome Biology and evolution, v. 10, n. 10, p. 2749. https://doi.org/10.1093/gbe/evy212

WILSON, E. O. The insect societies. The insect societies., 1971

HOOVER et al. The effect of queen pheromones on worker honey bee ovary development. Naturwissenschaften, v. 90, n. 10, p. 4773480, 18 out. 2003. DisponÌvel em: https://doi.org/10.1007/s00114-003-0462-z.

HARTFELDER et al. The ovary and its genes4developmental processes underlying the establishment and function of a highly divergent reproductive system in the female castes of the honey bee, Apis mellifera. Apidologie, v. 49, n. 1, p. 49370, 1 fev. 2018. DisponÌvel em: https://doi.org/10.1007/s13592-017-0548-9.

VOJVODIC et al. The transcriptomic and evolutionary signature of social interactions regulating honey bee caste development. Ecology and Evolution, v.5, n. 21, p. 4795–4807. https://doi.org/10.1002/ece3.1720. 

FORET et al. DNA methylation dynamics, metabolic fluxes, gene splicing, and alternative phenotypes in honey bees. Proceedings of the National Academy of Sciences of the United States of America, v. 109, n. 13, p. 496834973, 2012. https://doi.org/10.1073/pnas.1202392109 

LAGO et al. Positive selection in cytochrome P450 genes is associated with gonad phenotype and mating strategy in social bees. Sci. Rep. v.13, p. 5921, 2023. https://doi.org/10.1038/s41598-023-32898-6. 

GAO et al. High concentration of nectar quercetin enhances worker resistance to queen's signals in bees. Journal of Chemical Ecology, v.36, n. 11, p. 1241-3. https://doi.org/10.1007/s10886-010-9866-3
