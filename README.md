# Desenhando no Canvas

Este projeto é uma aplicação web simples que permite desenhar em um elemento `<canvas>` utilizando diferentes cores. A aplicação foi desenvolvida utilizando HTML, CSS e JavaScript.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- `index.html`: Contém a estrutura HTML da aplicação.
- `style.css`: Contém os estilos CSS para a aplicação.
- `script.js`: Contém a lógica JavaScript para a funcionalidade de desenho.

## Funcionalidades

- Desenhar no canvas com diferentes cores.
- Selecionar a cor desejada clicando em um dos botões de cor.
- Limpar o canvas clicando no botão "Limpar Quadro".

## Como Utilizar

1. Clone o repositório para o seu ambiente local.
2. Abra o arquivo `index.html` em um navegador web.
3. Utilize o mouse para desenhar no canvas.
4. Clique em uma das cores disponíveis para mudar a cor do desenho.
5. Clique no botão "Limpar Quadro" para limpar o canvas.

## Estrutura do Código

### HTML (`index.html`)

O arquivo HTML define a estrutura da página, incluindo o elemento `<canvas>`, a área de seleção de cores e o botão de limpar.

### CSS (`style.css`)

O arquivo CSS define os estilos para a página, incluindo o layout, cores e estilos dos elementos.

### JavaScript (`script.js`)

O arquivo JavaScript contém a lógica para desenhar no canvas, selecionar cores e limpar o canvas. Aqui estão as principais funções:

- `colorClickEvent(e)`: Muda a cor atual de desenho com base na cor selecionada.
- `mouseDownEvent(e)`: Inicia o desenho quando o botão do mouse é pressionado.
- `mouseMoveEvent(e)`: Desenha no canvas enquanto o mouse é movido.
- `mouseUpEvent()`: Para o desenho quando o botão do mouse é solto.
- `draw(x, y)`: Desenha uma linha no canvas.
- `clearScreen()`: Limpa o canvas.

## Autor

Criado por Bruno Sousa.
