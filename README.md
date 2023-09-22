
# Boas vindas ao repositório do projeto Página de Login do Facebook!

Você já usa o GitHub diariamente para desenvolver os exercícios, certo? Agora, para desenvolver os projetos, você deverá seguir as instruções a seguir. Atenção a cada passo, e se tiver qualquer dúvida, nos envie por _Slack_! #vqv 🚀

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto à partir desse repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.

---

## Sumário


  - [1. Crie uma barra azul na parte superior da página](#1-crie-uma-barra-azul-na-parte-superior-da-página)
  - [2. Posicione o logotipo do Facebook no canto esquerdo na barra superior](#2-posicione-o-logotipo-do-facebook-no-canto-esquerdo-na-barra-superior)
  - [3. Adicione um formulário de autenticação no canto direito da barra superior](#3-adicione-um-formulário-de-autenticação-no-canto-direito-da-barra-superior)
  - [4. Crie uma classe no CSS](#4-crie-uma-classe-no-CSS)
  - [5. Adicione um subcontainer para agrupar o rótulo e campo "E-mail ou telefone" dentro do formulário criado na etapa 3](#5-adicione-um-subcontainer-para-agrupar-o-rótulo-e-campo-"E-mail-ou-telefone"-dentro-do-formulário-criado-na-etapa-3)
  - [6. Adicione um subcontainer para agrupar o rótulo e campo "Senha" dentro do formulário criado na etapa 3](#6-adicione-um-subcontainer-para-agrupar-o-rótulo-e-campo-"Senha"-dentro-do-formulário-criado-na-etapa-3)
  - [7. Adicione um subcontainer com o botão "Entrar" dentro do formulário criado na etapa 3](#7-adicione-um-subcontainer-com-o-botão-"Entrar"-dentro-do-formulário-criado-na-etapa-3)
  - [8. Crie um container com a classe main-content abaixo da barra azul para agrupar o conteúdo principal da página](#8-crie-um-container-com-a-classe-main-content-abaixo-da-barra-azul-para-agrupar-o-conteúdo-principal-da-página)
  - [9. Crie um subcontainer para colocar o conteúdo do lado esquerdo](#9-crie-um-subcontainer-para-colocar-o-conteúdo-do-lado-esquerdo)
  - [10. Crie um subcontainer para colocar o conteúdo do lado direito](#10-crie-um-subcontainer-para-colocar-o-conteúdo-do-lado-direito)
  - [11. Crie um campo de entrada de texto para o nome do usuário dentro do formulário criado no requisito 10](#11-crie-um-campo-de-entrada-de-texto-para-o-nome-do-usuário-dentro-do-formulário-criado-no-requisito-10)
  - [12. Crie um campo de entrada de texto para o sobrenome do usuário dentro do formulário criado no requisito 10](#12-crie-um-campo-de-entrada-de-texto-para-o-sobrenome-do-usuário-dentro-do-formulário-criado-no-requisito-10)
  - [13. Crie um campo de entrada de texto para o celular ou email do usuário dentro do formulário criado no requisito 10](#13-crie-um-campo-de-entrada-de-texto-para-o-celular-ou-email-do-usuário-dentro-do-formulário-criado-no-requisito-10)
  - [14. Crie um campo de entrada para senha do usuário dentro do formulário criado no requisito 10](#14-crie-um-campo-de-entrada-para-senha-do-usuário-dentro-do-formulário-criado-no-requisito-10)
  - [15. Crie um campo de entrada para data de nascimento do usuário dentro do formulário criado no requisito 10](#15-crie-um-campo-de-entrada-para-data-de-nascimento-do-usuário-dentro-do-formulário-criado-no-requisito-10)
  - [16. Crie um campo de entrada para gênero do usuário dentro do formulário criado no requisito 10](#16-crie-um-campo-de-entrada-para-gênero-do-usuário-dentro-do-formulário-criado-no-requisito-10)
  - [17. Crie um botão para finalizar o cadastro dentro do formulário criado no requisito 10](#17-crie-um-botão-para-finalizar-o-cadastro-dentro-do-formulário-criado-no-requisito-10)
  - [18. Validar se todos os campos foram preenchidos ao clicar no botão Cadastre-se](#18-validar-se-todos-os-campos-foram-preenchidos-ao-clicar-no-botão-cadastre-se)
  - [19. Adicione um novo campo de texto no formulário se a pessoa usuária selecionar a opção `Personalizado` no campo Gênero](#19-adicione-um-novo-campo-de-texto-no-formulário-se-a-pessoa-usuária-selecionar-a-opção-personalizado-no-campo-gênero)
  - [20. Substitua o conteúdo do container com a classe right-content se o formulário estiver completamente preenchido e validado](#20-substitua-o-conteúdo-do-container-com-a-classe-right-content-se-o-formulário-estiver-completamente-preenchido-e-validado)
 

## Habilidades

Neste projeto, verificaremos se você é capaz de:

  * Criar formulários em HTML;

  * Utilizar CSS Flexbox para criar layouts flexíveis;

  * Criar regras CSS específicas para serem aplicadas a dispositivos móveis;

  * Construir páginas que alteram o seu layout de acordo com a orientação da tela;

--

### Desenvolvimento

⚠️ É importante que seus arquivos tenham exatamente estes nomes! ⚠️

O seu Pull Request deverá conter os arquivos `index.html`, `style.css` e `script.js`, que conterão seu código HTML, CSS e JavaScript, respectivamente.

Você pode adicionar outros arquivos se julgar necessário. Qualquer dúvida, procure o time de instrução.


## Como desenvolver

Todos os requisitos tem como base a página do **Facebook**. Use a imagem do site, além de acessar [este link com a página antiga de cadastro/login](https://web.archive.org/web/20200101163229if_/https://pt-br.facebook.com/). Tente ser o mais fiel possível.

Use a inspeção de código para verificar a estrutura da página de cadastro/login do **Facebook**.

![Página Facebook](./facebook.png)





### 1. Crie uma barra azul na parte superior da página

  Pontos importantes:
  * A barra deve ter a classe top-bar
  * A classe top-bar deve determinar que o elemento é um flex container
  * A classe top-bar deve possuir a propriedade `background-color: rgb(66, 103, 178)`


### 2. Posicione o logotipo do Facebook no canto esquerdo na barra superior

  Pontos importantes:
  * Deve existir um elemento img com a classe facebook-logo
  * O logotipo deve estar alinhado a esquerda dentro da barra azul
  * O atributo src do logotipo deve apontar para imgs/facebook-logo.png


### 3. Adicione um formulário de autenticação no canto direito da barra superior

  Pontos importantes:
  * O formulário deve estar alinhado a direita dentro da barra azul
  * Existe formulário com uma classe chamada facebook-login
  * O formulário deve ser um flex container


### 4. Crie uma classe no CSS

  Pontos importantes:
  * Essa classe deve se chamar form-group
  * Essa classe deve possuir a propriedade `diplay: flex`
  * Alinhe o eixo principal dessa classe para ser o eixo vertical


### 5. Adicione um subcontainer para agrupar o rótulo e campo "E-mail ou telefone" dentro do formulário criado na etapa 3

  Pontos importantes:
  * Este subcontainer deve ter a classe `form-group`
  * Dentro do subcontainer `form-group` criado, deve haver um rótulo com o id user-email-phone-label e o texto "Email ou telefone"
  * Dentro do subcontainer `form-group` criado, abaixo do rótulo deve haver campo de entrada de texto para receber o email ou o telefone do usuário com o id user-email-phone'

### 6. Adicione um subcontainer para agrupar o rótulo e campo "Senha" dentro do formulário criado na etapa 3

  Pontos importantes:
  * Deve haver um novo subcontainer utilizando a classe `form-group`
  * Dentro do novo subcontainer `form-group` criado, deve haver um rótulo com o id user-password-label e o texto "Senha"
  * Dentro do novo subcontainer `form-group` criado, abaixo do rótulo deve haver campo de entrada para senha com o id user-password

### 7. Adicione um subcontainer com o botão "Entrar" dentro do formulário criado na etapa 3

  Pontos importantes:
  * Deve haver um novo subcontainer utilizando a classe `form-control`
  * Crie uma classe no CSS form-control com a propriedade `align-self: flex-end`
  * Dentro do novo subcontainer `form-control` criado, deve haver um botão com o id "button-login" e o texto "Entrar"
  * O botão deve estar alinhado a direita do campo de entrada para senha
  * Ao clicar no botão com o id #button-login deve exibir um alert com o valor do campo "Email ou telefone"

### 8. Crie um container abaixo da barra azul para agrupar o conteúdo principal da página

  Pontos importantes:
  * Crie um elemento com a classe main-content
  * O elemento deve ser um flex container no eixo horizontal
  * O elemento deve posicionado abaixo da barra azul


### 9. Crie um subcontainer para colocar o conteúdo do lado esquerdo

  Pontos importantes:
  * Crie o subcontainer dentro do container com a classe main-content
  * O subcontainer deve ter a classe left-content
  * A classe left-content deve ter uma largura de 800px
  * Dentro do container com a classe left-content deve existir um parágrafo com id facebook-slogan e o texto "O Facebook ajuda você a se conectar e compartilhar com as pessoas que fazem parte da sua vida."
  * Dentro do container com a classe left-content deve existir abaixo do parágrafo com id facebook-slogan uma imagem com id facebook-networking e o src com o endereço `imgs/networking.png`.


### 10. Crie um subcontainer para colocar o conteúdo do lado direito

  Pontos importantes:
  * Crie o subcontainer dentro do container com a classe main-content
  * O novo subcontainer deve ter a classe right-content
  * A classe right-content deve ter uma largura de 300px
  * Utilize na classe main-content a propriedade justify-content com o valor mais apropriado para alinhar os conteúdos
  * Dentro do subcontainer com a classe right-content deve existir um elemento h1 com o texto "Abra uma conta"
  * Dentro do subcontainer com a classe right-content deve existir um elemento com a classe quick-easy com o texto "É rápido e fácil." posicionado abaixo do texto "Abra uma conta"
  * Dentro do subcontainer com a classe right-content deve existir um elemento form abaixo do texto "É rápido e fácil."
  * O elemento com a classe right-content deve estar a direita do elemento com a classe left-content


### 11. Crie um campo de entrada de texto para o nome do usuário dentro do formulário criado no requisito 10

  Pontos importantes:
  * O campo deve ter o atributo name com o valor "firstname"
  * O campo deve ter um placeholder com o valor "Nome"


### 12. Crie um campo de entrada de texto para o sobrenome do usuário dentro do formulário criado no requisito 10
  Pontos importantes:
  * O campo deve ter o atributo name com o valor "lastname"
  * O campo deve ter um placeholder com o valor "Sobrenome"
  * Esse campo deve estar alinhado a direita do campo de Nome


### 13. Crie um campo de entrada de texto para o celular ou email do usuário dentro do formulário criado no requisito 10

  Pontos importantes:
  * O campo deve ter o atributo name com o valor "phone_email"
  * O campo deve ter um placeholder com o valor "Celular ou email"
  * Posicione esse campo abaixo do campo do nome do usuário


### 14. Crie um campo de entrada para senha do usuário dentro do formulário criado no requisito 10

  Pontos importantes:
  * O campo deve ter o atributo name com o valor "password"
  * O campo deve ser do tipo "password"
  * O campo deve ter um placeholder com o valor "Nova senha"
  * Posicione esse campo abaixo do celular/email


### 15. Crie um campo de entrada para data de nascimento do usuário dentro do formulário criado no requisito 10

  Pontos importantes:
  * Um rótulo abaixo do campo nova senha com o id label-birthdate e o texto "Data de nascimento"
  * O campo deve ter o atributo name com o valor "birthdate"
  * O campo deve ser do tipo "text"
  * O campo deve ter um placeholder com o valor "dd/mm/aaaa"
  * Posicione esse campo abaixo do rótulo


### 16. Crie um campo de entrada para gênero do usuário dentro do formulário criado no requisito 10

  Pontos importantes:
  * Um rótulo abaixo do campo nova senha com o id label-gender e o texto "Gênero"
  * O campo deve ser formado por três `radio buttons` com as opções "Feminino", "Masculino" e "Personalizado"
  * Os `radio buttons` devem ter o atributo name com o valor "gender"
  * Posicione os radio buttons para ficar na mesma linha
  * Posicione os radio buttons para ficar abaixo do label


### 17. Crie um botão para finalizar o cadastro dentro do formulário criado no requisito 10

  Pontos importantes:
  * Um botão com o texto "Cadastre-se" e id "facebook-register"
  * Deve ter a propriedade type igual a submit


### 18. Validar se todos os campos foram preenchidos ao clicar no botão Cadastre-se

  Pontos importantes:
  * Exibir uma mensagem "Campos inválidos" dentro do formulário caso pelo menos um campo não esteja preenchido


### 19. Adicione um novo campo de texto no formulário se a pessoa usuária selecionar a opção `Personalizado` no campo Gênero

  Pontos importantes:
  * O novo campo dever ser uma campo de texto com o atributo name "gender-custom" e um placeholder "Gênero (opcional)"
  * O novo campo deve estar posicionado entre as opções de gênero e o botão "Cadastrar-se"


### 20. Substitua o conteúdo do container com a classe right-content se o formulário estiver completamente preenchido e validado

  Pontos importantes:
  * Exibir o e-mail ou telefone
  * Não exibir a senha
  * Exibir a data de nascimento
  * Caso a opção selecionada no campo Gênero seja Feminino exibir "Feminino"
  * Caso a opção selecionada no campo Gênero seja Masculino exibir "Masculino"
  * Caso a opção selecionada no campo Gênero seja Personalizado exibir "Personalizado":


