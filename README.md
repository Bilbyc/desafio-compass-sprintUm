# 1º DESAFIO - Compass

## Descrição do Projeto
<p align="justify"> Referente à perguntas do 1º Desafio do Programa de Bolsas Compass </p><br>

**1. Para que serve o método Scrum?**

**2. Como funciona o método Scrum?**
<details>
  <summary>Ver resposta</summary>
  <blockquote>
O Scrum necessita de sua base estrutural para seu funcionamento. Para que ele seja realizado, é necessário uma equipe em que cada um assumirá um papel igualmente importante para o andamento do projeto, sendo os papeis: O Product Owner, Scrum Master e Time de Desenvolvimento. Com uma equipe bem definida ocorre o planejamento da Sprint, incluindo o seu tempo de duração (Que pode variar entre 2 até 4 semanas por Sprint), e é definida a prioridade e a divisão das tarefas, ou seja, o Sprint Backlog (Tendo como base o Product Backlog). A Sprint é o período onde o time de desenvolvimento trabalha para cumprir as tarefas designadas durante o Planning. Diariamente ocorre a Daily Scrum, uma reunião de 15 mins de duração que tem como propósito a melhoria contínua do time, repassando o andamento da tarefa, o planejamento pro próximo dia de trabalho e os impedimentos (se houverem) que estejam retardando o andamento da tarefa. Ao final da Sprint é realizada a Sprint Review, reunião esta que tem uma duração em média de 1h por semana de Sprint, nesta review há a presença de toda a equipe e do cliente e é apresentado os resultados da Sprint, das tarefas realizadas e, se os critérios foram atingidos, nesta reunião busca-se o feedback do Cliente e de preferência do usuário final também, por isso é interessante a presença deste na reunião. E por fim, ocorre o último item do ciclo, a Sprint Retrospective, que tem basicamente o objetivo de reunir a equipe para conversar sobre o quê ocorreu bem na Sprint anterior e o quê pode ser melhorado para a próxima Sprint, seguindo o fundamento de Melhoria Contínua do Scrum. Com isso, o ciclo se reinicia afim de planejar os objetivos da próxima Sprint.</blockquote> </details>

**3. O que é Git?**
<blockquote>Git é um Sistema de Controle de Versões, ele é utilizado para controlar o histórico (ou log) de modificações de arquivos e projetos. Esse controle de versões permite a transição entre diferentes fases do projeto, com o benefício de localizar erros e comparar versões. Seu controle de histórico também permite com que equipes trabalhem dentro do mesmo projeto de forma muito mais eficiente e segura.</blockquote>

**4. O que é um scrum Product Owner?**
<blockquote>O Product Owner é um dos três papeis do Scrum, basicamente ele é o dono do Produto, responsável por maximizar o valor do produto resultado pelo trabalho do time de Scrum, realiza essa função através do gerenciamento do Product Backlog, tanto definindo a prioridade das tarefas listadas nesse backlog para as Sprint Planning, quanto refinando essa lista ao longo das futuras Sprints.</blockquote>

**5. Qual o comando para criação de um novo repositório no Git?** 
<blockquote>O comando seria ‘git init’</blockquote>

**6. O que é o HTTP?**
<blockquote>Significa HyperText  Transfer Protocol, é um protocolo que define a forma de comunicação entre o navegador e o servidor, se baseia no modelo computacional de Cliente-Servidor</blockquote>
  
**7. Como funciona o HTTP?**
<blockquote>Utilizando-se do modelo computacional Cliente-Servidor, onde o cliente (Normalmente através do navegador) faz um request e aguarda uma response por parte do Servidor, uma característica deste modelo computacional é que essa comunicação sempre será iniciada pelo cliente. Estes requests são enviadas, localizadas na rede através de URIs/URLs, processadas e retornadas ao usuário (response)</blockquote>

**8. Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando?**
<blockquote>git add ‘file’ (File sendo o nome do arquivo alterado)</blockquote>

**9. O que é a Branch master e para que serve?**
<blockquote>A Branch Master seria a branch padrão do repositório, nela em que todas as outras branches secundárias serão eventualmente incorporadas (através do merge), então pode-se dizer que ela seria a versão oficial do projeto</blockquote>

**10. Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo?**
<blockquote>Utilizamos o git pull para atualizar o repositório local em relação as branchs remotas, num exemplo onde a branch principal teria o nome de main e a remote de Origin, o comando ficaria: git pull origin main

Para fazer merge de outro branch ao branch ativo utilizados o: git merge ‘nome da branch a ser realizado o merge à branch ativa’. Caso a branch ativa não seja a correta, podemos utilizar o git checkout para navegar para diferentes branches</blockquote>

**11. Qual a diferença entre git e github?**

**12. Quais os dois verbos http que podemos utiizar para realizar um update? Explique a diferença entre eles.**
<blockquote>São os verbos Put e Patch, basicamente a diferença entre eles seria: O Put é utilizado quando se quer realizar um update integral, nesse situação todos os dados do recursos são substituídos pelos novos dados que estamos passando. O Patch por sua vez também realiza um update, mas é utilizado quando se quer executar um update parcial, com esse verbo é possível modificar uma única parte do recurso. </blockquote>

**13. Qual o status code que pode ser usado na criação de um novo usuário?**
<blockquote>O status code que melhor se adequa na criação de usuários seria o 201, por definição ele significa que a request foi bem sucedida e como resultado, um novo recurso foi criado</blockquote>

**14. Quais são os três status code que modem ser utilizados para realizar o delete?**
<blockquote>Em caso de um delete bem sucedido, os Status code que podem ser utilizados seriam: o 200, que seria o mais comum como resposta a um request aceito e em processamento. O 202, que significa que o request foi recebido e aceito para ser processado, mas talvez não imediatamente e o terceiro seria o 204, semelhante aos outros dois, a diferença que é ele avisa não haver necessidade de enviar algum dado como retorno</blockquote>

**15. Exemplifique para que serve os metódos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)!**
<details>
  <summary>Ver resposta</summary>
  <blockquote>
Embora existe dezenas de variações, o primeiro número da resposta já é o bastante pra identificar o resultado da request realizada, basicamente cada um serve para:

<br>1xx: Esse é usado apenas como uma resposta temporária, indica que o servidor recebeu a request e o 1xx irá aparecer enquanto o processamento da request continua, não serve como resposta final.

2xx : Para indicar que o request foi bem sucedido

3xx: Para indicar que houve redirecionamento, normalmente ocorre o redirecionamento para uma nova URL/URI ao acessar o endereço antigo

4xx: Para indicar que ocorreu um erro do lado do Cliente, exemplo quando há erro de sintaxe ou quando se tentar acessar um recurso que não se tenha permissão 

5xx: Ocorre para indicar um erro do lado do Servidor, normalmente indica também que o Servidor está ciente do erro de sua parte ou indicar que é incapaz de processar o request em questão.</blockquote></details>

**16. Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa @node.js_mar22 e quais suas expectativas a partir de agora:** 
