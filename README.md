<div align="center">
<img src="https://i.ibb.co/F3sc7Nb/Purple-Music-Store-Etsy-Banner.png" alt="Whatsapp-Botto-Xre" border="0">

# **WhatsApp-Botto-xRe**
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FSomnathDas%2FWhatsapp-Botto-Xre.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FSomnathDas%2FWhatsapp-Botto-Xre?ref=badge_shield)


> A WhatsApp Bot Built on Top of [Baileys](https://github.com/adiwajshing/baileys) <br>
> Work in progress. More features and commands will be added soon
>
</div><br/>
<br/>

## Highlights
- 💖 Object Oriented 
- 💙 Written in [TypeScript](https://www.typescriptlang.org/)
- 💛 Event-Based 
- 💚 [Express](https://expressjs.com/) Contorl Panel
- 💜 Self-Resoting Auth
- 💝 Built with [Baileys](https://github.com/adiwajshing/baileys) (The Best WhatsApp Library Out There) 

## Features [Not limited to]
- Sticker ~ Create stickers or animated stickers, hassle free and smoothly.
- Group Utils ~ Can promote demote and remove members in the group.
- Anime ~ Get Anime information and data by either name or aid.
- Manga ~ Get Manga information and data by either name or mid.
- Character ~ Get Character information and data by either name or chid.
- Many are on their way brr brr....

## Installation 

> Make sure you have the following softwares installed
- [Git](https://git-scm.com/)
- [Node.JS](https://nodejs.org/en/)
- [WebP](https://developers.google.com/speed/webp/download)
- [FFMpeg](https://ffmpeg.org/download.html)
- [ImageMagick](https://imagemagick.org/index.php) (Make sure to enable the `legacy functions` while installing)

Clone the repo and install the npm packages after installing these
```SH
> git clone https://github.com/SomnathDas/Whatsapp-Botto-Xre
> cd Whatsapp-Botto-Xre
> npm i && npm i -D
```

## Configaration
> Edit the `config.json` according to your needs
```JSON
{
    "name": "Xre",
    "prefix": "!",
    "admins": []
}
```
`name` The name of the Bot <br>
`prefix` The Prefix of the Bot <br>
`admins` The [JIDs](https://adiwajshing.github.io/Baileys/interfaces/wauser.html#jid) of the users who you want to the Admins/Mods for the bot

> Create a file called `.env` 

In the created `.env` and make sure to add every fields wrriten below
```txt
MONGO_URI=YOUR_MONGODB_CONNECTION_URI
```
`MONGO_URI` is the [connection URI](https://docs.mongodb.com/manual/reference/connection-string/) for the Database

## Building

Run `npm run build` and the Compiled JS files, Decleration Files, Maps and Declaration Maps with their folder will appear in the `dist` folder

## Running

```SH
npm start
```
Running the above command will start the bot. 
To authenticate scan the QR which shows up in the terminal or the link which is logged when the QR event fires using the WA-Web Scanner on your WhatsApp.
Now you're on your own. Good Luck!

## Contribution

+ Feel free to open issues regarding any problems or if you have any feature requests
+ Please do follow the code strurcture while editing the files for PRs





## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FSomnathDas%2FWhatsapp-Botto-Xre.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FSomnathDas%2FWhatsapp-Botto-Xre?ref=badge_large)