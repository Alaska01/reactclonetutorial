# Cloning React Project and Taking Over Ownership

- This project is a tutorial for people who may find it difficult creating react on their system
- I would advise such persons to clone this repository
- Check the node version on your system to ensure you have node installed. Use `$ node -v` or `$ node --version`
- run the command `$ npm install` after cloning the repo, if the project runs on your system, then here are the next steps to follow.
- Next run `$ npm start` to see if the project displays
- If the project succesfully displays, it means you can copy the project and own it.

# Create A New Folder

- The new folder you just created should be named the way you want to name your app. For me I advise naming all your react app in lowercase without spaces or any special characters i.e **newreactapp** any name of your choice is fine.
- Go to the project you just clones and copy this files and paste into your newly created folder. i.e (copy the public, src folders and .gitignore, readme, package.json files) ignore the (nodemodules and package-lock-json file and folder).
- Paste the copied content into the new folder created called **newreactapp**
- Go to the package.json file and on line 2 change this code `"name": "reactclone",` to `"name": "name of folder housing your project",` i.e `"name": "newreactapp",` as can be seen in the screenshot below.

![screenshot](/images/01cloneapp.png)

- Run `$ npm install` or the yarn command you use to install.
- After it have successfully installed, run `$ npm start` to start your project.
- Hurray, you have successfully cloned, and created a new react project and gained ownership of a new project and left the creat-react-app issues behind.
- You can begin to edit and add various components, styles and whatever you may wish to do.