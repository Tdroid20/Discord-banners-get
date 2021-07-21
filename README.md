# Discord-banners-get
get the user's banners with just one command

with just one command you can get the banners of users. just enter the command and pass the key 'banner' and vúala, now you will have the banner of the users

<h1>in the desired command enter the following code</h1>
 const bannerHash = (await this.client.api.users[user.id].get()).banner;

    if (!bannerHash) message.channel.send(`o ${user} não possuí nenhuma banner😟`);

    const banner = `https://cdn.discordapp.com/banners/${
      user.id
    }/${bannerHash}${bannerHash.startsWith("a_") ? ".gif" : ".png"}?size=4096`;
<h3>o codigo foi fornecido por <a href="https://www.youtube.com/channel/UCz2V-73WjkV9N6Nwxef9HgA">zSpl1nterUS_<a> e daptado com permisão por: <a href="https>//highframe.tdroid20.repl.co">Tdroid20<a></h3>
