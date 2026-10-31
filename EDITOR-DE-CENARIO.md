# Editor de Cenário

1. **Abrir:** no menu do jogo, clique em **🛠 EDITOR DE CENÁRIO**, ou aperte **F2**. Escolha o mapa na lista do topo.
2. **Escolher:** clique num objeto (árvore, pedra, placa, casa, navio…). Ele fica marcado com uma caixa amarela.
3. **Mexer:**
   - **Mover (G):** arraste as setas.
   - **Girar (R):** arraste o anel.
   - **Tamanho (T):** arraste os cubinhos.
   - **Duplicar:** Ctrl+D.
   - **Apagar:** Del.
   - **Desfazer:** Ctrl+Z.
4. **Adicionar:** na lista à esquerda, clique num modelo pirata. Ele aparece na frente da câmera.
5. **Andar com a câmera:**
   - W A S D ou setas para andar;
   - Q / E para descer / subir;
   - botão direito do mouse + arrastar para olhar;
   - roda do mouse para ir para frente e para trás;
   - Shift para andar rápido;
   - F para ir até o objeto escolhido.
6. **Salvar:**
   - Tudo o que você muda já fica guardado **no seu navegador**, e o jogo usa essas mudanças no seu computador.
   - Para valer **para todo mundo**, clique em **💾 Salvar arquivo**. Ele baixa o arquivo `cenarios.json`.
   - Coloque esse arquivo na raiz do repositório, no lugar do atual, ou mande para o Claude.

**O que o editor não mexe:** a pista, as caixas "?" e as moedas.

**Bichos e perigos que se mexem sozinhos** (jacarés, balas de goma, tentáculo, tucanos) voltam para o lugar deles, porque o jogo os move a cada momento.

**Os modelos piratas** só aparecem pelo site (Netlify). Abrindo o `index.html` direto do computador, eles não carregam.
