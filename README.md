# alfred-bunch-workflow

> Run bunches using [Brett Terpstra's awesome Bunch app](https://brettterpstra.com/projects/bunch/) in macOS

## Dependencies
- [Node.js](https://nodejs.org) 4+
- Alfred [Powerpack](https://www.alfredapp.com/powerpack/)

## Install
```

$ npm install --global alfred-bunch-workflow

```

## Configuration

1. Open Alfred Preferences. 
2. Click on the "Workflows" tab and find Bunch.
3. Click on the "Configure workflow and variables" button.
4. Add the path to your Bunches folder in Workflow Environment Variables:
    - `bunchLocation`: `/Users/yourname/bunches`
5. (Optional) Change bunch toggle to true if you want the Alfred Workflow to open/close the bunch based on the bunches state
    - `bunchToggle`: `true`
5. Click "Save"

## Usage

- In Alfred, type `bu`. 
    - Press <kbd>Enter</kbd> to open the Bunch preference pane.
    - Press <kbd>⌘2</kbd> to refresh your list of bunch files
- Continue typing a bunch name to filter the returned list. you can further filter the list by typing a bunch name
    - Press <kbd>Enter</kbd> to run the selected bunch.

## Created Using

- [Alfy](https://github.com/sindresorhus/alfy) – Create Alfred workflows with ease

## Inspired By
- [Jay Miller](https://kjaymiller.com)  
- [Matthew Johnson](https://github.com/mttjhn/alfred-bunch)

## License

MIT © [John Christopher](https://github.com/jgchristopher/alfred-bunch-workflow)  

