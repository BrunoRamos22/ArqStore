Aluno: Bruno Ramos Email: brunormsodre@gmail.com

Simple Store
Este é um projeto desenvolvido como parte do curso de Ruby on Rails. O objetivo é aplicar os conceitos aprendidos em aula para criar uma aplicação web funcional, bem estruturada e com boas práticas de desenvolvimento.

📦 Tecnologias Utilizadas
Ruby 3.3.x
Ruby on Rails 8.x
SQLite
Propshaft
Puma
Importmap-rails
Turbo-rails

🚀 Como rodar o projeto localmente
# Clone o repositório
git clone https://github.com/BrunoRamos22/ArqStore.git
cd Store

# abra o VSCode
# Inicie o projeto dentro do dev container
✅ Funcionalidades implementadas

Cadastro e login de usuários com autenticação
CRUD de Itens
Inclusão de fotos e texto personalizado para cada item
Sistema de Logout
Controle de estoque
Sistema de inscrição para aviso quando o produto voltar a estar disponível

🧠 Conceitos aplicados
Abaixo estão os conceitos aprendidos em aula e aplicados neste projeto, junto com a justificativa de sua utilização:

1. Cache
   Armazena temporariamente informações (como resultados de consultas ao banco de dados ou páginas web geradas) para que, da próxima vez que forem solicitadas, o Rails possa servi-las diretamente do cache, em vez de ter que gerá-las novamente. Isso reduz o tempo de carregamento e melhora a experiência do usuário. Foi utilizado em alguns prompts HTML para otimização das páginas estáticas.

2. Concern
  Em Ruby on Rails, um Concern é um módulo que você pode incluir em várias classes (geralmente Models, Controllers ou até mesmo Views) para reutilizar funcionalidades. Foi utilizado principalmente nas funções "show" e "edit" que são muito parecidas, com isso seguindo o DRY.

3.  Rubocop
  O RuboCop em Ruby on Rails é como um "policial de código" que ajuda a manter seu código limpo e consistente. Ele verifica seu código Ruby em busca de problemas de estilo e de possíveis erros, seguindo as diretrizes de estilo da comunidade Ruby (principalmente o estilo do guia do Ruby). Foi utilizado para verificar se o código estava "limpo" e garantir que não haveriam inconsistências.

4. Routes
   As rotas (routes) em Ruby on Rails são como o mapa de estradas do seu aplicativo. Elas definem como as solicitações do usuário (como quando alguém clica em um link ou envia um formulário) são direcionadas para os controladores e ações corretas dentro do seu aplicativo. Foram utilizadas em vários momentos, para organização das páginas da loja.

5. O Active Record em Ruby on Rails é como um tradutor entre o seu aplicativo e o banco de dados. Ele é uma camada de abstração que permite que você interaja com o banco de dados usando objetos Ruby, em vez de escrever consultas SQL complexas. Utilizado principalmente para o gerenciamento de usuários e de itens da loja, podendo inclusive guardar imagens que forem colocadas.
  
   
