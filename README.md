# ooo
const Discord = require("discord.js"); const client = new Discord.Client();  client.on('ready', () => {   console.log(`Logged in as ${client.user.tag}!`); });  client.on('message', msg => {   if (msg.content === 'ping') {     msg.reply('Pong!');   } });  client.login('MzkxMDk3NTk1ODkzNjQ1MzEy.DSLDwQ.ehLxGkLlpiaO4SDOqFPkzA_H3jg');
