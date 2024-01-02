# Publishing My Vault Online
I found a free alternative way to publish my Obsidian Vault using [Quartz](https://quartz.jzhao.xyz/) which uses node.js locally but I can use Quartz and GitHub pages to host and also properly format my markdown notes, hopefully nothing breaks.
## Setting up Quartz
Here I am just basing it from the documentation of [Quartz 4.0](https://quartz.jzhao.xyz/).
Install the Node.js v18.14 or above, or just install the latest version of Node.js. For this I will use nvm. Just follow these installation instructions
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
source ~/.bashrc
nvm install node
```
After installing Node.js next is installing Quartz.
```bash 
git clone https://github.com/jackyzha0/quartz.git
cd quartz
npm i
npx quartz create
```
This clones the Quartz repository from GitHub and initializes the files needed using `npm`. 
## Using Quartz
Quartz is going to be used to format the markdown files to be in html and also adds features like in obsidian such as the local graph, searching functions, and file navigation on the side.

For starters we are going to be locally hosting Quartz in our system to check if our markdown files are properly displayed. 
```bash
npx quartz build --serve
```
This command will start a local web server which you can visit in your browser the default is `localhost:8080`.

Visiting the site you are greeted with the starting template markdown file. To see or add files, you must put in the the `/content` directory in the cloned repo, there you will see the `index.md` which is the first file loaded when visiting the website.
