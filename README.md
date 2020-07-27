![eng_soft](https://miro.medium.com/max/3200/1*if1uQe4ZeFF3zT0jDKLGRA.jpeg)
# Aprovação em Engenharia de Software
![forthebadge](https://forthebadge.com/images/badges/made-with-java.svg)

Estudaremos aqui os tópicos para um melhor entendimentos nas aulas de Engenharia de Software III.

Abordaremos os assuntos:

 - Orientação a Objetos
 - SOLID
 - Design Patterns:
   - DAO
   - Façade
   - Strategy
   - Command
   - View Helper
 - UML
 - Arquitetura em camadas
 - Arquitetura MVC

É bom desde já escolhermos uma linguagem. Tenho uma forte opinião do uso do Java (me julguem), tendo em vista que as aulas de Engenharia de Software são em Java (e também não conheço C#).

## Orientação a Objetos

![POO](https://cdn.wallpapersafari.com/43/40/7c8kqr.png)

Nesse primeiro tópico, não creio que precisemos nos aprofundar em orientação a objetos, apenas imagino que apenas entender bem coisas mais básicas (cruciais para a aula, e bem características de linguagem) seja o suficiente.
Coisas como o uso de:

 - classes concretas;
 - classes abstratas;
 - interfaces;
 - List e ArrayList e
 - Map e HashMap.
 
### Material
 
Para começo, o vídeo [Abstração, Herança e Polimorfismo a base de um bom código](https://www.youtube.com/watch?v=qiGTRJlCnlA) da DevMedia é muito bom.

Alguns artigos pequenos, que explicam melhor (e de forma resumida) cada conceito: 

- [Conceitos Básicos de Orientação a Objetos — Parte 1](https://medium.com/gdgcampinas/conceitos-b%C3%A1sicos-de-orienta%C3%A7%C3%A3o-a-objetos-b58809b2d809)
- [Conceitos Básicos de Orientação a Objetos — Parte 2](https://medium.com/@RafaelSermenho/conceitos-b%C3%A1sicos-de-orienta%C3%A7%C3%A3o-a-objetos-parte-2-5accfe670a6e)

Agora, separando um pouco aqui, para quem prefere ver isso melhor em vídeo, recomendo o [Curso completo de POO em Java](https://www.youtube.com/playlist?list=PLHz_AreHm4dkqe2aR0tQK74m8SFe-aGsY) do Curso em Vídeo.

Para quem prefere ler um livro sobre o assunto, tem o [Orientação a Objetos](https://drive.google.com/file/d/1Frj0x3YExf5zdhFaRCPyL32YLpD0qdXi/view?usp=sharing) da casa do código.

_Ainda estou lendo o livro, logo mais posto os capítulos mais interessantes._

Sobre as estruturas de dados (List, ArrayList, Map e HashMap) pesquisem, não vai matar, e é rapidinho... mas vou deixar uns links aqui:

 - [Java Collections: Set, List e Iterator](https://www.devmedia.com.br/java-collections-set-list-e-iterator/29637)
 - [Java 101: Array vs ArrayList](https://medium.com/@thaisdalencar/java-101-array-vs-arraylist-a04950cfc522)
 - [Conhecendo a interface Map do Java](https://www.devmedia.com.br/conhecendo-a-interface-map-do-java/37463)
 - [HashMap Java: Trabalhando com Listas key-value](https://www.devmedia.com.br/hashmap-java-trabalhando-com-listas-key-value/29811)

## SOLID

![SOLID](https://miro.medium.com/max/3600/1*TjDnfpnw4gI8sZ2fvaK9zg.jpeg)

Aqui já é necessário um bom entendimento dos tópicos anteriores.
SOLID nada mais é do que um acrônimo que representa os 5 princípios da programação orientada a objetos (Tio Wikipédia).
Acredito que separarmos uma semana apenas para entender esse tópico vai nos ajudar bastante.
Tenho diversos links de artigos, vídeos e livros.

### Material

**Alguns artigos (tanto em português como em inglês):**
 - [SOLID com Java: Orientação a Objetos com Java](https://www.alura.com.br/conteudo/orientacao-a-objetos-avancada-e-principios-solid)
 - [O que é SOLID: O guia completo para você entender os 5 princípios da POO](https://medium.com/desenvolvendo-com-paixao/o-que-%C3%A9-solid-o-guia-completo-para-voc%C3%AA-entender-os-5-princ%C3%ADpios-da-poo-2b937b3fc530)
 - [Princípios S.O.L.I.D: o que são e porque projetos devem utilizá-los](https://medium.com/@mari_azevedo/princ%C3%ADpios-s-o-l-i-d-o-que-s%C3%A3o-e-porque-projetos-devem-utiliz%C3%A1-los-bf496b82b299)
 - [SOLID Principles every Developer Should Know](https://blog.bitsrc.io/solid-principles-every-developer-should-know-b3bfa96bb688)
 - [SOLID Principles: Explanation and examples](https://itnext.io/solid-principles-explanation-and-examples-715b975dcad4)
 - [The S.O.L.I.D Principles in Pictures](https://medium.com/backticks-tildes/the-s-o-l-i-d-principles-in-pictures-b34ce2f1e898) - Esse é meu favorito
 
**Os vídeos sobre o assunto (vejam na ordem. O vídeo em inglês é opcional):**
  - [SOLID (O básico para você programar melhor) // Dicionário do Programador](https://www.youtube.com/watch?v=mkx0CdWiPRA)
  - [SOLID - Teoria e Prática](https://www.youtube.com/watch?v=Q2QdkiX6p_Y)
  - [Becoming a better developer by using the SOLID design principles by Katerina Trajchevska](https://youtu.be/rtmFCcjEgEw)
  
Um bom livro sobre SOLID é o [SOLID para Ninjas](https://drive.google.com/file/d/1hJundIegQHJ-0SEPw9TD0Lv528kAVx_a/view?usp=sharing) também da casa do código.

## Design Patterns

![design_patterns](https://miro.medium.com/max/720/1*nwakpRp_GabhICWPNw5VDQ.png)

Aqui é onde o filho chora e a mãe não vê. Eles são bem de boas, mas sem um bom entendimento dos tópicos anteriores, vai tudo pra cucuia. Duas semanas aqui, sem nem pensar.

### Materiais

**Vídeos sobre o assunto:**
 - [O que são Design Patterns?](https://www.youtube.com/watch?v=8vq2QB4ogKM) - Bom ver esse vídeo da DevMedia primeiro, explica bem os básicos.
 - [Design Patterns // Dicionário do Programador](https://www.youtube.com/watch?v=J-lHpiu-Twk)
 - [Design Patterns in Object Oriented Programming](https://www.youtube.com/playlist?list=PLrhzvIcii6GNjpARdnO4ueTUAVR9eMBpc) - Se entende inglês, essa série de vídeos é muito boa.
 
_Não achei um curso em português_
 
**Alguns artigos:**
 - [Java — good practices and recommendations: Design patterns](https://blog.singular.uk/java-good-practices-and-recommendations-design-patterns-eade30be7965)

_Só achei um artigo, mas deve ter outros bons por aí, e em português... prometo achar._

 - [Padrões de Projeto](https://drive.google.com/file/d/1g_VZYRJSCBXVNuXZIBbr_-SBQog04N63/view?usp=sharing) - Livro utilizado nas aulas. Não é necessário a leitura completa, apenas alguns capítulos.
 
**Capítulos de importante a leitura:**
 - **Capítulo 1** - _Introdução_
 - **Capítulo 4, pg 179** - _Façade_
 - **Capítulo 5, pg 222** - _Command_
 - **Capítulo 5, pg 292** - _Strategy_

_O capítulo 2 e o capítulo 6 são de leitura opcional._

**DAO e ViewHelper**

Esses padres foram definidos pelo J2EE, então não aparecem no livro do GoF, mas podem ser vistos nos seguintes links:
 - **DAO:**
   - [Curso Java Completo - Aula 174: Padrões de projeto pt 03: Padrão DAO](https://www.youtube.com/watch?v=Ff8GVy4IfEg) - _vídeo_
   - [Java com Banco de Dados MySQL - #03 - Criando DAO e Salvando Dados](https://www.youtube.com/watch?v=EZPYKkPkN4A) - _vídeo_
   - [Criando classes DAO e Model para recuperar do Banco de Dados](https://www.youtube.com/watch?v=OnbvhKiIn4Y) - _vídeo_
 - **ViewHelper:**
   - [Padrão de Projeto View Helper em Java e seus paradoxos](https://www.devmedia.com.br/padrao-de-projeto-view-helper-em-java-e-seus-paradoxos/29052) - Único artigo bom que encontrei, o resto é bem meia boca.
   - [View Helper Design Pattern in Java](https://www.javaguides.net/2018/08/view-helper-design-pattern-in-java.html) - _artigo_
   - [View Helper Design Pattern – Core J2EE Patterns](https://www.dineshonjava.com/view-helper-design-pattern/) - _artigo_

## UML

![UML](https://i.pinimg.com/236x/20/32/03/2032034a440712c975bcf721517d79b9--class-diagram-software-development.jpg)

Um que eu sempre me ferro. Nunca lembro o que cada caixinha faz, se cada caixinha é necessária, qual a direção da seta, PQP. Isso aqui é necessário demais

### Material

Como esse tópico não é tão extenso, vou só deixar um curso mesmo que parece bom, o resto são só artiguinhos complementares.

 - [Curso de UML](https://www.youtube.com/watch?v=C3xYBT3o_5k&list=PLucm8g_ezqNqCRGHGHoacCo6N1bfN7hXZ&index=1) - _vídeos_
 - [Tutorial de Diagramas de Classes UML](https://www.youtube.com/watch?v=rDidOn6KN9k) - _vídeo_
 - [Diagrama de Classes](https://medium.com/documenta%C3%A7ao-uml/diagrama-de-classes-ba91a9d29575) - _artigo_
 - [Compreendendo Diagrama de Classes da UML na prática.](https://medium.com/studio-oceano/compreendendo-diagrama-de-classes-da-uml-na-pr%C3%A1tica-1f7e6422021c) - _artigo_
 - [UML Class Diagrams Tutorial, Step by Step](https://medium.com/@smagid_allThings/uml-class-diagrams-tutorial-step-by-step-520fd83b300b) - _artigo_
 - [UML Quick Reference](https://medium.com/federicohaag/uml-unified-modeling-language-5a2a0c2fb973) - _artigo_
 - [UML: por que menos pode ser mais?](https://medium.com/@ullmanngabriel/uml-por-que-menos-pode-ser-mais-56d05e118711) - _artigo_
 - [UML — Diagrama de Casos de Uso](https://medium.com/operacionalti/uml-diagrama-de-casos-de-uso-29f4358ce4d5) - _artigo_

## Arquitetura em camadas

![LAYERED](https://herbertograca.files.wordpress.com/2018/11/100-explicit-architecture-svg.png?w=1024)

_"Os componentes de uma arquitetura em camadas são organizados em camadas horizontais onde cada uma desempenha um papel específico na aplicação."_ (Achei por aí).

Com essa citação, meus amigos, começo dizendo que é bom a gente entender esse tópico, mas da pra fazer isso durante as aulas sem problemas. Mas sério, ele até chega a perguntar sobre isso em provas.

## Arquitetura MVC

![MVC](https://4.bp.blogspot.com/-pWUFlbiZUAI/Vx1XdepeCLI/AAAAAAAAAV4/unTNxfFZwUkiBHWFAMP29qfLzYRoKNOYwCLcB/s1600/layer.png)

É a arquitetura em camadas sem tirar nem por... Mas colocando algumas coisas. Ou tirando, não sei ainda :thinking:
Esse é o modelo arquitetural que a gente vai usar nas aulas.
É importante notar a diferença do padrão arquitetural MVC para o padrão em camadas ~que pra mim é 0, mas pro Rodrigo tem, e quem dá a nota é ele né...~
