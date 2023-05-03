# midjourney-discord-wrapper
use  midjourney-discord 
node.js client for MidJourney wrapper in Discord.
<div align="center">
	<p>
		<a href="https://discord.gg/GavuGHQbV4"><img src="https://img.shields.io/discord/1082500871478329374?color=5865F2&logo=discord&logoColor=white" alt="Discord server" /></a>
	</p>
</div>

[web ui example](https://github.com/erictik/midjourney-ui/)

## Implemented commands documentation
[Join discord experience](https://discord.gg/GavuGHQbV4)
Generating idea
```
/oh_imagine [ MT : prompt (string)]
```
![prompt_pwz2u1](image/prompt.gif)
Upscaling   
Reply `u1` `u2` `u3` `u4` 
![upscale](image/upscale.gif)
Variations  
Reply  `v1` `v2` `v3` `v4`
![variation](image/variation.gif)
## Usage
[How to get your Discord SALAI_TOKEN:](https://www.androidauthority.com/get-discord-token-3149920/)  
[How to create a Discord bot and add it to your server:](https://www.xda-developers.com/how-to-create-discord-bot/)
### Docker
``` bash
docker run -d  --env-file .env erictik/midjourney-discord-wrapper
```

### Node.js
To run the included example, you must have [Node.js](https://nodejs.org/en) installed. Then, run the following commands in the root directory of this project:
1. clone the repository
```
git clone hthttps://github.com/erictik/midjourney-discord-wrapper.git
cd midjourney-discord-wrapper
```
2. install dependencies
```bash
yarn 
```
or
```bash
npm install
```
3. build
```bash
yarn build
```
#
``` bash
npm run build
```
4. run the example
```bash
yarn start
```
or
```bash
npm run start
```
