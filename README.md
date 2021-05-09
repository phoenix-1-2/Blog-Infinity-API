# Blog Infinity API
Developed a real-world blogging platform API. It has features like Adding Post, Editing Post, Deleting Post, Image Uploading, and Advanced Authentication.

#API Docs

## GET REQUEST

### /feed/posts -> To get all the posts
### /feed/post/id -> To get a single post of particular id
### /feed/login -> To login the Blog Infinity

## POST REQUEST

### /feed/post/ -> To post a particular blog
### /feed/signup -> To sign up the blog

## PUT REQUEST

### /feed/post/ -> To update a particular blog


## DELETE REQUEST

### /feed/post/id -> To delete a single post of particular id



---
## Requirements

For development, you will only need Node.js and a node global package, Yarn, installed in your environement.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

###
### Yarn installation
  After installing node, this project will need yarn too, so just run the following command.

      $ npm install -g yarn

---

## Install

    $ git clone https://github.com/phoenix-1-2/Blog-Infinity-API
    $ cd Blog-Infinity-API
    $ npm install

## Configure app

Open `a/nice/path/to/a.file` then edit it with your settings. You will need:

- A setting;
- Another setting;
- One more setting;

## Running the project

    $ npm start

## Simple build for production

    $ npm build
