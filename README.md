#preev.com in your menubar

![Screenshot](https://www.dropbox.com/s/bi93ufx5kghiqd3/github_menubar_electron.jpg?raw=1)

This makes [preev.com](http://preev.com) quickly available in your menubar.

preev is a simple bitcoin converter website that let's you calculate BTC to other currencies.

###Installation
Do you have `electron` installed? [Learn more about electron](https://github.com/electron/electron) and install it globally on your machine with `npm install -g electron`

###Usage
 - Clone or download this repo to a directory of your choice
 - Navigate your Terminal.app to this directory with `cd path/of/your/choice`
 - Only once you need to `npm install` the get the dependencies (electron, menubar)
 - `npm start` will run this menubar app in the background. You can close & exit your Terminal.app window

###Compiling
`npm build` should work and build this for OSX(64bit) in a /dist subdirectory but I did not test. Ensure you have electron-packager (v7.7.0+) available on your system or install it globally with `npm install -g electron-packager`. 

`electron-packager . --platform=darwin --icon=Icon --arch=x64 --out=dist PreevApp` will compile to your machine. Look inside the `dist` directory for `PreevApp`.

I've uploaded a [zipped version 0.0.1 of PreevApp](https://bit.ly/2bAhEcp) to Dropbox.

###Thank you's
Kudos to [@electron](https://github.com/electron/) and [@maxogden](https://github.com/maxogden) for his great [menubar](https://github.com/maxogden/menubar) package - plus of course the people that built & maintain preev.com - you know who you are.

* * *
If you find this repo useful consider to **give a star** or send some satoshis: `1BoFajaVNQ5Z8a3E7ZQvt8sWyTCGrxRtS9`.
Fork, comment, contribute, hack away and let me know by sending a pull request if you have any great additions to this little app project.
