# Projeto com Efeito Parallax

Este projeto implementa o efeito 
*parallax* em uma página simples, onde o fundo de cada seção se move a uma velocidade diferente do conteúdo. Isso cria uma sensação de profundidade enquanto o usuário rola pela página.

![parallax](https://github.com/user-attachments/assets/eb2bcf6e-ca1a-405e-b7b9-f0064fd1deb0)

![paralla2](https://github.com/user-attachments/assets/3c4ec238-a6ff-4fc5-b76b-1af851673377)


## Descrição do Projeto

A página é composta por três seções, cada uma com uma imagem de fundo e um conteúdo que se sobrepõe a essa imagem. O efeito parallax é aplicado ao fundo, criando uma experiência visual dinâmica. As imagens de fundo se movem enquanto o conteúdo permanece fixo, fazendo com que o fundo e o conteúdo se desloquem de forma independente durante a rolagem.

### Estrutura do HTML

O projeto possui as seguintes seções dentro da tag 
`<main>`:

1. **section-one**: Apresenta um título centralizado com o texto "Parallax".
2. **section-two**: Contém um parágrafo com texto de exemplo (Lorem Ipsum).
3. **section-three**: Uma seção adicional com uma imagem de fundo que dá continuidade ao efeito parallax.

### Efeito Parallax

O efeito parallax é obtido usando a propriedade CSS 

O efeito parallax é obtido usando a propriedade CSS `background-attachme

O efeito parallax é obtido usando a propriedade CSS

`background-attachment: fixed`, que mantém a imagem de fundo fixa enquanto o conteúdo se move. Isso cria o efeito visual desejado, onde o fundo parece se mover a uma velocidade diferente do conteúdo.

#### Propriedades CSS Usadas

- **Estilos globais**: O código CSS começa com regras para zerar margens, bordas e padding, além de definir o `box-sizing` como `border-box` para facilitar o dimensionamento de elementos.
- **Responsividade**: Utiliza unidades relativas como `dvh` para ajustar as seções de acordo com a altura da janela de visualização, tornando o design mais flexível.
- **Fundo fixo**: A propriedade `background-attachment: fixed` aplica o parallax, fazendo com que o fundo se mova a uma velocidade diferente do conteúdo.
- **Gradientes**: Cada seção possui um gradiente com transparência no topo e um tom escuro na parte inferior, garantindo que o texto fique visível sobre a imagem de fundo.
- **Sombra no texto**: Para aumentar a legibilidade, o texto contém sombras usando a propriedade `drop-shadow`.

## Funcionamento do Parallax

O efeito é implementado com três propriedades principais:

- **`background-attachment: fixed`**: Garante que o fundo se mova de forma independente do conteúdo enquanto o usuário rola a página.
- **`background-position: center top`**: Centraliza a imagem no topo da seção, ajustando-se adequadamente ao contêiner.
- **`background-size: cover`**: A imagem de fundo é redimensionada para cobrir toda a área da seção, mantendo suas proporções.

## Tecnologias Usadas

- **HTML5**: Utilizado para estruturar o conteúdo da página.
- **CSS3**: Estilização, incluindo o efeito parallax.
- **Responsividade**: O design foi desenvolvido para ser responsivo, adaptando-se a diferentes tamanhos de tela.
