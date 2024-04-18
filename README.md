[# Acessibilidade](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/What_is_accessibility)

Quando tocamos no assunto acessibilidade digital, não estamos falando somente sobre a possibilidade de acessar um Website através de um navegador que é utilizado por várias pessoas.

Na Web, o termo acessibilidade se refere à quanto um Website é acessível para todos os tipos de público, **principalmente** para que **pessoas com deficiência** **consigam utilizá-lo**. Isso significa que, mesmo que o usuário seja portador de qualquer doenças, transtornos ou deficiências de fala, visual, auditiva, cognitiva, neurológica ou física, ele deve ser capaz de entender, navegar, interagir e contribuir com a Web.

Mas acessibilidade não se refere exclusivamente a pessoas com deficiências ou necessidades especiais. Acessibilidade é sobre tornar a experiência da Web melhor para todos os usuários, desde a forma como as cores são usadas para tratar o contraste e legibilidade da página; atalhos de teclado; ou até a legenda em um vídeo, que não só ajuda deficientes auditivos a entender sobre o que o vídeo se trata, mas também para quem possui dificuldades temporárias, como, por exemplo, um ambiente barulhento, vídeo em outro idioma, onde existe dificuldade para entender o que é dito, ou até mesmo a utilização dessa funcionalidade por preferência.

> O poder da Web está em sua universalidade. O acesso de todos, independentemente da deficiência, é um aspecto essencial.

*- TIM BERNERS-LEE (Criador da WEB)*
>
Então, visando maneiras de melhorar toda essa experiência, surgiram iniciativas como a Web Accessibility Initiative, criada em 1997, com o objetivo de melhorar a acessibilidade da WEB para pessoas com deficiências, criando diversas diretrizes e materiais educacionais sobre o assunto, e iniciou a WCAG (Web Content Accessibility Guidelines).

Então, visando maneiras de melhorar toda essa experiência, surgiram iniciativas como a Web Accessibility Initiative, criada em 1997, com o objetivo de melhorar a acessibilidade da WEB para pessoas com deficiências, criando diversas diretrizes e materiais educacionais sobre o assunto, e iniciou a WCAG (Web Content Accessibility Guidelines).
 [## WCAG]( https://www.w3.org/WAI/fundamentals/)

A WCAG (Web Content Accessibility Guidelines) busca introduzir uma série de diretrizes, padrões, recomendações e documentos que explicam como tornar a Web mais acessível para pessoas com deficiência.

## A WCAG se baseia em quatro princípios:

- **Perceptível:** As pessoas devem conseguir ver o conteúdo, ou ouvir.
- **Operável:** As pessoas devem conseguir usar o computador através do teclado, ou por voz.
- **Compreensível:** O conteúdo contém linguagem clara e simples para que as pessoas compreendam com facilidade.
- **Robusto:** As pessoas devem conseguir utilizar diversos tipos de tecnologia assistivas.

### Critérios de sucesso

A WCAG 2.0 possui 61 critérios de sucesso, já a sua versão 2.1 possui 78 critérios de sucesso. Todos os 61 critérios de sucesso da WCAG 2.0 fazem parte da versão 2.1, que apenas adicionou 17 novos critérios de sucesso. As WCAG 3 terão requisitos de acessibilidade fundamentais e específicos semelhantes às WCAG 2. As WCAG 3 terão uma estrutura diferente, um modelo de conformidade diferente e um escopo mais amplo.

Os critérios de sucesso estão divididos em três níveis, nomeados como nível A, nível AA e nível AAA. Quanto maior o nível que seu Website for compatível, maior o grupo de pessoas para quem esse conteúdo é considerado acessível. 

- **Nível A:** Possui 30 critérios que devem ser atingidos para se chegar a esse nível, são critérios mais fáceis de atingir, tendo menor impacto na estrutura ou design do Website. Se você está iniciando, provavelmente o nível que você quer mirar é esse.
- **Nível AA:** Além de atingir todos os 30 critérios do nível A, deve-se atingir outros 20 critérios referentes ao nível AA. Isso significa que todo Website que atinge o nível AA já atingiu também o nível A. Eles possuem média complexidade e já alteram o design do site, como, por exemplo, para que o texto apresente níveis de contraste especificados. Em alguns países, tipos específicos de sites podem ser obrigados por lei a oferecer esse nível de acessibilidade. Grandes times de desenvolvimento ao redor do mundo tentam atingir pelo menos o nível AA, e é o nível comumente buscado quando se quer tornar um site acessível.
- **Nível AAA:** Adiciona novos 28 critérios para serem atingidos. Esse nível não é obrigatório, pois alguns de seus critérios não são possíveis em alguns tipos de conteúdos. Possuem maior complexidade, como regras ainda mais estritas sobre contraste. Mesmo assim, saber sobre eles e atingir alguns deles vai tornar seu site ainda mais acessível.

Dentro dos critérios do que é **perceptível** temos alguns como:

**[1.1.1 Conteúdo não textual:](https://www.w3.org/TR/WCAG21/#text-alternatives)** Atinge o nível A. Deve ser fornecido alternativas em formato de texto para quaisquer conteúdo que não seja texto, como imagens, gráficos, áudios, etc. Essas devem descrever da melhor forma possível exatamente o que o conteúdo multimídia está transmitindo, com algumas exceções, como inputs, imagens utilizadas de fundo ou decoração visual do website, obras de arte que dependem de uma experiência sensorial ou até mesmo atividades (testes) onde a descrição da imagem descreveria a resposta desse teste, então a descrição deve ser uma identificação para esse conteúdo. Você pode fazer isso utilizando a propriedade `alt` existente em elementos HTML para imagem. 

Esse critério beneficia, não exclusivamente, pessoas que tem dificuldade em perceber conteúdos visuais, como pessoas cegas, pessoas surdas ou que possuem deficiência auditiva, entre diversos outros grupos de pessoas beneficiadas.
**[1.4.3 Contraste (Minimo):](https://www.w3.org/TR/WCAG21/#contrast-minimum) [](https://www.w3.org/TR/WCAG21/#distinguishable)** Atinge o nível AA. Especifica o contraste mínimo que elementos de texto e imagens de texto devem possuir. Esse contraste é medido em comparação à cor do fundo e influencia diretamente na legibilidade e acessibilidade daquele texto. O nível de contraste varia de acordo com o tamanho do texto, mas também possui algumas exceções, como logos. 

Esse critério beneficia, não exclusivamente, pessoas que possuem dificuldade em ler conteúdos que não tem contraste suficiente com sua cor de fundo, como no caso de daltonismo ou acromatopsia.

**[1.4.4 Texto redimensionável:](https://www.w3.org/TR/WCAG21/#resize-text)** Atinge o nível AA. Os conteúdos em texto, exceto legendas e imagens de texto, devem poder ser redimensionados até 200% sem perder conteúdo ou funcionalidade.  

Esse critério permite que pessoas com baixa visão se beneficiem ao poder aumentar o tamanho dos textos para que consigam ler.
**[1.4.6  Contraste (Melhorado):](https://www.w3.org/TR/WCAG21/#contrast-enhanced)** Atinge o nível AAA. As regras de contraste são ainda mais estritas, especificam que você somente pode utilizar cores muito escuras em fundos muito claros, ou textos muito claros em fundos muito escuros.

Esse critério beneficia, não exclusivamente, pessoas que possuem dificuldade em ler conteúdos que não têm contraste suficiente com sua cor de fundo, como no caso de daltonismo ou acromatopsia.

Dentro dos critérios do que é **operável** temos alguns como:

**[2.1.1 Teclado:](https://www.w3.org/TR/WCAG21/#keyboard)** Atinge o nível A. Define que todo o conteúdo deve ser operável por meio de um teclado sem necessitar de um timing específico para uso das teclas. Existe algumas exceções, como, por exemplo, se a funcionalidade depender de um fluxo específico feito através dos movimentos do usuário.

Esse critério beneficia, não exclusivamente, pessoas cegas que não conseguem usar mecanismos como mouse, pessoas com baixa visão que podem ter dificuldade de encontrar o cursor do mouse e também pessoas que podem possuir tremores nas mãos, dificultando o uso de mouse e, por isso, usam o teclado como meio de navegação.
**[2.1.3 Teclado (sem exceções):](https://www.w3.org/TR/WCAG21/#keyboard-no-exception)** Atinge o nível AAA. Define exatamente a operabilidade do ponto 2.1.1, removendo totalmente a exceção relacionada aos movimentos do usuário, ou seja, todo o conteúdo deve ser operável por meio de um teclado sem necessitar de um timing específico para uso das teclas.

Esse critério beneficia, não exclusivamente, pessoas cegas que não conseguem usar mecanismos como mouse, pessoas com baixa visão que podem ter dificuldade de encontrar o cursor do mouse e também pessoas que podem possuir tremores nas mãos, dificultando o uso de mouse e, por isso, usam o teclado como meio de navegação.

**Bonus:** Para programadores ReactJS existem diversas bibliotecas focadas em acessibilidade, como a [Radix UI](https://www.radix-ui.com/), fornecendo componentes prontos que possuem navegação por teclado já implementadas além de outras funcionalidades de acessibilidade que você pode apenas utilizar em seus websites.

Dentro dos critérios do que é **compreensível** temos alguns como:

**[3.1.1 Idioma da página:](https://www.w3.org/TR/WCAG21/#language-of-page)** Atinge o nível A. A língua padrão da página pode ser configurada de maneira programática. Utilizando o HTML, pode ser configurado através do atributo `lang` no elemento `<html>` .
Esse critério beneficia, não exclusivamente, diversos grupos de pessoas que utilizam ferramentas que convertem o conteúdo de texto para áudio, como screen readers e text-to-speech.

**[3.1.3 Abreviações:](https://www.w3.org/TR/WCAG21/#abbreviations)** Atinge o nível AAA. Deve existir um mecanismo para exibir a forma expandida de abreviações utilizadas pelo conteúdo.

Esse critério beneficia, não exclusivamente, pessoas que possuem memória limitada e até mesmo pessoas com deficiências visuais e que usam ferramentas para amplificar o tamanho da tela e que perdem o contexto do conteúdo por conta dessa amplificação. Além disso, possui diversos outros benefícios como a melhor compreensão do contexto em geral, visto que nem todas as abreviações são óbvias.
**[3.2.3 Navegação consistente:](https://www.w3.org/TR/WCAG21/#consistent-navigation)** Atinge o nível AA. Formas de navegação que são repetidas em diversas páginas devem sempre manter a mesma ordem relativa, a não ser que o usuário consiga alterá-la. Isso facilita que os usuários entendam e prevejam onde os itens que se repetem entre páginas estarão. Alguns exemplos são a forma que um menu de navegação é posicionado ou a posição de um botão para se pular direto para o conteúdo principal do site.

Esse critério faz com que usuários se sintam mais confortáveis com a navegação do website, pois eles conseguirão prever onde cada coisa estará em cada página. Isso beneficia todos, mas é extremamente útil para pessoas com baixa visão, pessoas cegas ou com limitações cognitivas.

**[3.3.1 Identificação de erros:](https://www.w3.org/TR/WCAG21/#error-identification)** Atinge o nível A. Caso um erro em um input seja identificado automaticamente, esse erro deve ser descrito para o usuário em formato de texto.

Esse critério ajuda cegos e pessoas com daltonismo a entenderem que um erro ocorreu. Além de ajudar outros grupos de pessoas que possam ter dificuldades de entender ícones e outros indicativos visuais que representem o erro.
Dentro dos critérios do que é **robusto** temos alguns como:

**[4.1.3 Mensagens de status:**](https://www.w3.org/TR/WCAG21/#status-messages) Atinge o nível AA. Mensagens de status podem ser implementadas programaticamente para representar ações como, por exemplo, status de sucesso, erros de input ou falta de preenchimento de inputs obrigatórios, etc.

Quando utilizado corretamente, esse critério pode beneficiar usuários de leitores de tela, como pessoas cegas ou com baixa visão, uma vez que essa mensagem de status será anunciada por voz assim que ela for emitida, dando maior contexto e conhecimento sobre o status dos acontecimentos durante o uso do sistema.

### Concluindo critérios de sucesso

Como ressaltado antes, esses critérios de sucesso não atingem somente pessoas com deficiência física, os pontos de acessibilidade focam em trazer uma experiência melhor e mais acessível para todos os usuários. Além disso, nem todos os critérios atingem somente o conteúdo em texto, alguns podem atingir também a produção audiovisual. Um exemplo é o seguinte critério de sucesso:
**[1.4.7 Som de fundo baixo ou nenhum som:](https://www.w3.org/TR/WCAG21/#low-or-no-background-audio)** Atinge o nível AAA. Esse critério especifica que o volume do áudio em conteúdos audiovisuais deve ser separado entre o som de fundo e a voz. Esse critério específica que deve se existir pelo menos uma das seguintes:

- Não possuir nenhum som de fundo;
- Caso tenha algum som de fundo, que seja possível desligá-lo;
- Caso tenha som de fundo e não seja possível desligá-lo, ele deve ser pelo menos 20 decibéis mais baixo que o volume do som da voz, em média 4 vezes mais baixo que o som da voz;

E quem esse critério atinge? Principalmente pessoas com deficiências auditivas que possuem dificuldades em separar o que é dito do som de fundo, mas pode atingir diversos outros grupos de pessoas, como pessoas do espectro autista que possuem sensibilidade aos sons, e, por isso, devem também evitar sons que possam ser irritantes, como sons repetitivos ou agudos.

Existem diversos outros critérios, mas, em conclusão, destacamos a mensagem de que vale a pena o estudo e leitura de todos eles. A implementação de alguns critérios pode depender do tipo de conteúdo que seu website possui, mas não se desencoraje para implementar qualquer um deles. Um site que cumpre alguns dos critérios é melhor do que um site que não cumpre nenhum.

