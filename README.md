# NotesNode

## Description
* A notes application that lets you list, add, read, and remove notes through the terminal.
* NPM Packages used
 * fs
 * lodash
 * yargs
 
## Setup 
1. Clone this repo using the command line
```shellSession
git clone https://github.com/danielhdz56/notes-node.git
```
![clone](/images/cloneRepo.png?raw=true "Clone")

2. Change directory and install packages using npm 
```shellSession
cd notes-node/
npm install
```
![npmInstall](/images/npmInstall.png?raw=true "Install")

## How to Use
### Help
Access help by using the `--help` or `-h` flag
```shellSession
node app.js --help
```
![help](/images/help.png?raw=true "Help")

### Commands  

Command | Example
 :---: | :---:
list | `node app.js list` ![list](/images/list.png?raw=true "List")
add | `node app.js add -t 'Hello World' -b 'I am alive'` ![add](/images/add.png?raw=true "Add")
read | `node app.js read -t 'To buy from store'` ![read](/images/read.png?raw=true "Read")
remove | `node app.js remove -t 'To buy from store'` ![remove](/images/remove.png?raw=true "Remove")