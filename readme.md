# Visão Geral sobre TDD

    Na comunidade Ruby, o uso de TDD(testdriven development) é constante e todo o projeto open-source famoso na comunidade possui testes automatizados. Um desenvolvedor Ruby completo possui esse padrão no dia a dia. 
  <br>

#### **1.1 TDD e sua história . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .**

    O TDD surgiu primeiramente com a biblioteca **SUnit**, criada por Kent Beck, a ideia dele era facilitar a execução dos testes, então ele automatizou essa tarefa que era realizada manualmente. Isso na década de 90. Após alguns anos, em um evento bem famoso de orientação a objetos, o OOPSLA(ObjectOriented Programming, Systems, Languages & Applications), Kent Beck e Erich Gamma escreveram uma versão do SUnit em Java, o **JUnit**.
<br>
    O JUnit, ele ganhou muito epaço no mundo de desenvovimento de software, e foi sendo desenvolvido para outras linguagens, como Ruby, C++, Perl, Python, PHP e outras. Esse padrão formada por todas esses bibliotecas, recebeu o nome de**xUnit**.
~~
    A biblioteca xUnit amadureceu, utilizar a biblicateca em si, não era mais visto apenas como uma atividade de teste, mas sim como uma atividade de design de (projeto) de código. Esse visão fez sentindo, porque, antes de implementar um determinado método ou classe, os usuários de xUnit, primeiro escrevem um teste, especificando o comportamento esperado, para depois fazer o código que vai fazer com que esse teste passe. Ao fazer uso das bibliotecas do xUnit, se originou o nome de testdriven development (TDD).
~~
    No final da década de 90, Kent Beck formaliza o o Extreme Programming (XP), que viria a ser uma das principais metodologias ágeis de desenvolvimento de software do mundo. O XP, possui algumas práticas essenciais, entre elas o TDD.
~~
   Entrando na linguagem Ruby, a primeira biblioteca de testes automatizados foi escrita por Nathaniel Talbott, recebeu o nome de Lapidary. O Lapidary, foi apresentando na primeira RubyConf da história em 2002. Apartir do Lapidary surgiu o Test::Unit, que é a tradicional biblioteca xUnit em Ruby, que é utilizada até hoje. TDD em Ruby, desde o começo da comunidade, sempre foi a regra e não a excessão, todo o projeto open-source em Ruby que se preza, possui testes automatizados.
~~
  Em 2003, David Heinemeier Hansson (DHH) escreveu o Ruby on Rails, ou somente Rails. Rails se tornou tão bom, que as pessoas começaram a aprender Ruby, só por causa dele, por padrão, todo o projeto em Rails, já vem com um diretório específico para os testes automatizados, Rails te convida a fazer TDD.
~~
  TDD hoje é uma prática vista como uma das bases para desenvolvimento de software com qualidade e de fácil manutenção.
~~

#### **1.2 E por qual motivo eu deveria usar TDD? . . . . . . . . . . . . . . . . .**
