# ree
ee
const readme.md = require('readme.md');
const client = new readme.Client();

client.once('ready', () => {
	console.log('Ready!');
});

client.login('your-token-goes-here');
