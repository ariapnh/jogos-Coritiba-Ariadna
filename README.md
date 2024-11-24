# Mini Projeto: Calendário de Jogos com Google Apps Script

## Descrição

Oi, pessoal! Hoje quero compartilhar com vocês um mini projeto que desenvolvi neste fim de semana, utilizando o **Google Apps Script** e o **Google Planilhas**.

Com o fim de ano se aproximando, já estou me preparando para o calendário de jogos do meu time para o próximo ano (afinal, é o que sobrou para quem torce para o Coxa 🥲).

Anteriormente, eu costumava usar as agendas de sites de esportes (via URL de importação no Google Calendar) para manter a programação do meu time sempre atualizada no meu calendário. Porém, enfrentava alguns problemas como datas erradas ou falta de atualizações, especialmente para campeonatos menores, como o estadual.

## Como Funciona

Para 2025, resolvi testar algo diferente: criei uma **planilha** com as datas dos jogos já confirmados, incluindo **Data**, **Adversário**, **Local** e **Hora**. (Tudo com a ajuda do **ChatGPT**, que me ajudou a acelerar o processo 😄).

Depois, escrevi um **script** em Google Apps Script para que, sempre que eu adicionasse uma nova linha na planilha, um evento fosse criado automaticamente no meu **Google Calendar**. Esse processo foi inspirado no vídeo *"Como Conectar Google Planilhas à Agenda"* do **Carlos Baqueta**.

### Funcionalidades do Script:
- **Criação automática de eventos no Google Calendar** sempre que novas linhas forem adicionadas à planilha.
- **Verificação de eventos duplicados**: se o evento já existir, ele será atualizado.
- **Notificação de 5 dias** para os jogos em casa, para que eu me organize melhor e não perca nenhum jogo importante.
  
Claro, algumas melhorias foram feitas durante o processo, sempre com a ajuda do ChatGPT.

## Manutenção

Vou ter que atualizar a planilha a cada trimestre, conforme novas datas forem divulgadas, mas, sinceramente, isso já é muito melhor do que o estresse que passei este ano utilizando o calendário vinculado! 😂

## Como Usar

1. **Clone o repositório** para sua máquina local.
2. **Adicione a planilha** com as datas dos jogos (em formato `.xlsx` ou `.csv`).
3. **Instale o script**: crie um novo projeto no Google Apps Script e copie o código do script para ele.
4. **Conecte com o seu Google Calendar** e comece a usar!

## Contribuição

Se alguém tiver interesse em colaborar ou melhorar o script, fique à vontade para abrir uma *pull request* ou sugerir melhorias!
