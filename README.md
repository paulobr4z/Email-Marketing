# Email-Marketing

## Desenvolvimento do projeto

A princípio minha ideia era fazer o e-mail do zero, e assim eu fiz, utilizando HTML e CSS, consegui fazer todas as telas, testei no navegador e estava tudo correto, mas quando fui enviar o email me deparei com um problema, o layout ficou com um erro na estrutura, então fui verificar o que tinha acontecido e percebi, cada plataforma de e-mail e gerenciador de email, possui particularidade nos seus critérios de compatibilidade, um determinado arquivo html pode funcionar perfeitamente no Gmail e não funcionar corretamente no outlook, por exemplo.
Percebi isso quando fui testar o e-mail em uma plataforma especializada em e-mail marketing chamada Stripo, como foi sugerido nas instruções do teste.
Pelo que eu entendi lendo as instruções, era sugerido utilizar esse tipo de plataforma para testar o email, para verificar a eficácia da solução que estava sendo desenvolvido.
Então como eu não teria mais tempo para modificar o meu código, e para não deixar de entregar algo funcionando corretamente,  eu criei um e-mail utilizando o editor da plataforma.
Sendo bem franco acredito que seria mais viável criar os email utilizando a plataforma Stripo, do que fazer tudo do zero, pois o programador teria um trabalho bem complexo para criar uma solução que se adaptasse a todas as diferenças de compatibilidade de cada serviço de e-mail.
Se eu tiver entendido mal as instruções e no teste poderia utilizar uma plataforma de e-mail marketing para criar o mesmo, a solução está pronta e rodando perfeitamente.
 
## Organização dos arquivos

Na pasta assets estão as imagens;
Os arquivos html estão nomeados em ordem numérica, assim como seus respectivos arquivos de estilo.
Na pasta email-mkt está a solução que eu desenvolvi utilizando a plataforma Stripo.
 
## O que poderia ter melhorado?

Pelo que pude observar lendo o código fonte do email criado na Stripo, eu teria baseado o meu código HTML em tabelas e não em div como eu fiz, acredito que os serviços de e-mail tem mais compatibilidade com layouts baseados em tabelas. E no CSS, percebi que modelos de layout mais atuais como flexbox, não tem boa aceitação, no caso eu teria utilizado float, position relative, etc.
