## README: Galeria de Imagens - Guia Chile

Neste README, você encontrará informações sobre o meu aprendizado da página "Guia Chile," que apresenta um guia turístico com informações sobre diferentes destinos no Chile. Abaixo estão os principais atributos e características do código.


<img src ="https://github.com/alibiohenrique/curso-desenvolvimento-web-fullstack/assets/118008033/b728f009-9bae-4a26-885e-56c37328d298" alt = "page">
<img src= "https://github.com/alibiohenrique/curso-desenvolvimento-web-fullstack/assets/118008033/1e025670-1504-47a0-9e68-7f5dfbb92810" alt = "page+01">



### Principais Atributos do Código HTML:

-   Metadados e Título: O código HTML define a linguagem (lang) como "pt-br" e inclui metadados como a ligação para o arquivo de estilo AOS e o título da página "Guia Chile."

-   Estrutura do Documento: O HTML é estruturado com cabeçalho (<head>) e corpo (<body>) do documento, seguindo as práticas comuns.

-   Uso de AOS: O código inclui a biblioteca AOS (Animate on Scroll) para adicionar efeitos de animação a elementos da página.

-   Inclusão de Estilos: O código vincula um arquivo de estilo externo chamado "style.css" para a formatação da página.

-   Tags de Imagem: Diversas tags <img> são usadas para exibir imagens nos diferentes destinos turísticos apresentados.

### Durante o desenvolvimento deste código, alguns conhecimentos e técnicas específicas foram aplicados:

<br>

<details> 
  <summary> Conhecimentos desenvolvidos nesta atividade </summary>

<br>

    Estilo CSS Global: 
    -  O código CSS global define estilos para elementos de nível superior, como o corpo da página e os estilos de fundo.

    Efeito de Gradiente: 
    -  É aplicado um efeito de gradiente de cores de fundo à página usando a propriedade `background-image` no elemento `<body>`.
    
    Uso de Flexbox: 
    -  O layout dos cartões de informações é criado usando o modelo de layout flexbox, que permite organizar elementos em linhas e colunas de forma flexível.

    Efeitos de Transição: 
    -  Transições de imagem suaves são implementadas usando a propriedade `transition` para criar uma experiência de usuário mais agradável.

    Filtros de Imagem: 
    -  Efeitos de filtro de imagem, como o desfoque, são aplicados às imagens na galeria para criar uma interação visual interessante.

<br>

-  `Metadados` são informações descritivas que fornecem contexto e organização aos dados, documentos ou recursos. Eles incluem detalhes como título, autor, data, palavras-chave, formato e são usados para identificação, pesquisa e compreensão de conteúdo, tornando-o mais acessível e útil.
-   `display: inline-block;` é uma propriedade CSS que permite que um elemento seja exibido como um bloco, mas mantenha características de elementos em linha, como a capacidade de estar ao lado de outros elementos em linha no mesmo nível. Isso é útil para criar layouts em que você deseja que os elementos se comportem como blocos, mas também desejam que eles fiquem em linha uns com os outros.-   `checked`  indica que um elemento de entrada, como uma caixa de seleção ou botão de rádio, está marcado ou selecionado por padrão.
- `data-aos="zoom-out"`: Isso define o tipo de animação que será aplicado quando o elemento entrar na visualização do usuário. Neste caso, a animação "zoom-out" será aplicada, o que provavelmente fará o elemento parecer menor ou recuar.
- `data-aos-easing="linear"`: Define o tipo de função de animação. "Linear" significa que a animação ocorrerá com velocidade uniforme ao longo do tempo.
- `data-aos-duration="1500"`: Define a duração da animação em milissegundos. Neste caso, a animação terá uma duração de 1500 milissegundos (ou 1,5 segundos).
-  `transition` é usada para criar uma transição suave entre os estados de um elemento quando alguma alteração ocorre. 
-  `transition: all 1.3s cubic-bezier;` está definindo uma transição para todos os atributos do elemento, com as seguintes configurações:
- `1.3s` define a duração da transição, que é de 1,3 segundos. Isso significa que as mudanças de estilo ocorrerão gradualmente ao longo de 1,3 segundos.
- `cubic-bezier` é uma função de temporização personalizada que pode ser especificada para controlar a aceleração da transição. No entanto, falta a definição dos valores específicos do cubo de Bezier, que normalmente seriam fornecidos, como `cubic-bezier(0.25, 0.1, 0.25, 1)`, por exemplo.
-   `<span></span>` é uma tag HTML usada para aplicar estilos ou scripts a um pequeno trecho de texto ou conteúdo.
-   Essa linha HTML `<link rel="stylesheet" href="style.css">` importa um arquivo de estilo chamado "style.css" para ser aplicado à página da web.
-   `<!DOCTYPE html>` é uma declaração no início de um documento HTML que define o tipo de documento e a versão do HTML que está sendo utilizado. Neste caso, é para HTML5.
-   `.galeria div:hover { flex: 4; }` quando você passa o mouse sobre um elemento "div" dentro de um elemento da classe ".galeria", o elemento em foco aumenta sua largura flexível para 4 vezes o tamanho original.
-  `.galeria:hover div:not(:hover) { filter: blur(5px) }` quando você passa o mouse sobre um elemento da classe ".galeria", todos os elementos "div" que não estão em foco ficam desfocados.

</details>

