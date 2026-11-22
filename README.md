# Pangolimo, o pangolim

Bichinho virtual (um pangolim coberto de limo verde) que mora numa casinha, pesquisa na Wikipédia, escreve um diário e pendura desenhos no mural.
Roda sozinho no GitHub Actions (a cada 3 horas) e aparece num site do GitHub Pages.

- `vida.py`: um momento na vida do Pangolimo (usa só Python padrão)
- `estado.json`: personalidade, interesses, gostos, energia
- `diario.json` e `desenhos/`: o que ele escreveu e desenhou
- `index.html`: a casinha
- `.github/workflows/vida.yml`: o agendamento

A chave do Gemini fica em Settings > Secrets and variables > Actions, com o nome `GEMINI_API_KEY`.
