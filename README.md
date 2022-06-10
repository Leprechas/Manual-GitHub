# Manual-GitHub
Desenvolvido por: 

  Ana C. S. Brandão,

  Guilherme G. Dariani,

  Shaian J. Anghinoni,

  Vitor E. G. Barelli.
  
  Link para baixar o manual: [Manual GitHub.pdf](https://github.com/Leprechas/Manual-GitHub/files/8881200/Manual.GitHub.pdf)
  
<h2> Sumário </h2>
<ol>
<li> # print("Vamos lá, o que é o GitHub?"); </li>
<li> # print(“Como usar o GitHub?”); </li>
<li> # print(“Já criei meu repositório, e agora?”); </li>
<li> # print(“Ei, moço... mas o que é commit?”); </li>
<li> #print(“Você pode baixar um repositório de outro usuário para colaborar! Mas como?”); </li>
<li> # print(“Baixando o repositório para a sua máquina, editando e enviando de volta para o servidor do GitHub”); </li>
<li> # print(“Multiverso da GitLoucura: Criando um “universo paralelo” para editar sem influenciar no seu documento principal!”); </li>
</ol>
 
# print(“Vamos lá, o que é o GitHub?”)

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git, ele permite que programadores ou qualquer usuário da plataforma produza códigos abertos, ou não, e contribuam em projetos de outros usuários.

Imagem 1

print("tradução: - wow! Como você conseguiu tudo isso?
Toda vez que eu mudo uma linha... eu faço UM push!
Jesus Cristo.")

Não entendeu a tirinha? Aposto que depois deste manual, você vai reler e rir! (Ou ao menos soltar um arzinho pelo nariz). 

# print(“Como usar o GitHub?”)

  O primeiro passo é criar uma conta, é muito simples! Só clicar em “sign up” ou “inscreva-se” e seguir os passos! =)
  
  Depois, vamos criar um repositório, que é uma pasta, onde você junta tudo sobre um projeto. Então;
  
Passo 1 - Vá no seu perfil e clique que "repositories";

Passo 2 - Criando um repositório: clique em "New" e de um nome para o repositório em "Repository name", se você quiser, pode descrever brevemente sobre o seu trabalho em "description";

Passo 3 – Logo abaixo da descrição, existe a opção de escolher se o seu repositório vai ser público "public" ou privado "private";

Passo 4 - Para iniciar seu repositório, você pode escolher começar com uma pasta base clicando em "add a README file" (o README é um documento, geralmente em texto, com uma breve descrição do seu projeto ou instruções sobre);

Passo 5 - Se você quiser, pode adicionar alguma linguagem de programação no "add .gitignore" e essa linguagem vai ter as bibliotecas e adicionais excluídos para não atrapalhar seu código (resumindo, vai ficar mais bonitinho);

Passo 6 - Em "chosse a license" é onde você pode escolher se o seu código vai ser apenas seu, e seu uso dependerá da sua permissão, ou, você apenas vai liberar seu código para livre uso com direitos autorais, existem alguns termos e responsabilidades dependendo do tipo de licença escolhido. 

# print(“Já criei meu repositório, e agora?”)

Vamos editá-lo!

Passo 1 - Seu repositório foi criado, agora vai começar a editar: Após clicar em "create", abrirá uma nova aba automaticamente, nessa aba você terá diversas outras informações, mas, vamos focar no início: clique em "<> code" ali você vai ver a pasta "README.md" criada anteriormente e aí poderemos editar essa pasta!

Passo 2 - Vamos editar a pasta "README.md", clique na imagem de lápis e a aba vai se modificar e dividir em duas "<> edit file" e "preview", na primeira você pode escrever um texto ou adicionar seu código e na segunda você terá uma prévia de como vai ficar quando terminar de editar; 

Passo 3 - SEMPRE que você editar uma pasta, texto ou um mísero ponto na linha de código, um "commit" será criado. Os "commits" serão encontrados rolando um pouco para baixo na página. 

# print(“Ei, moço... mas o que é commit?”)

Commit é, basicamente, um comentário da edição que você realizou, é útil para você não se perder conforme o documento/pasta evolui e ver suas edições e quem editou, ali temos duas caixas de texto, na primeira você deve dar um título para a edição e na segunda tu descreves o que foi feito ou os motivos da modificação.

Passo 1 - Para confirmar sua edição e commit, clique em "commit changes" aí o seu comentário e edição serão adicionados no histórico;

  Curiosidade do "commit": ele também serve como uma máquina do tempo, clicando no símbolo do relógio com uma seta no sentido antihorário (o histórico) tu podes ver a antes e depois da sua edição.

Passo 2 - Criando uma nova aba/pasta/"file" ou como você quiser chamar: clique em "add file", esse bloco fica embaixo de "insights" no começo da página;

Passo 3 - Clique em "create new file" para criar e a página irá atualizar e você deverá dar um nome para a nova pasta e, assim, pode usar como pretender essa nova "file". 

# print(“Você pode baixar um repositório de outro usuário para colaborar! Mas como?”)

Passo 1 - Escolha um repositório ou tenha um link de repositório;

Passo 2 - Abra o link ou o repositório;

Passo 3 - Clique em "fork" e a página irá atualizar, você pode alterar o nome do repositório e adicionar uma descrição, depois disso clique em "create fork";

Passo 4 – Abrirá o "fork" feito, ele é semelhante a uma cópia do repositório original. Para colaborar, escolha alguma das pastas ou file e edite algo dentro delas;

Passo 5 - Após editar faça o "commit changes" ou "propose changes" para confirmar sua alteração, clique na aba "pull requests", que seria a edição feita por você para o arquivo, ali, você pode criar e enviar o seu comentário sobre algo clicando em "new pull request" ou comparar com outros comentários e enviar o seu comentário clicando em "compare e pullrequest";

Passo 6 – Agora, basta o dono do arquivo aceitar as mudanças feitas na sua aba do "pullrequest". Mas saiba que: o dono do repositório não vai conseguir aceitar arquivos que deem conflito na hora de atualizar o repositório original, então, sempre se lembre de editar o repositório mais recente.

# print(“Baixando o repositório para a sua máquina, editando e enviando de volta para o servidor do GitHub”)

  Para baixar algum repositório em uma máquina precisamos criar uma pasta nomeada como você quiser e em qualquer lugar do seu computador, e ter o software GitBash instalado.
  
Passo 1 - Na pasta criada, clique com o botão direito do mouse e clique em "Git Bash Here", isso deve abrir um painel, estilo prompt de comando, do Git;

Passo 2 - Escreva "git status" e clique em enter para confirmar que o painel não tem nenhum trabalho rodando, algo como “nothing to commit, working tree clean”;

Passo 3 - Escreva "git clone link" e clique em enter, mas atenção: mas você não vai colocar literalmente "link"! Para colar o link, você usa shift + Insert. Esse link pode ser achado clicando em “code”, que está ao lado de “add file”, verifique se a opção HTTPS está selecionada e clique em algo que parece dois papéis sobrepostos , que é para copiar o link;

Passo 4- Você vai notar que aparecerá um documento na pasta "GitHub", não se preocupe, ele só vai ficar lá enquanto estivermos usando-o;

Passo 5 – Agora, com algum software de sua preferência, pode ser VisualCode, ou outro, você pode abrir e editar o repositório, é importante dar um “cd nome_do_repositório” (esse nome aí é o nome do repositório, não literalmente como está escrito) para indicar o painel que os comandos a seguir devem ser dados em função do seu repositório; 

Passo 6 - Lembre-se que você está editando na sua máquina, logo, se você não fizer nada, o repositório online não será modificado;

Passo 7 - Após editar o que quisermos, temos que fazer o mesmo passo que online, o passo de dar um "commit", só que no Git Bash. Você deve escrever “git commit -m "título da edição” (-m = permite você criar uma mensagem para o commit);

Passo 8 - O título da edição é pessoal, após dar enter no passo commit, você deve dar "git status" para ver se o painel terminou de rodar os seus pedidos;

Passo 9 - Se você modificou algum documento, o "git status" vai retornar "modified: nome_do_repositório" na cor vermelha, isso significa que ele identificou uma modificação nesse repositório;

Passo 10 - Para mandar o painel adicionar a modificação feita, deve-se escrever "git add ."(que vai adicionar todas as modificações aos seus respectivos documentos);

Passo 11 - Para verificar se tudo está ocorrendo de forma certa, dê um "git status" e ele deve retornar "modified: nome_do_repositório" na cor verde, isso significa que tudo ocorreu com sucesso! 

Passo 12 - E, por fim, um "git push" para mandar o documento atualizado para o servidor da GitHub.
  
  Agora você pode verificar no GitHub online que o documento foi atualizado com sucesso! 

# print(“Multiverso da GitLoucura: Criando um “universo paralelo” para editar sem influenciar no seu documento principal!”)

Passo 1 - Para criar o “branch”, iremos chamar esse universo de “branch” a partir de agora, é necessário abrir o site no repositório escolhido;

Passo 3 - Com ele aberto, clique no quadrado superior esquerdo escrito "main", escreva o nome do “branch”;

Passo 4 - Depois de escrito, irá abrir uma opção "create branch:[nome_do_branch]", clique nessa opção;

Passo 5 - Com isso irá criar um espaço novo no diretório, com a cópia de todos os arquivos da "main";

Passo 6 - Agora abra o Git Bash na pasta do repositório no seu computador;

Passo 7 - Primeiro é dar o comando “git pull”, com isso o Bash já reconhece o "branch”;

Passo 8 - Para selecionar a “branch” o comando é "checkout [nome_branch]";

Passo 9 – Pronto! Você está dentro da “branch”, tudo que você fizer aqui ficara apenas nessa “branch”;

Passo 10 - Vamos testar se deu certo: crie um arquivo qualquer, pode ser um "teste.txt";

Passo 11 - Vamos adicionar ele usando o "git add .", depois vamos dar o “commit” para ficar salvo nesse “branch”, se não fizer esses dois passos o arquivo não tem um “branch” fixo;

Passo 12 - Se os passos foram corretos o arquivo está linkado com um “branch”, então podemos dar o comando "git checkout main", notou que o arquivo sumiu? Se quiser salvar a alteração não esqueça do push;

Passo 13 - Sempre que quiser editar um arquivo específico sem alterar o main, ou criar um arquivo sem ter certeza se irá utilizá-lo, volte para qualquer “branch” e faça o que você precisar sem interferir na principal;

Passo 14 - Quando quiser juntar as “branch’s” (sim! você pode), irá colocar tudo que não tem na principal na principal;

Passo 15 - Abra o site no repositório, nas opções superiores tem o pull request, clique no Pull requests, na tela aberta clique em new pull request;

Passo 16 - Na nova tela aparecera uma barrinha, mude as opções, nesse exemplo base: main e “compare: [nome_branch];

Passo 17 - A tela irá mudar mostrando todas as alterações entre um “branch” e outro, se estiver correto clique em "create pull request", se quiser mudar o nome a hora é agora, se não, clique novamente;

Passo 18 – Sim... outra confirmação! Se ficou verdinho, clique em "merge pull request", e confirma novamente ou pode mudar a descrição;

Passo 19 – Pronto, deu certo! Volta para a opção Code, está na barra superior, agora você consegue ver que o arquivo está na “branch” main.

  Esse negócio de “branch” é mesmo meio confuso, e você pode ficar como esse meme:
  
  Imagem 2
  
(tradução: quando eu colega de trabalho pergunta em qual branch do git você está trabalhando
atualmente)

  Mas, qualquer dúvida, procure os gênios da programação da Ilum – Escola de Ciência: Profº Daniel e Profº James, eles com certeza saberão te ajudar! 
  
 # print(“Esperamos que tenha gostado e que esse manual possa te ajudar! Boa sorte nos seus estudos!”)
