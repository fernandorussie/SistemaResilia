 
<h1 align="center">Projeto Individual M4 - Sistema Resilia</h1>

<h2>Contexto</h2>

A Resilia está pensando em lançar um novo sistema de acompanhamento e para isso precisa de ajuda para modelar um banco de dados que vai armazenar seus cursos, turmas e alunos.

<h2>O que é para fazer?</h2>

Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem
e responder algumas perguntas com nosso modelo:

⇨ Existem outras entidades além dessas três?

⇨ Quais são os principais campos e tipos?

⇨ Como essas entidades estão relacionadas?


<h2>Projeto</h2>

<h4>Diagrama Lógico:</h4>
<img src="https://github.com/fernandorussie/banco-imagens/blob/main/1N.png" />

<h4>Diagrama Conceitual:</h4>
<img src="https://github.com/fernandorussie/banco-imagens/blob/main/Diagrama%20sem%20nome.drawio.png" />

<h3>Respostas:</h3>

⇨ Existem outras entidades além dessas três?<br>
> Sim, "Escola", "Professor" e "Disciplina". <br>
Acredito que tenha sido necessário acrescentar mais três entidades, aonde a entidade "Cursos", "Alunos" e "Professor" ficam vinculados a entidade "Escola" e a entidade "Professor" fica vinculado a "Disciplina", para ter um melhor gerenciamento no banco de dados. <br> <br>

⇨ Quais são os principais campos e tipos?<br>
> Os principais campos são os de Nomes, CPF, Data de Nascimento, Email e principalmente os cod_id de cada entidade.
Os tipos mais utilizados foram, int, varchar<br> <br>

⇨ Como essas entidades estão relacionadas?<br>
> Por meio de Cardinalidades:<br><br>
um-para-muitos (1:N)<br>
um-para-um (1:1) 
<br> <br>
