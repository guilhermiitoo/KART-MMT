# Modelos 3D (Meshy)

O jogo já tem os 6 pilotos feitos em código. Para trocar um deles por um modelo do Meshy, suba o arquivo `.glb` com o nome certo nesta pasta:

| Piloto | Arquivo |
|---|---|
| CAPY | `modelos/personagens/capy.glb` |
| FOX | `modelos/personagens/fox.glb` |
| RICKY | `modelos/personagens/ricky.glb` |
| ZORP | `modelos/personagens/zorp.glb` |
| HAMMY | `modelos/personagens/hammy.glb` |
| OSSUDO | `modelos/personagens/ossudo.glb` |

O que o jogo faz sozinho:
- **Tamanho:** ajusta a altura e centraliza o modelo no banco do veículo.
- **Volante:** coloca o volante na frente do piloto.
- **Falta de arquivo:** se o arquivo não existir, continua usando o piloto feito em código.

Dicas para gerar no Meshy:
- **Pose:** gere o personagem **sentado, com as mãos para a frente** (como se segurasse um volante), **sem o carro**.
- **Leveza:** use o modelo leve (baixo polígono) e textura 1024. O jogo roda com até 6 telas ao mesmo tempo.
- **Direção:** a frente do personagem deve olhar para a frente do modelo (padrão do Meshy).

Os modelos só carregam pelo site (Netlify). Abrindo o `index.html` direto do computador, aparece o piloto feito em código.
