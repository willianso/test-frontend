# Desafio | Frontend

Este é um **CRUD** apenas no **lado do cliente**, ou seja, irá manter as informações armazenadas no **localStorage** do navegador.

As regras dos campos sendo utilizados são as seguintes:
* Nome: obrigatório para preenchimento
* E-mail: obrigatório para preenchimento
* Telefone: não obrigatório
* Data de nascimento: não obrigatório
* Cidade onde nasceu: não obrigatório

3 bugs foram inseridos no código. Um no HTML, um no CSS (vide o arquivo layout.jpg para referência) e um no JS (localizado na classe MyCrud).
Além disso, você deve implementar o método de remoção (localizado na classe MyCrud).

Serão avaliadas suas capacidades de leitura de código e resolução de problemas. Não se preocupe caso não consiga terminar tudo, nos envie o teste mesmo assim, destacando, logo abaixo, suas principais dificuldades e como fez para resolver os problemas.

# Resposta do participante
_Responda aqui quais foram suas dificuldades e como fez para encontrar e resolver os problemas ao enviar a solução_

- O bug no update do crud.js foi um pouco complicado por conta da complexidade envolvendo as classes e minha inexperiência, mas fui debugando com console.log até chegar no loop da variavel map, a qual após ver os seus valores, ficou claro o que precisava ser feito.

- no método delete, não sabia de cabeça o método para excluir um valor do array por meio da posição, então tive que pesquisar. Para salvar no localStorage, usei como base o funcionamento do método update.