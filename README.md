# IPM-L2.2

Interface of a restaurant with a table that has touch screen technology
Techonogys used: HTML5, CSS, JavaScript

.: This is how our teacher presented us the problem (too long for me to translate it all correctly, maybe use google translate or even an underpaid and foreign friend :D) :.

O bitoque chega sempre com o molho frio? Quando a Coca-Cola chega já tem a garganta encarquilhada com a sede? O bacalhau à lagareiro veio sem azeite? Não volte a esse restaurante com empregados humanos pouco eficicentes. Use o Com.ISTo, a maior revolução na restauração desde que alguém se lembrou de juntar chouriço ao caldo verde!
O Com.ISTo é uma mesa interactiva na qual pode ver o menu do restaurante (e não só!), encomendar a sua refeição (e a dos amigos), pedir os cafés (um deles cheio e com cheirinho), ou mesmo oferecer uma sobremesa à miúda (ou rapaz!) da mesa do lado que quer deixar bem impressionada(o). O seu ecrã sensível ao toque torna-o fácil de usar, e os vários sensores e câmaras ao seu dispor na mesa podem tornar a sua visita mais agradável.
Não fique seco! Sempre que o vinho estiver a acabar, o Com.ISTo manda vir outra garrafa! Está na hora de pedir a conta? O Com.ISTo parece que adivinhou... Vem mais um amigo e precisa de mais talheres? Está sob controlo!
Objetivo: Desenvolver uma interface utilizador para a mesa que permita aos utilizadores aceder às suas funcionalidades de forma eficiente, eficaz e agradável. 
Requisitos/Restrições: A aplicação deve simular a interacção, que seja relevante, com toda a mesa e não ser "um iPad encaixado na mesa". A aplicação deve assumir a existência de sensores que permitam interacções para lá do simples ecrã táctil. A criatividade na exploração do cenário será um aspeto considerado na avaliação.
Especificações: A mesa é sensível ao toque e capaz de produzir imagem em toda a sua superfície. Para além disso, dispõe de:
colunas (stereo)
acelerómetro (sente se tremer/for deslocada/levar um pontapé ou um murro)
sensores de peso, distribuídos pela sua superfície (é capaz de saber o peso do que está colocado nos diferentes locais)
sensores de temperatura, distribuídos pela sua superfície (é capaz de saber a temperatura do que está colocado nos diferentes locais)
leitor de smartcards/NFC

Sejam criativos, pensem em cenários inovadores. Lembrem-se que quem já bebeu um pouco não consegue acertar em botões pequenos, um restaurante pode ser barulhento, as bebidas entornam-se, o molho do bife salta do prato e há várias pessoas à mesa a fazer pedidos.

Notas: A interface deve ser desenvolvida usando tecnologia HTML5 (HTML+JavaScript+CSS). Deve funcionar de forma local (as in desligo o computador da rede e funciona na mesma), sem necessidade de servidores, etc. (isto é, basta descompriir um zip e abrir um ficheiro). Não precisa de funcionar igualmente em todos os browsers, mas, deverá funcionar pelo menos na última versão do firefox ou do chrome. O código não é o mais importante. É-o, sim, a interacção que possibilita. As interacções físicas (bater na mesa, colocar copos em cima dela, inserir cartões, etc.) devem ser simuladas se forem parte da interacção (mesmo que seja carregando num botão ou clickando numa imagem, se isso não tiver impacto na experiência de utilização).
Não é permitida a utilização de serviços/produtos para criação automática de HTML, especialmente serviços online. A utilização de "mini-sites" já feitos, incluídos por iframes ou semelhante também não é permitida (queremos avaliar a vossa interface, não aquela que copiaram de alguém...)
É permitida a utilização de bibliotecas Javascript, desde que funcionem localmente (Bootstrap, etc. etc.). Neste caso, no entanto, tenham a preocupação de que o look&feel (e a maneira como funcionam) deve ser ajustada para o cenário da superfície sensível ao toque (não pode ser "um site a correr numa mesa")


Problems with our implementation (To be worked upon):

- Users didn't have notifications that their order had been added to the left.

- Users didn't have enough notifications that they had paid for their, or someone else's food.

- Pictures of the plate not good enough
(This is kind of an hidden feature, maybe remove it so it doesn't cause confusion)

- There is no sound

Disclaimer: This is an educational project, the point was to teach us how to make an interface and why do it the way we did it. It is not functional at all, because it was not the point of this project.
