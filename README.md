#Como usar senhas seguras?

Num mundo cada vez mais conectado resultará em mais ataques e ameaças de segurança.
Precisamos então melhorar o uso e abordagens de questões de segurança.
Para quem precisa usar muitas senhas, isso pode ser delicado.
O linux possui várias formas de melhorar a segurança e implementar processos automatizados de acesso e login, assim como outros sistemas operacionais.
Em uma outra abordagem criei um arquivo para geração de hash mais seguros.
Nessa abordagem trato da criação de senhas propriamente.
Não vou passar muitos detalhes técnicos apenas vou explicar como o processo de criação/uso de senhas funciona no script criado.
Programas/comandos usados:
cat 
/dev/urandom
tr
fold
head

Como você poderá criar suas senhas?
Execute o arquivo/script passwords.sh com o comando:
sh passwords.sh

Escolha sua opção de senhas que irá ser gerada aleatoriamente com letras e números.

Ao escolher a opção criar senha, se o caminho arquivo tiver sido gravado antes ele será sobrescrito.
Se a opção criar senha foi selecionada por engano é possível sair apertando control+c.

Ao escolher a opção copiar senha ela poderá ser colada via terminal ou no gerenciador de janelas qualquer seja no navegador ou app em uso.

O arquivo de senha gerada ficará na pasta raiz do script passwords.sh a menos que vc queira mudar isso reescrevendo o script.

Bom se você não deseja abrir o arquivo de senhas para visualizar, nem você saberá sua senha. Quanto mais...
Ficamos por aqui.