# Coralinda

Bot para o Cora Hacker Clube em Nodejs

Bot criado com o propósito de ajudar os membros do Cora Hacker Clube, seja ensinando-os a programar Bots, seja informando a cotação atual do Bitcoin. Novas funções serão incorporadas por quem quiser ajudar!

#### "Feliz aquele que transfere o que sabe e aprende o que ensina"

Links úteis:

- https://core.telegram.org/bots
- https://core.telegram.org/bots/api

#### Basicamente, Bots são contas especiais que não precisam de número e que podem ser criadas com o BotFather, no próprio Telegram.

Ao criar seu Bot (/start), informe o nome e o username. Será gerado um token que você poderá usar para programar funções para o Bot.
De imediato, é possível personalizar o bot com os comandos /setdescription (Descrição), /setabouttext (Mensagem inicial do Bot para quem acessar) e /setuserpic (Foto do Bot)

Toda call ao bot deve usar a seguinte forma:
https://api.telegram.org/bot\<token\>/METHOD_NAME

Assim, foi a token foi colocada dentro de um arquivo .env, e referenciado sempre no código usando os dizeres "process.env.BOT_TOKEN".
