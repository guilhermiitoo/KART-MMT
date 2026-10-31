# Modelos 3D (Meshy)

O jogo já tem os 6 pilotos e os 6 veículos feitos em código. Para trocar um deles por um modelo do Meshy, suba o arquivo `.glb` com o nome certo nesta pasta:

| Piloto | Arquivo | Veículo | Arquivo |
|---|---|---|---|
| CAPY | `modelos/personagens/capy.glb` | CAPIVARA | `modelos/veiculos/capivara.glb` |
| FOX | `modelos/personagens/fox.glb` | FOGUETE | `modelos/veiculos/foguete.glb` |
| RICKY | `modelos/personagens/ricky.glb` | TURBO | `modelos/veiculos/turbo.glb` |
| ZORP | `modelos/personagens/zorp.glb` | NEON | `modelos/veiculos/neon.glb` |
| HAMMY | `modelos/personagens/hammy.glb` | MONSTRO | `modelos/veiculos/monstro.glb` |
| OSSUDO | `modelos/personagens/ossudo.glb` | FANTASMA | `modelos/veiculos/fantasma.glb` |

O que o jogo faz sozinho:
- **Piloto:** ajusta a altura, centraliza no banco do veículo e coloca o volante na frente dele.
- **Veículo:** ajusta o tamanho pelo comprimento (6,6 m no jogo) e centraliza.
- **Falta de arquivo:** se o arquivo não existir, continua usando o modelo feito em código.

O que muda com o veículo do Meshy:
- **Cor e número:** ele fica com as cores da textura dele, então não pinta com a cor do jogador nem mostra o número. A cor do jogador continua na placa do nome.
- **Rodas:** as rodas não giram, porque o modelo vem em uma peça só.

Dicas para gerar no Meshy:
- **Pose do piloto:** **sentado, com as mãos para a frente** (como se segurasse um volante), **sem o carro**.
- **Veículo sem piloto:** gere com o **banco vazio**, porque o piloto entra separado.
- **Leveza:** use o modelo leve (baixo polígono) e textura 1024. O jogo roda com até 6 telas ao mesmo tempo.
- **Direção:** a frente do modelo deve olhar para a frente (padrão do Meshy).

Os modelos só carregam pelo site (Netlify). Abrindo o `index.html` direto do computador, aparece o modelo feito em código.
