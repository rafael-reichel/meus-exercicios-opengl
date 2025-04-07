1.
 
1.1 - Translacao Interativa:
Criei uma funcao specialKeyPressed para capturar as teclas especiais(setas)
Assim, o código agora também reage ao pressionamento das setas do teclado, movendo o objeto para as direções correspondentes.

1.2 - Escala Simples:
Mudanças:
glTranslatef(scale_origin_x, scale_origin_y, 0.0f);: Esta linha move o sistema de coordenadas para o ponto onde você quer que a escala aconteça. Nesse caso, usamos (scale_origin_x, scale_origin_y) como ponto de origem para a escala.

glScalef(scale_factor, scale_factor, 1.0f);: A escala é aplicada com base no novo ponto de origem, ou seja, o ponto de origem da escala será o ponto (scale_origin_x, scale_origin_y).

glTranslatef(-scale_origin_x, -scale_origin_y, 0.0f);: Após aplicar a escala, o sistema de coordenadas é movido de volta para a origem do espaço de coordenadas original.

1.3 - Rotacao Ponto:
Alterei o deslocamento do quadrado para o centro de tela, que antes estava 5 unidades direita

Para compilar o codigo basta baixar o arquivo meus-exercicios-opengl.workspace e abrir com o Codeblocks!
