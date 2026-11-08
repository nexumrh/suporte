# NexumCell — Portal do Suporte

Aparelhos e trava (travar, liberar, liberar 24 h, mensagem, histórico) e chamados.

## Arquivos
- `index.html` — o portal (não precisa mexer).
- `nexumcell-config.js` — **cole aqui o `firebaseConfig`** do projeto NexumCell e os endereços dos portais. Use o **mesmo conteúdo** em todos os repositórios NexumCell.

## Publicar (GitHub Pages)
1. Estes arquivos ficam no repositório `nexumrh/suporte`.
2. *Settings → Pages → Branch: main / (root) → Save*.
3. Endereço: `https://nexumrh.github.io/suporte/` (ou domínio próprio em *Custom domain*).
4. No Firebase: *Authentication → Configurações → Domínios autorizados* → adicione o domínio.

Sem `apiKey` no config, o portal abre em **modo demonstração** (dados de exemplo só no navegador).
