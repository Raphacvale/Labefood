#  Projeto Labefood



## 

Objetivo do projeto:

O projeto é baseado em aplicativos de comida (iFood, UberEats e Rappi) e é do tipo mobile first. É uma case do módulo frontend do bootcamp de desenvolvimen web da Labenu, o intuito principal é aplicar todo o conhecimento adquirido em um projeto complexo e completo, totalmente funcional.



### Funcionalidades:

- Login: realiza o login do usuário e armazena as informações de autenticação do usuário no local storage
- Cadastro: efetua o cadastro de um novo usuário e redireciona para tela de cadastro de endereço
- Cadastro de endereço: realiza o cadastro do usuário e redireciona para a tela de Home
- Home: renderiza todos os restaurantes, possui um filtro por categoria e redireciona para página de busca ao clicar no input de busca
- Busca: realiza a busca de restaurantes pelo nome
- Home e Busca: ao clicar nos cards dessas tela o usuário é redirecionado para a página do restaurante selecionado
- Restaurantes: renderiza as informações do restaurante e seus produto, ao clicar em adicionar ele abre um popup para informar a quantidade e ao confirmar o item é adicionado ao carrinho, também é possível remover esse item, não é possível adicionar itens de restaurantes distintos
- Carrinho: o usuário pode remover itens, efetuar a compra, se existir uma compra em andamento só é possível realizar outra quando está for concluída
- As únicas páginas públicas são Login e Cadastro, as outra só podem ser acessadas por usuários logados

### 📚 Bibliotecas utilizadas:

- styled-components
- axios
- react-router-dom
- material ui


### 🔗 Link Surge:

https://quixotic-measure.surge.sh/login


