## Componente Lista de Frutas

Este componente React Native é responsável por:

* **Buscar dados de frutas:** Realiza uma requisição HTTP para a API da Fruityvice para obter informações sobre diferentes tipos de frutas.
* **Gerenciar o estado:** Utiliza o hook `useState` para manter um array de objetos que representam as frutas, atualizando-o após a requisição à API.
* **Renderizar a lista:** Emprega o componente `FlatList` para exibir a lista de frutas de forma eficiente.
* **Demonstrar diferentes abordagens para assincronismo:** Inclui botões para simular o uso de callbacks, promises e async/await ao lidar com operações assíncronas.

### Tecnologias Utilizadas
* **React Native:** Framework para desenvolvimento de aplicativos mobile.
* **JavaScript:** Linguagem de programação utilizada.

### Como funciona
1. **Requisição à API:** Ao carregar o componente, uma requisição é feita para a API da Fruityvice para obter os dados das frutas.
2. **Atualização do estado:** Os dados recebidos da API são utilizados para atualizar o estado local, que contém a lista de frutas.
3. **Renderização da lista:** O componente `FlatList` renderiza a lista de frutas com base no estado atual.
4. **Botões de ação:** Os botões permitem simular diferentes formas de lidar com operações assíncronas, como callbacks, promises e async/await.

### Estrutura do Código
* **`useState`:** Utilizado para gerenciar o estado da lista de frutas.
* **`fetch`:** Empregado para realizar a requisição HTTP para a API.
* **`FlatList`:** Utilizado para renderizar a lista de frutas de forma eficiente.

### Próximos passos
* **Estilização:** Implementar estilos personalizados para a lista e os itens.
* **Funcionalidades adicionais:** Adicionar funcionalidades como busca, filtragem e ordenação.
* **Gerenciamento de erros:** Implementar um mecanismo para lidar com erros durante a requisição à API.

