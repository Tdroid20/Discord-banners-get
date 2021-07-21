# get banner from users on discord
get the user's banners with just one command

with just one command you can get the banners of users. just enter the command and pass the key 'banner' and vúala, now you will have the banner of the users

<h1>in the desired command enter the following code</h1>

    const bannerHash = (await this.client.api.users[user.id].get()).banner;
    if (!bannerHash) message.channel.send(`o ${user} não possuí nenhuma banner😟`);

    const banner = `https://cdn.discordapp.com/banners/${
      user.id
    }/${bannerHash}${bannerHash.startsWith("a_") ? ".gif" : ".png"}?size=4096`;
<h3>the code was provided by<a href="https://www.youtube.com/channel/UCz2V-73WjkV9N6Nwxef9HgA"> zSpl1nterUS_<a>and adapted with permission by:<a href="https://highframe.tdroid20.repl.co">Tdroid20<a></h3>

<h1>supported languages</h1>
<img alt="NodeJS" src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node.js&logoColor=white"/>
<h1>platform tested</h1>
<img alt="Repl.it" src="https://img.shields.io/badge/Repl.it-%230D101E.svg?style=for-the-badge&logo=Replit&logoColor=white"/> 
<h1>help the creators</h1>
<h5>discord server</h5>
zSpl1nteUS_: <a href="https:/discord.gg/zafriel">Servidor do spl1nter</a>
    <br>
Tdroid: <a href="https://discord.gg/dhXQPTuQy8">Servidor do Tdroid</a>
<h5>discord bots</h5>
    Zafriel: <a href="https://discord.com/oauth2/authorize?client_id=601847636546289664&permissions=20887631278&scope=bot">adicionar o Zafriel</a>
    <br>
Highframe: <a href="https://discord.com/oauth2/authorize?client_id=821548564421148692&permissions=2147483647&scope=bot%20applications.commands%20identify">adicionar o HIghframe</a>
