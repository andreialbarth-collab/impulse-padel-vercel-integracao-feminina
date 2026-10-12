# Impulse Padel BVB — Torneio

Aplicação estática pronta para deploy na Vercel.

## Deploy pela interface da Vercel
1. Extraia o ZIP.
2. Acesse https://vercel.com/new e importe/crie um projeto.
3. Faça upload do diretório do projeto em um repositório Git (GitHub/GitLab/Bitbucket) e importe esse repositório na Vercel.
4. Não é necessário configurar Build Command nem Output Directory. O site é estático e o `index.html` fica na raiz.
5. Clique em Deploy.

## Rodar localmente
Abra `index.html` no navegador. Não há dependências ou etapa de build.

## Recursos
- Cadastro de 8 jogadores de direita e 8 de esquerda.
- Sorteio de duplas e confrontos nas rodadas 1 e 2.
- Da rodada 3 em diante, duplas cruzadas pelo ranking anterior.
- Tentativa de evitar adversários repetidos em rodadas consecutivas.
- Placares, pontos de classificação e ranking individual separado por lado.
- Cronograma de quadras Stone e Cresol.
- Exportação CSV dos jogos e classificação.

## Observação
Os dados ficam na memória do navegador e são perdidos ao recarregar/fechar a página. Exporte o CSV ao final para guardar os resultados. Para persistência entre dispositivos, seria necessário adicionar banco de dados e autenticação.
