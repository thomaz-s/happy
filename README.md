Este respositório traz o código do back-end do projeto Happy, desenvolvido com a equipe da [Rockeseat](https://github.com/rocketseat-education) durante a Terceira Next level Week.

O objetivo da aplicação é fazer um cadastro de orfanatos para facilitar a busca de informações por quem quer visitá-los.

Basicamente os orfanatos são cadastrados em uma página web, feita com React, e através de um aplicativo para Android ou IOS desenvolvido em React-Native, os usuários podem fazer a consulta para conseguir as informações. Mas nesse respositório só incluí a parte do back-end, feita com Nodejs.

Abaixo algumas capturas de tela das rotas sendo acessadas através do Insomnia:

Cadastro de orfanato:

![Cadastro](https://raw.githubusercontent.com/thomaz-s/happy/master/.github/criar_orfanato.png)

A API possui validação, utilizando a biblioteca [Yup](https://github.com/jquense/yup), no exemplo abaixo é retornado um erro devido ao tamando do campo about:

![Erro de validação](https://raw.githubusercontent.com/thomaz-s/happy/master/.github/about_erro.png)

Listagem de orfanatos (função index):

![Listagem de orfanatos](https://raw.githubusercontent.com/thomaz-s/happy/master/.github/listar_orfanatos.png)

Retornar apenas um orfanato (função show):

![Mostrar orfanato](https://raw.githubusercontent.com/thomaz-s/happy/master/.github/mostrar_orfanato.png)