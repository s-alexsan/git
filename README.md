# PADRÕES UTILIZADOS PARA CRIAR UMA BRANCH OU REALIZAR UM COMMIT 
**Branch**: Nomes de branches são compostos de 2 partes
 1. type ou categoria do branch. Os types podem ser os seguintes
    	 - **docs**: apenas mudanças de documentação;</br>
    	 - **feat**: uma nova funcionalidade;</br>
    	 - **fix**: a correção de um bug;</br>
    	 - **perf**: mudança de código focada em melhorar performance;</br>
    	 - **refactor**: mudança de código que não adiciona uma funcionalidade e também não corrigi um bug;</br>
    	 - **style**: mudanças no código que não afetam seu significado (espaço em branco, formatação, ponto e vírgula, etc);</br>
    	 - **test**: adicionar ou corrigir test </br>
 2. O que a branch faz em si

**Commit**
Essa é a estrutura que seguimos para um commit:

    <type>(<scope>): <subject> 
    <BLANK LINE>  
    <body>  
    <BLANK LINE>  
    <footer>
Vamos dissecá-la:

1. type ou categoria do commit: podem ser os mesmos utilizados para criar branches e que foram explicados acima.

2. scope: onde a alteração foi feita. Aqui, criamos nossos próprios scopes que, na maioria dos casos, refletem o nome de uma funcionalidade.

3. subject: um resumo do commit. Deve utilizar o imperativo, como: faz, adiciona, altera, muda e etc.

5. body: espaço utilizado para detalhar o que foi feito. É opcional.

6. footer: versão da aplicação.

Onde tem <BLANK LINE> significa que temos que deixar uma linha em branco. 🤷🏻‍♂️

[Link do artigo](https://medium.com/prolog-app/nossos-padr%C3%B5es-de-nomenclatura-para-branches-e-commits-fade8fd17106)
