# TarefasAPP
![](/assets/images/Logo_IFC2.png)
### Já fez todas as suas tarefas da faculdade hoje ?
Aplicativo destinado para os estudantes gerenciarem suas tarefas diárias no IFC Fraiburgo. Ao iniciar o aplicativo, na tela inicial, apresenta-se todas as atividades ordenadas pela data da entrega(da mais próxima a última). As tarefas possuem **título**, **data para ser entregue**, e a **prioridade da atividade**. O estudante ao concluir algumas das atividades cadastradas, ele poderá clicar no checkbox ao lado direito do nome da atividade e automaticamente o aplicativo riscará o mesmo, demonstrando que tal atividade já foi concluida. Caso o estudante precise alterar quaisquer informação na atividade, basta ele clicar no nome da atividade e o aplicativo levará ele na tela com as informações daquela atividade, ao preencher as informações atualizada o usuário poderá clicar no botão "*atualizar*" que atualiza as informações e volta para a tela inicial ou "*apagar*" que apaga a atividade do banco de dados e volta para a tela inicial. 

![](/assets/images/3TelasApp.jpg)
Uma demonstração do aplicativo pode ser [Visualizada por Aqui](https://i.imgur.com/nU7F4vc.mp4)

### Funcionalidades do Aplicativo
* Inserir, atualizar e apagar tarefas;
* Input de data é carregada automaticamente com a data atual na tela de cadastrar tarefa
* Validação nos input para verificar se o usuário escreveu corretamente
* Contador do total de atividades cadastradas e do total de atividades concluídas
* Ordenação de data mais próxima p/ ultima
* Botão de atualizar e apagar tarefas na página de detalhes da ativade.

### Pacotes e tecnologias utilizadas
Aplicativo desenvolvido com o SDK flutter utilizando a linguagem Dart
* intl 0.17.0 -> Para formatar a data no padrão BR
* sqflite 2.0.0+3 -> Banco de dados relacional
* path_provider 2.0.1 -> Para acessar o sistema de arquivo dos celulares dos usuários para que possa armazenar dados SQLite localmente.
### Comentarios
Foi utilizado a classe **SingleChildScrollView** para que o teclado não atrapalhe na digitação do usuario no input.
### Refêrencias para desenvolver esse APP
* [Flutter SQLite e banco de dados local](https://balta.io/blog/flutter-sqlite)
* [Simple SQFlite database example in Flutter](https://suragch.medium.com/simple-sqflite-database-example-in-flutter-e56a5aaa3f91)
* [PlayList Flutter with Sqflite | Todo List Application | Notekeeper Application | Local Database | Offline Application](https://www.youtube.com/playlist?list=PLW9-80IN43dlvfnira5Ty3-9Mq21SP3eN)
### Autor e Professor
Trabalho desenvolvido por [Leonardo Teixeira](https://github.com/leoteixeiraa/) para a disciplina de **PROGRAMAÇÃO PARA DISPOSITIVOS MÓVEIS** ministrada pelo [Prof Fabricio Bizotto](https://github.com/fabricioifc). 