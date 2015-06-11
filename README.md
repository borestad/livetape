# livetape
Run tape tests with LiveScript support

# Installation:
    npm install -g livetape

# Usage from cli:
    livetape path/to/files/*.ls

# Tips & tricks
If you don't want to install livetape as a global package, install it locally like this: `npm install --save-dev livetape`, add this nifty alias to your `.bashrc` or `.zshrc`. Don't forget to reload your environment, i.e `source ~/.bashrc`

`alias npm-exec='PATH=$(npm bin):$PATH'`

You'll now be able to run livetape like this:
`npm-exec livetape path/to/files/*.ls`
