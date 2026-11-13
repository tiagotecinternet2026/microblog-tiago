# Prompts para o gerenciamento de noticias

1. Pedir pra IA analisar o projeto no estado atual

Analise todas as classes utilizadas até o momento (contidas na pasta src), em especial
a classe NoticiaServico e a classe Noticia.

Veja também as páginas administrativas, em especial usuários.php e categorias.php.

Identifique padrões, como nomes de métodos, propriedades, variáveis, arquivos, namespaces.

Aguarde o próximo comando.


---

2. Criação do método listarTodos

Crie na classe NoticiaServico o método listarTodos, de maneira semelhante ao que foi feito em CategoriaServico e UsuarioServico.

Atenção: a consulta SQL deve no caso de usuários admin, carregar todas as noticias incluindo o nome do autor delas. Se for um usuário editor, a consulta deve carregar apenas as noticias dele próprio, sem incluir o nome do autor.










Tarefas:

- visualizar noticias e nome do autor delas (admin)
- visualizar noticias próprias (editor)