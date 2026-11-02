NOVIDADES DA 1.66.1 (correção da Sala)
- Correção: a Sala podia ficar presa em "Não deu para conectar: cannot add presence callbacks…" quando a primeira conexão demorava (por exemplo, na primeira vez que o servidor liga o canal). Agora cada nova tentativa começa limpa, e o app tenta de novo sozinho até conectar, sem precisar reiniciar.
