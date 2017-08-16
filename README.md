# NotesNode

## Setup 
1. Clone this repo using the command line
```shellSession
git clone https://github.com/danielhdz56/notes-node.git
```
![clone](/images/cloneRepo.png?raw=true "Optional Title")

2. Change directory and install packages using npm 
```shellSession
cd notes-node/
npm install
```
![npmInstall](/images/npmInstall.png?raw=true "Optional Title")

## How to Use
#### Help
Access help by using the `--help` or `-h` flag
```shellSession
node app.js --help
```
![help](/images/help.png?raw=true "Optional Title")

#### Commands  

Command | Description | Example
--- | --- | ---
`node app.js list`| list all notes | **nicely**
`node app.js add -t 'Hello World' -b 'I am alive'` | Add a note with a title and body | 3
`node app.js read -t 'To buy from store'` | Read a note with a title | 4
`node app.js read -t 'To buy from store'` | Remove a note with a title | 5

