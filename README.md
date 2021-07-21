# get banner from users on discord
get the user's banners with just one command

with just one command you can get the banners of users. just enter the command and pass the key 'banner' and vúala, now you will have the banner of the users

<h1>in the desired command enter the following code</h1>

    const bannerHash = (await this.client.api.users[user.id].get()).banner;
    if (!bannerHash) message.channel.send(`o ${user} não possuí nenhuma banner😟`);

    const banner = `https://cdn.discordapp.com/banners/${
      user.id
    }/${bannerHash}${bannerHash.startsWith("a_") ? ".gif" : ".png"}?size=4096`;
<h1>supported languages</h1>
<img alt="NodeJS" src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node.js&logoColor=white"/>
<h1>platform tested</h1>
<img alt="Repl.it" src="https://img.shields.io/badge/Repl.it-%230D101E.svg?style=for-the-badge&logo=Replit&logoColor=white"/> 
