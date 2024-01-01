## README: Página Halloween com Carrossel de Imagens usando elemento `radio`

###  Neste README, você encontrará informações sobre a atividade em aula que resultou na criação da página Halloween. 

-  O principal objetivo desta atividade foi adquirir conhecimento sobre como implementar um carrossel de imagens usando o elemento radio.
-  Para isso, utilizamos pseudo-classes `checked` para controlar a exibição das imagens em um contêiner flexível.
-  Quando um botão de opção de imagem específico (por exemplo, `#imagem1:checked`) é selecionado, a imagem correspondente é exibida deslocando-se horizontalmente por meio da propriedade `margin-left`.

![image](https://github.com/alibiohenrique/curso-desenvolvimento-web-fullstack/assets/118008033/c5dcbfca-ba90-4dcf-9d52-d24ffe0903ec)
![image](https://github.com/alibiohenrique/curso-desenvolvimento-web-fullstack/assets/118008033/146fee3c-6d7a-403e-8d34-a0166557d1ec)


Características do Código:

O código da página Halloween possui as seguintes características-chave:
-  Container de Imagens: Foi definido um contêiner `.imagens` com uma largura de 600% para acomodar várias imagens.
-  Imagens Equitativas: Cada imagem dentro do contêiner tem uma largura de 1/6 para ocupar igualmente o espaço disponível no container flexível.
-  Botões de Opção: Os botões de opção (por exemplo, `#imagem2:checked`) são usados para controlar qual imagem é exibida, definindo a margem esquerda da classe `.img1`.

Certificar de que o HTML também esteja estruturado adequadamente para funcionar com essas regras CSS. Isso geralmente envolve o uso de elementos `<input type="radio">` para os botões de opção e elementos `<label>` correspondentes para ativá-los.


<br>

<details> 
  <summary> Conhecimentos desenvolvidos nesta atividade </summary>

-   `<input type="radio">` é um elemento HTML para seleção única, agrupado com outros usando o atributo "name". O "id" é um identificador exclusivo.
-   `checked`  indica que um elemento de entrada, como uma caixa de seleção ou botão de rádio, está marcado ou selecionado por padrão.
-   `transform: translate(-50%);` é uma propriedade que desloca um elemento horizontalmente, movendo-o 50% do seu próprio tamanho para a esquerda.
-   `* {}` seletor universal, colocar um padrão para todos os navegadores
-   `@font-face` Define uma fonte personalizada usando um arquivo de fonte externa chamado. Isso permite o uso dessa fonte em elementos do texto. Certificar de fornecer o caminho correto para o arquivo de fonte.
-   `border-style: groove;` cria uma borda 3D com sombras internas, proporcionando uma aparência esculpida em elementos HTML.
-   `cursor: pointer;` define o cursor do mouse como uma mão quando ele passa sobre o elemento, indicando que o elemento é interativo e pode ser clicado.
-   `transition: .99s;` especifica uma transição suave de 0,99 segundos para as mudanças de estilo, proporcionando uma animação suave quando o elemento sofre alterações.

</details>

