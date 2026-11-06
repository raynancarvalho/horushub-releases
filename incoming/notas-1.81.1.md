## Correção: verificação da HLTV ("Confirme que é humano")

- O clique na verificação da Cloudflare não passava: a verificação começava com a janela ainda escondida e travava. Agora, quando a janela aparece para você, a verificação é recarregada já visível e o clique funciona.
- A leitura automática do ranking (Comparar com o top) não abre mais a janela de verificação sozinha nem baixa os logos; se a HLTV pedir verificação, ela espera algumas horas para tentar de novo.
- Em Comparar com o top, o botão "Buscar referência agora" pode abrir a verificação (você está ali para concluir); a coleta automática nunca abre.
