NOVIDADES DA 1.122.0
- O banco de dados saiu da memória da janela: agora é um SQLite no disco, no processo principal do app, criptografado (SQLCipher, com a chave protegida pelo Windows como antes).
  - A janela fica mais leve e o app não regrava mais o arquivo inteiro a cada alteração: cada mudança já vai direto para o disco.
  - Na primeira abertura os dados são trazidos sozinhos do formato antigo (horushub.db). Nada é apagado.
  - O formato antigo continua sendo atualizado de tempos em tempos e ao fechar, então os backups automáticos e a restauração funcionam como antes, e voltar para uma versão anterior também.
  - A tela Gestão › Saúde dos apps mostra "banco no disco" em quem já está na versão nova.
- Esteira no GitHub: cada envio de código passa por verificação de tipos, todos os testes (inclusive com o banco novo) e monta a versão para Windows sozinha.

