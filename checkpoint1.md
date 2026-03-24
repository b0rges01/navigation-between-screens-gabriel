Feat: Passagem de parametros oobrigatórios sobre a tela de PerfilScreen

Nesse primeiro commit, realizo a implementação de alguns parâmetros e permito que ocorra a comunicação entre telas do nosso aplicativo que estamos desenvolvendo,
nessa comunicação fiz com que fosse exibido nomes de maneira mockada, 
Para validar e demonstrar o funcionamento, foi utilizado um valor mockado ("Basilio"). 
Ao acionar a navegação, esse nome é enviado como argumento, recuperado na tela de destino e exibido na interface, o que acaba por evidenciar o correto fluxo de dados entre as telas.

Feat: Implementação dos parâmetros opcionais sobre a tela de PedidosScreen

No segundo commit, fiz a implementação de parâmetros opcionais que foi criada com o objetivo da rota aceitar o parâmetro de "cliente", o que gera uma maior flexiblidade na navegação das telas
Por padrão deixei o nome 'Basilio" para ser exibido, também foram feitas mudanças na PedidosScreen para que ela recebesse esse dado de uma maneira mais dinâmica.

Feat: Inserção de valor sobre o parametro opcional sobre a tela de pedidos

No terceiro commit, foi inserido um valor sobre o parâmetro opcional que criamos anteriormente, 
agora o cliente passa a receber um valor, portanto agora validamos a passagem de dados, realizei essas alterações sobre a tela de MenuScreen

Feat: Implementação de mais parâmetros

No quarto commit, coloquei mais parâmetros além dos anteriormente adicionados, 
a nossa rota agora teve uma adaptação para receber novos argumentos, 
"nome" e "idade",  foram feitas mudanças na estrutura do código Main, PerfilScreen e MenuScreen, 
foi feito um Mock novamente para assegurar um correto funcionamento do código, coloquei o nome "Basilio" e a idade "80",
para a tipagem foi utilizado o NavType


