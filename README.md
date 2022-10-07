# Sistema de cadastro

> Status: Em desenvolvimento

Para rodar essse projeto na sua máquina, por favor digite:

```
node app.js
```
> Resumo do que aprendi:

<p>git clone: cria uma cópia do repositório em sua máquina</p>
<p>git pull: atualiza seus arquivos locais</p>
<p>git log: exibe um relotário de todos os commits realizados. (podemos usar uma relatório light usando um --oneline)</p>
<p>git status: exibe as alterações feitas em seus arquivos. Isso o ajudará a saber o que deverá commitar e atualizar o repositório.</p>
<p>git add: adicionar um arquivo para ser commitado.</p>
<p>git commit NOME DO ARQUIVO -m "MENSAGEM DESCRITIVA DO COMMIT": serve para descrever o commit para melhor entendimento das alterações.</p>
<p>git push: "empurrar" todas os commit que você fez para o repositorio.</p>
<p>git restore --source: restaura o projeto a apartir de um commit. É nesse informar o ID do commit logo após a flag <i>--source</i>. Podemos encontrar os ID dos commit usando o <i>git log</i></p>
<p>git checkout -b NOME-DA-BRANCH: serve para criarmos novas branchs</p>
<p>git switch: para alterar as branchs</p>
<p>git branch: exibir as branchs existentes</p>
<p>git merge: unir duas branchs para fazer o push. Para isso, é necessário trocar para a branch que receberá as atualizações, depois unir as branchs indicando com o merge qual será a branch que possui as atualizações. Ex.:</p>
<p>Passo 1: git switch main<br>
Passo 2: git merge desenvolvimento<br>
Passo 3: git push origin main
</p>
:)