### Exercício de versionamento no github

Projeto de upload de versionamento ao Github como
proposta de exerício pela FIAP, segundo semestre do curso de Análise e Desenvolvimento de Sistemas.

Com o exercício, pude retomar um pouco meu conhecimento a pouco esquecido dos comandos básicos do git
e reaver as técnicas e utilidade do mesmo. 

Os comandos utilizados seguem abaixo:

<pre>
//criação de ambiente git
git init

//configuração de usuário
git config --global user.name "Jonatan Nogueira"
git config --global user.email "jonatan.magrao92@gmail.com"
gif config --list

//criação de uma branch e commiting
git add * 
git commit -m "Primeiro commit"

//verificação do status de commit
git status

//envio para github através da linha de comando
git remote add origin https://github.com/JonatanMagrao/fiap_cap_5.git
git push -u origin master
</pre>
