# Electron Dolphin Launcher

Clone of `electron-quick-start` for launching Dolphin process. Uses ipcMain to send messages from renderer process to main and open file. Can be used as template for 


## To Use

First create a `config.json` file at the root fo the project setup with your path to dolphin i.e.
```json
{
	"PATH_TO_DOLPHIN": <your file path>
}
```

Then install the depencies and run the project with `node`

```bash
# Install dependencies
npm install
# Run the app
npm start
```

EVERYTHING BELOW THIS LINE IS FROM THE `electron-quick-start` REPO

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
