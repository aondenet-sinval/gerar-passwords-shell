#!/bin/bash
#Comandos usados no curso Shell profissional módulo 1
#
#programador: Sinval Gomes dos Santos
#Email: sinvalsatv@gmailcom
#site: http://www.aondenet.com
#Data de criação inicial dos scripts: 20/07/21
      echo -e "Escolha uma operação:\n
      1 - Gravar nova senha \n
      2 - Copiar senha\n  
      3 - Divisão \n
      4 - Sair";
      read OPERACAO
case $OPERACAO in
		1)
      echo -e "Escolha uma nome para o arquivo de senha. Talvez prefira usar o seu no de login ou outro nome mais identifiçavel:\n";
      read arquivoDeSenha;
      echo -e "Escolha o número de caracteres para sua senha. \n ";
      read tamanho;
      caminhoDoArquivo=$arquivoDeSenha;
      echo $caminhoDoArquivo;
      echo "Essa ação irá apagar sua senha existente se ela já foi gravada. \n
      Ao prosseguir você confirma estar ciente que ao apagar sua senha ela não poderá ser recuperada. \n
      Para confirmar que você deseja criar uma nova senha sobrescrevendo uma anterior, aperte qualquer tecla + Enter. \n
      Ou digite control+c para sair ";
      read status;
      echo -e "Aguarde sua senha está sendo gerada.";
      time cat /dev/urandom | tr -dc '0-9a-z0-9A-Z0-9' | fold -w $tamanho | head -n 1 > $caminhoDoArquivo.txt;;
      2)
      echo "Digite seu login";
      read login;      
      xclip -sel clip < $login.txt;
      echo "Sua senha foi copiada para a área de transferência." ;;     
      3)
      echo $OPERACAO;;
      4)
      exit
      ;;
esac    ;