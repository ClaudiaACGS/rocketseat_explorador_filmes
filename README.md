# rocketseat_explorador_filmes

Crie um aplicativo Android chamado "Explorador de Filmes", que permita aos usuários buscar e visualizar informações sobre filmes populares. O aplicativo deve consumir dados de uma API externa (The Movie Database - TMDb ou similar), seguir os princípios de Clean Architecture, utilizar Injeção de Dependência (Hilt) e ser modularizado.

Instruções
Estrutura, regras e requisitos do projeto

1. Estrutura inicial
Crie um projeto com *Kotlin utilizando XML + ViewBinding como base para criar as interfaces.
O design pattern a ser aplicado é MVVM ou MVI
O padrão arquitetural a ser aplicado é Clean Architecture (Data, Domain, Presentation)
Para Injeção de Dependência, podemos usar Hilt ou Koin
Para Gerenciamento de Estado, podemos usar LiveData ou StateFlow
Para Módulos, temos:
O módulo ⁠app é responsável apenas pela inicialização.
O módulo ⁠core contém classes utilitárias e comuns. 
O módulo ⁠feature-movies apresenta a tela de listagem e detalhes dos filmes.
O módulo ⁠feature-favorites exibe a tela de favoritos. 
O módulo ⁠data implementa os repositórios e o acesso à API. 
O módulo ⁠domain abrange casos de uso e modelos de domínio. 
Para Persistência, utilizamos Room para salvar filmes favoritos.
Para Chamada de API, empregamos Retrofit junto com Gson/Moshi. 
Para Tratamento de Erros, garantimos um exception handling adequado.
Para Navegação, utilizamos o Jetpack Navigation Component.
2. Funcionalidades obrigatórias
📱 Tela Inicial - Listagem de Filmes
Buscar e exibir filmes populares usando a API do TMDb.
Exibir:
Pôster do filme.
Título do filme.
Ano de lançamento.
Nota média.
Permitir ao usuário clicar em um filme para ver mais detalhes.
🎬 Tela de Detalhes do Filme
Exibir informações detalhadas do filme:
Título, sinopse, data de lançamento, nota, duração.
Permitir que o usuário adicione/remova o filme dos favoritos.
Exibir um botão para assistir ao trailer, abrindo o link no YouTube.
⭐ Tela de Favoritos
Listar todos os filmes que o usuário marcou como favoritos (salvos no Room).
Permitir que o usuário remova filmes da lista de favoritos.
🔎 Busca de filmes
Criar uma tela ou barra de busca para que o usuário possa procurar filmes pelo nome.
Atualizar dinamicamente a lista conforme o usuário digita.
3. API para consulta dos filmes
Utilize a API do The Movie Database (TMDb) para buscar filmes. Crie uma chave de API gratuita 
aqui
.

4. Interface (baseada no layout do Figma)
O layout deve ser feito com base no Figma do projeto. Após ele ser finalizado, se sinta livre para publica-lo e realizar alterações, mas para o desenvolvimento do desafio, se atenha ao que temos especificado no Figma.

5. Desenvolvendo o projeto
Para desenvolver esse projeto, recomendamos utilizar as principais ferramentas que utilizamos durante a formação até aqui.

Caso você tenha alguma dificuldade você pode ir no nosso 
fórum
 e deixar sua dúvida por lá!

Após terminar o desafio, caso você queira, você pode tentar dar o próximo passo e deixar a aplicação com a sua cara. Tente mudar o layout, cores, ou até adicionar novas funcionalidades para ir além 🚀

6. Entrega
Lembre-se que o intuito de um desafio é te impulsionar, por isso, dependendo do desafio, pode ser que você precise ir além do que foi discutido em sala de aula. Mas isso não é algo ruim: ter autonomia para buscar informações extras é uma habilidade muito valiosa e vai ser ótimo pra você treinar ela aqui com a gente!

E lembre-se: tenha calma! Enfrentar desafios faz parte do seu processo de aprendizado!

Após concluir o desafio, você deve enviar a URL do seu código no Github.

Além disso, que tal fazer um post no LinkedIn compartilhando o seu aprendizado e contando como foi a experiência?

É uma excelente forma de demonstrar seus conhecimentos e atrair novas oportunidades!

Obs: Se você se sentir à vontade, pode postar um print do resultado final e nos marcar! Vai ser incrível acompanhar a sua evolução! 💜

Feito com 💜 por Rocketseat 👋
