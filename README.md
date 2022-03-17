# Tiger Example Project

## Credits where credits due

Since this project is strongly connected with the Tiger project, which on another side is a fork of Leopard, I have to give credit to the amazing people, responsible for this project:

- [Leopard](https://github.com/PullJosh/leopard)
- [sb-edit](https://github.com/PullJosh/sb-edit)
- [PullJosh's github](https://github.com/PullJosh)
- [adroitwhiz's github](https://github.com/adroitwhiz)
- [towerofnix's github](https://github.com/towerofnix)
- [PullJosh's youtube channel](https://www.youtube.com/channel/UCyzmitdHlr_WnDifP9b_YhA)

Please, make sure to check those links out, some amazing people participate in this project. And if you're one of the creators of this project and I've missed your credits, please don't hesitate to log an issue, neglecting your hard work is the last thing i want to do.

## What is this?

This is a simple project template to get you started working with the Tiger library.

## How to use?

### 1. Clone this project

You could do this by downloading the whole project as a .zip and extracting it on your PC, or alternatively, click the green `Use this template` and fill out the information about your project (make it private, if you don't know what you're doing). Then, go to your newly created repository, go to the green button `Code` and click on it. Copy the link there. Then, go to whereever you want to clone your project, open a terminal there and type the following command:

```
> git clone (the link you copied)
```

### 2. Initialising the project

After you've installed the project locally on your PC, open a terminal in the root of the project and run the following command:
```
> npm i
```
This will install all dependencies of the project, including `Tiger`.

### 3. Developing your project

Druing development, you'll type your code in the `./src` folder. Now it would be very convenient if the project recompiled each time you modified your code. Luckily, you can do that by running the following command:
```
> npm run watch
```
What this will do is that each time you save any of your files (remember, save, not just edit), your files will be recompiled and the server will relaunch. Then, a link to the server will be outputted. You can click on that link to see your app in action.

### 4. Deploy your project

Let's say you've reached a point at which you're happy with what you've done. What you need to do is to run this command:
```
> npm run build
```
This will build your whole project in production mode, which means that the output file sizes will be drastically smaller. Then, you can run the following:
```
> npm run serve
(on unix systems this needs to be run with elevated privileges, sudo)
```
This will start the server of the project. Again, a link will be outputted. Note that this link is bount to your system, and noone else has access to it. In order to allow others to open this link, you'll need to do wizardry like forwarding a port in your router, but fear not, a planned feature is to be able to deploy this to the world wide web.
