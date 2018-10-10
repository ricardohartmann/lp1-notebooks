# PROJETOS

Este documento descreve padrões para entrega de projetos para as disciplinas do curso de Engenharia de Software ministradas pelo professor Alan R. Fachini.

## DATAS

* *24/10* Entrega da primeira versão do trabalho escrito
* *05/12* Entrega da versão final do trabalho escrito e apresentações

As apresentações devem ter entre 15 e 20 minutos.

## BONS PROJETOS

Bons projetos vêm de estudantes escolhendo uma área de aplicação na qual eles estão interessados, ou escolhendo algum subcampo de aplicação que eles querem explorar mais. Então, escolha um tema pelo qual você está, ou pode ficar apaixonado! Seja corajoso ao invés de tímido, e sinta-se à vontade para propor coisas ambiciosas com as quais você está animado. Só não se esqueça de pedir ajuda ao professor se você não tiver certeza de como começar.

Considerarei um projeto como *muito bom* se ele for publicável ou quase publicável em eventos da SBC (Sociedade Brasileira de Computação)

Depois de identificar um tópico de interesse, pode ser útil pesquisar por projetos similares usando palavras-chave relacionadas em um mecanismo de pesquisa acadêmico, como o [Google Scholar](http://scholar.google.com).

Além disso, espero ver no trabalho escrito uma metodologia sólida e a discussão de análise ou de resultados obtidos quando necessário.

## AVALIAÇÃO DO PROJETO

Os projetos serão avaliados com base em:

* *Qualidade técnica*: o material técnico faz sentido? As coisas foram julgadas de forma razoáveis? Os algoritmos ou apps propostos são inteligentes e interessantes? Os autores transmitem uma nova visão sobre o problema e/ou algoritmos?
* *Qualidade acadêmica*: o artigo ou trabalho escrito apresenta rigor científico e está bem escrito?
* *Interesse*: os autores escolheram um problema interessante ou “real” para trabalhar, ou apenas um pequeno problema pelo qual ninguém se interessa? Esse trabalho pode ser útil e/ou ter impacto?
* *Inovação*: este projeto está aplicando uma técnica comum em novos problemas? O problema é fácil, mas a técnica é uma novidade?

## FORMATO DO ARTIGO

Os textos finais dos projetos devem ter no mínimo 8 páginas (incluindo apêndices e figuras) e no máximo 12. Pode conter páginas extras contendo apenas referências. Se você fez este trabalho em colaboração com outra pessoa, ou se alguém (como outro professor) o aconselhou sobre este trabalho, seu artigo deve reconhecer plenamente suas contribuições.

Nos nossos artigos seguimos o [formato da SBC](http://www.sbc.org.br/documentos-da-sbc/summary/169-templates-para-artigos-e-capitulos-de-livros/878-modelosparapublicaodeartigos). Por favor use o template no formato LaTeX. O uso do LaTeX já lhe confere credibilidade junto ao professor :)

A seguir descrevemos o que é esperado em cada sessão do artigo.

### 1 RESUMO
Aproximadamente um parágrafo.

O resumo é opcional. Deve conter um parágrafo consistindo na motivação para o seu trabalho e uma explicação de alto nível da metodologia você usou e resultados obtidos.

### 2 INTRODUÇÃO
Aproximadamente 0.5 ou 1 página.

Explique o problema e porque ele é importante. Discuta sua motivação para trabalhar com esse problema. Dê alguma fundamentação, se necessário.

Por exemplo, se seu artigo é sobre a aplicação de um algoritmo de Aprendizado de Máquina, indique claramente o que é a entrada e a saída do projeto. Seja bastante explícito: “A entrada para o nosso algoritmo é uma
{imagem, amplitude, idade do paciente, medições de chuva, vídeo em escala de cinza, etc.}. Nós então usamos um {SVM, rede neural, regressão linear, etc.} para produzir uma previsão de {idade, preço das ações, tipo de câncer, gênero musical, etc.}.

### 3 TRABALHOS RELACIONADOS
Aproximadamente 0.5 ou 1 página.

Você deve encontrar projetos similares a ideia que você quer desenvolver, agrupá-los em categorias com base em suas abordagens e discutir seus pontos fortes e fracos, bem como em quais aspectos eles são semelhantes e diferem do seu trabalho. Na sua opinião, quais abordagens eram inteligentes e boas? Qual é o estado de arte na área de pesquisa? A maioria das pessoas executa a tarefa manualmente? Você deve procurar ter pelo menos 5 referências no trabalho relacionado. Incluir tentativas anteriores de outras pessoas para resolver o seu problema, métodos técnicos anteriores. Use o [Google Scholar](https://scholar.google.com).

### 4 CONJUNTO DE DADOS E RECURSOS USADOS
Aproximadamente 0.5 ou 1 página.

Esta seção é apenas necessária para projetos onde existe a aplicação de algoritmos de Aprendizado de Máquina.

Descreva seu conjunto de dados. Quantos exemplos de treinamento, validação e teste você possui? Existe qualquer pré-processamento que você fez? E quanto a normalização ou aumento de dados? Qual é a resolução de suas imagens? Como seus dados de séries temporais são discretizados? Inclua uma citação sobre de onde você obteve seu conjunto de dados. Dependendo do espaço disponível, mostre alguns exemplos do seu conjunto de dados. Você também deve falar sobre os recursos que você usou. Se você extraiu características usando transformadas de Fourier, word2vec, histograma de gradientes orientados (HOG), PCA, etc, certifique-se de falar sobre isso. Tente incluir exemplos de seus dados no relatório (por exemplo, incluir uma imagem, mostrar uma forma de onda, o cabeçalho da tabela, etc.).

### 5 MÉTODO
Aproximadamente 1 ou 2 página.

Descreva nesta seção os algoritmos, arquiteturas ou frameworks (arcabouços) estudados ou desenvolvidos. Certifique-se de incluir notações matemáticas ou gráficos relevantes que colaborem com o entendimento. Para cada um, dê uma breve descrição de aproximadamente um parágrafo. Como professor, estou preocupado em avaliar a sua compressão sobre cada um.

Em projetos de negócio, descreva a área de mercado que você está explorando, as técnicas que já foram usadas, cases de sucesso.

### 6 EXPERIMENTOS/RESULTADOS/DISCUSSÃO
Aproximadamente 1 e 3 páginas.

Como você deve ter percebido, esta seção pode ter três tipos de nomes: Experimentos para quando você está testando algoritmos, resultados para quando você está descrevendo a aplicação de um algoritmo ou aplicação que você desenvolveu, ou então discussão quando você está apenas comparando uma ou mais técnica, framework ou arquitetura.

Em caso de algoritmos, você deve fornecer detalhes sobre quais parâmetros você escolheu e como você os escolheu. Antes de listar seu resultados, certifique-se de listar e explicar quais são suas principais métricas. Forneça equações para as métricas, se necessário.

Certifique-se de discutir as figuras e tabelas em seu texto principal em toda esta seção. Seus gráficos devem incluir legendas, rótulos de eixo e ter tamanhos de fonte legíveis quando impressos.

### 7 CONCLUSÃO E TRABALHOS FUTUROS
Aproximadamente 1 e 2 parágrafos.

Resuma seu trabalho e reitere os pontos-chave. Quais abordagens tiravam melhor resultado? Por que você acha que algumas abordagens funcionaram melhor que outros? Para trabalho futuro, se você tivesse mais tempo, mais membros da equipe ou mais recursos computacionais, o que você exploraria? Quais ideias você teve a partir desse trabalho?

### 9 CONTRIBUIÇÕES

A seção de contribuições não está incluída no limite de 8 páginas. Esta seção deve descrever o que cada membro da equipe fez e contribuições para o trabalho. Se tiveram ajuda ou conversaram com pessoas de fora da aula, por favor indiquem aqui. Se usaram dados de suas empresas, por favor agradeçam elas aqui.

### 10 REFERÊNCIAS (sem limite de páginas)

Esta seção deve incluir citações para quaisquer trabalhos mencionados na seção de trabalhos relacionados. Artigos descrevendo algoritmos que você usou e que não foram abordados na aula. Código ou bibliotecas que você baixou e usou.
