## Correção: login do PRACC

- O app não reconhecia o login do PRACC. O site entra pela Steam num pop-up ("Authentication Window") e espera a resposta dele; o app bloqueava esse pop-up, então o login nunca terminava do lado do PRACC.
- Agora o pop-up da Steam abre normalmente e fecha sozinho quando o login termina; a janela do PRACC fecha em seguida e as sessões de DM entram na Rotina.
- A consulta ao PRACC agora é feita como um navegador comum e, se o site recusar, de dentro da própria página do pracc.com.
- Se o login não der certo, o aviso mostra o motivo.

Quem já tentou: clique de novo em "Conectar minha conta do PRACC" (Rotina › Dia).
