# GitFlow


## O que é o GitFlow
O Git Flow é um modelo, uma estratégia ou, ainda, um fluxo de trabalho muito utilizado por equipes de desenvolvimento de software. Ele se destaca por auxiliar na organização do versionamento de códigos.

## Porque estudar o GitFlow?

Desenvolvimento Paralelo
Uma das grandes vantagens do Git Flow é que ele torna o desenvolvimento paralelo muito simples, isolando o novo desenvolvimento do trabalho finalizado.

Colaboração
As branches de feature também facilitam a colaboração de duas ou mais pessoas desenvolvedoras em uma mesma tarefa, porque cada branch é uma caixa de proteção onde as únicas alterações que ocorreram são as que aconteceram para realizar a tarefa.

Com isso, conseguimos compartilhar nossa branch com outras pessoas para elas nos ajudarem ou terminarem a tarefa. Isso também torna muito fácil de ver e acompanhar o que cada pessoa está fazendo em um projeto.

Área de preparação
Mais conhecida como a branch develop, com ela é possível ter um local onde podemos testar todas as nossas novas features, isso sem se preocupar se estamos ou não em produção.

Suporte para correções de emergência
Com o suporte a branches de hotfix se torna possível realizar alterações de emergência sem preocupações, sabendo que o hotfix conterá apenas a correção. Não há risco de você acidentalmente mesclar um código que não deveria, pois tudo está devidamente separado.

Mas como nem tudo são flores, agora que vimos os benefícios do Git Flow, vamos ficar por dentro também das desvantagens de utilizar essa abordagem.

### main
È a branch onde será resistrada as versões para acabadas ou prara a produção.é usual subir as atualizações da develope para a main utilizando as versão do projeto 

### develop
é a branch secundaria originada da main. É nela o onde as features do projetos serão reunidas 


### feature 

A features derivam-se da develop, são nelas onde a o desenvolvimento de fato.

### Release
As release é onde ocorre os teste e a documentação do projeto.

### bugfix
Onde há os ajusto menos urgentes ou simples.
O bugfix pode ser origninar qualquer etapa do projeto.
### hotfix 

### Links 
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
https://www.alura.com.br/artigos/git-flow-o-que-e-como-quando-utilizar#beneficios-do-git-flow 