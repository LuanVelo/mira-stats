# Mira — páginas estáticas

Fotografias estáticas das estatísticas de CS2 geradas pelo Mira, a partir das demos oficiais
das partidas de Premier. Sem servidor: são páginas únicas, hospedadas no GitHub Pages.

| Página | O que é |
|---|---|
| [Ficha tática](https://luanvelo.github.io/mira-stats/) | Os números de LM: cards, tendências e partidas. Gerada por `scripts/build_snapshot.py` (repositório privado do projeto). |
| [Leitura das partidas](https://luanvelo.github.io/mira-stats/leitura/) | Todas as partidas com review, com abas de LM e RM e o review de cada partida. Gerada por `npm run publish:leitura` (repositório privado do projeto) a cada atualização. |

Sobre a **Leitura das partidas**: os números saem do banco do Mira, mas os textos são escritos à
mão a partir deles — nada ali é gerado automaticamente, e por isso a página só cobre as
partidas que já têm review. Toda comparação com "a média" usa as outras partidas do mesmo jogador, nunca a partida
que está sendo lida.
