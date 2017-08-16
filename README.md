# NotesNode

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
#### Help
Access help by using the `--help` or `-h` flag
```shellSession
node app.js --help
```
![help](/images/help.png?raw=true "Help")

#### Commands  

Command | Description | Example
--- | --- | ---
`node app.js list`| list all notes | ![list](/images/list.png?raw=true "List")
`node app.js add -t 'Hello World' -b 'I am alive'` | Add a note with a title and body | ![add](/images/add.png?raw=true "Add")
`node app.js read -t 'To buy from store'` | Read a note with a title | ![read](/images/read.png?raw=true "Read")
`node app.js remove -t 'To buy from store'` | Remove a note with a title | ![remove](/images/remove.png?raw=true "Remove")