# Editor de Pista

Desenhe sua própria pista no jogo, com subidas, túnel, ponte, rampa e espiral grudenta.

## Como abrir
- Tela inicial: tecla **F3** (ou clique em "F3 EDITOR DE PISTA" no rodapé).
- Tela de mapa: tecla **P** ou o cartão **"✏️ DESENHAR PISTA"** no fim da lista.
  Se o mapa escolhido já for uma pista desenhada, abre ela para editar.

## Comandos
| Ação | Como |
|---|---|
| Novo ponto | clique no chão (perto da linha, o ponto entra no meio do trecho) |
| Mover ponto | arraste |
| Apagar ponto | botão direito no ponto, ou **Del** |
| Mover a vista | arraste com o botão direito no chão |
| Zoom | roda do mouse |
| Altura do ponto (0 a 30 m) | barra deslizante, **Q / E** ou **↑ / ↓** |
| Trecho especial (do ponto até o próximo) | **1** normal · **2** rampa · **3** túnel · **4** ponte · **5** espiral |
| Largada | selecione o ponto e clique em "🏁 LARGADA AQUI" |
| Desfazer | **Ctrl+Z** |
| Testar | **T** ou "▶ TESTAR PISTA" (ao sair da corrida, volta para o editor) |

## Trechos especiais
- **🛹 Rampa:** buraco com rampa no meio do trecho (água, lava, chocolate ou V-cut, conforme o tema). Funciona melhor com altura 0.
- **🕳️ Túnel:** arco de pedra com luzes no teto.
- **🌉 Ponte:** tábuas de madeira, corrimão e rio embaixo.
- **🌀 Espiral:** a pista dá uma volta de 360° subindo 14 m a partir do ponto, com a **Faixa Gruda-Gruda** (azul, brilhante): nela o kart gruda e não decola. Dica: deixe o ponto seguinte 14 m mais alto que o ponto da espiral.

## O editor avisa quando
- a pista cruza com ela mesma sem 8 m de diferença de altura (vire uma ponte subindo um dos trechos);
- dois trechos ficam encostados;
- uma curva fica fechada demais;
- uma subida ou descida fica íngreme demais;
- a pista fica curta demais (mínimo 900 m).

Erros em vermelho impedem o teste. Avisos em amarelo deixam correr.

## Onde fica salvo
- **💾 SALVAR:** fica neste navegador e a pista já aparece na lista de mapas.
- **⬇ pistas.json:** baixa um arquivo com todas as pistas. Coloque esse arquivo na raiz do repositório (ao lado do `index.html`) para todo mundo ver as pistas no site.
