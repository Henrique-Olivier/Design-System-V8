# -Design-System-V8
**Componente Input Personalizável**
Este componente de input permite uma estilização flexível e aceita as seguintes propriedades:

Propriedades Obrigatórias:
- inputSize: Especifica o tamanho do input, podendo ser 'default' ou 'small'.

Propriedades Opcionais:

- textLabel: Um rótulo que pode ser adicionado acima do input para descrever seu propósito.
- textError: Uma mensagem de erro que aparece abaixo do input, útil para validações.
- disabled: Um booleano que determina se o input deve estar desabilitado.
- icon: Um ícone que pode ser exibido dentro do campo de input, oferecendo uma indicação visual.
OBS: O caminho de um SVG deve ser passado. Certifique-se de que o ícone seja um SVG, pois é o formato suportado para garantir melhor renderização e flexibilidade visual.

**componente  Button**
O componente Button é um botão versátil com diversas variações de estilo, incluindo: main, secondary, text, e link.

Para utilizá-lo, basta chamar a tag \<Button> com o fechamento apropriado \<Button/>. Ele espera as seguintes props:

Props:
- children (obrigatório):

O conteúdo do botão, geralmente o texto que será exibido dentro dele.


- type (obrigatório):

Define a aparência e o estilo do botão.
Aceita os seguintes valores:
1. 'main': Para botões primários com destaque visual.
2. 'secondary': Para botões secundários.
3. 'text': Para botões com estilo de texto simples, sem bordas.
4. 'link': Para botões que parecem links de texto.


- size (obrigatório):

Controla o tamanho do botão.
Aceita os seguintes valores:
1. 'large': Botão grande.
2. 'medium': Botão médio (padrão).
3. 'small': Botão pequeno.


- icon (opcional):

Caso o botão precise de um ícone, o caminho de um SVG deve ser passado. Certifique-se de que o ícone seja um SVG, pois é o formato suportado para garantir melhor renderização e flexibilidade visual.

**Componente Typography**
O componente Typography é um componente que possui estilização para: tags heading(H1, H2, H3, H4) para desktop, tablet e mobile; e a tag paragraph(p) para main text.

Para utilizá-lo, basta chamar a tag \<Typography> com o fechamento apropriado \<Typography/>. Ele espera as seguintes props:

- size (obrigatório):

Aceita os seguintes valores:
1. 'desktop', Usado com heading.
2. 'tablet', Usado com heading.
3. 'mobile', Usado com heading.
4. 'main', Usado com paragraph.

- tag (obrigatório):
Aceita os seguintes valores:
1. 'H1', Usado com o size desktop, tablet ou mobile.
2. 'H2', Usado com o size desktop, tablet ou mobile.
3. 'H3', Usado com o size desktop, tablet ou mobile.
4. 'H4', Usado com o size desktop, tablet ou mobile.

5. 'body-L', usado com o size main.
6. 'body-M-reguar', usado com o size main.
7. 'body-M', usado com o size main.
8. 'body-S', usado com o size main.
9. 'body-S-regular', usado com o size main.
10. 'body-XS', usado com o size main.

- children (obrigatório):

O conteúdo do typography, sendo o texto que será exibido dentro dele.