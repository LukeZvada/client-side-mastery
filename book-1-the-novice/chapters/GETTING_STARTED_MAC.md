# Getting Started

## Journal

Get a nice journal and a comfortable pen, and start keeping a daily journal of what you are learning every day. Writing your thoughts on a regular basis [increases your ability to remember it](https://www.lifehack.org/articles/featured/writing-and-remembering-why-we-remember-what-we-write.html). There are even studies that found writing is [beneficial for your health](https://www.apa.org/monitor/sep01/keepdiary.aspx).

## Hardware

Up until now, you didn't have the power to destroy your machine, but within the first two weeks of attending Nashville Software School you will have that power. Go buy a backup drive RIGHT NOW and start backing up your entire hard drive.

**Seriously, right now!**

## Online Services

### Github

Github is the primary site that software developers throughout the world use to store their code, and share it with other developers. Visit the [sign up page](https://github.com/join) and create your own, free account.

### dbdiagram.io

Sign up on [dbdiagram.io](https://dbdiagram.io) and bookmark the site.

### devdocs.io

Bookmark the [devdocs.io](https://devdocs.io/) site. It contains documentation for nearly everything you will be learning during your time here at NSS.

## Spectacle

This application will allow you to use certain combinations of keys on your keyboard to move and resize applications while you are developing.

[Download and install Spectacle](https://www.spectacleapp.com/) and after it is installed, click on the link labeled _**keyboard shortcuts**_ on the web site to try it out.

## Homebrew

Visit the [homebrew home page](http://brew.sh/) and follow the single instruction there to get it installed.

### Did it work?
Make sure that homebrew was installed successfully by typing this in your terminal:
```
brew help
```

If you see the message `command not found`, go through the homebrew instructions again.

## Visual Studio Code

Visual Studio Code is the editor we will all be working on to start the course. To install it, run the following command

```sh
brew cask install visual-studio-code
```

## Command Line Launcher

Set up Visual Studio Code to be [launched from the command line](https://code.visualstudio.com/docs/setup/mac).


## Google Chrome

[Google Chrome](https://www.google.com/chrome/browser/desktop/index.html) is the most popular browser for web developers because of the powerful tools it provides to test code, manipulate documents, and measure performance.

## Node

Visit the [Node.js](https://www.nodejs.org) site and install the LTS release.

### Did it work?

Make sure that Node was installed successfully by typing in your terminal:
```
node -v
```

If you see the message `command not found`, go through the node installation again.

## Node Packages

Now that you have Node installed, you can install some open source software that you will need in the course.

```sh
sudo npm i -g serve json-server
```

### Did it work?
Make sure that `serve` was installed successfully by typing in your terminal:
```
serve -v
```

If you see the message `command not found`, type in `sudo npm i -g serve` again.

Make sure that `json-server` was installed successfully by typing in your terminal:
```
json-server -v
```

If you see the message `command not found`, type in `sudo npm i -g json-server` again.

## Xcode Command Line Tools

Since you are going to be learning how to be a professional software developer, you will be using your computer terminal heavily. OSX users need to install some baseline tools to use more advanced things later in the course.

Type this command into your terminal, and then wait a while.

```sh
xcode-select --install
```

## Git

Git is how you and your teammates will work on a shard codebase during your time at NSS. Type in the following command to install.

```sh
brew install git
brew install tig
```

### Did it work?
Make sure that Git was installed successfully by typing in your terminal: 
```
git --version
```

If you see the message `command not found`, go through the git installation again.

### Configuring Git

Once Git is done being installed, watch the video on how to [set up global Git configuration](https://youtu.be/66EB9oxGMzQ) so that you can successfully back up your code to Github in a few days... once we show you how to do it.

### Handling Permission Issues After Setup

Sometimes, a student has permission issues after installing and configuring Git. To ensure that this doesn't happen to you, watch the [Owning Your Git Config Directory](https://youtu.be/exva3J_jojc) video and follow the steps.

## Oh My Zsh

1. If you haven't install Homebrew from the previous step, please complete that first.
1. Install zsh which is a powerful replacement for the standard bash terminal by typing the following command into the terminal
    ```sh
    brew install zsh zsh-completions
    ```
1. Install [Oh My Zsh](http://ohmyz.sh/) which is a framework for Z shell which makes the terminal a pleasure to work in. Use the following command.
    ```sh
    sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
    ```
1. Run the following command in Terminal application.
    ```sh
    echo 'alias gs="git status"
    alias hs="serve -l 8080"' >> ~/.zshrc
    ```

## Show Hidden Files

While you have your terminal open, enter in the following command.

```sh
defaults write com.apple.finder AppleShowAllFiles YES
```

This will allow you to view hidden files in the Finder app.

## SSH Key

SSH is a technology that allows you to create a very secure connection between your computer, and a computer located somewhere else in the world. It's an acronym for Secure SHell. When you create an SSH key on your computer, it actually creates two files

1. A public key file that you share with other people and computers. It is usually named `id_rsa.pub`.
1. A private key file that you never, ever, ever, ever, ever share with anyone. It is usually named `id_rsa`.

### Creating Your SSH Key

Watch a short video for [creating an SSH key in the terminal](https://youtu.be/znRMcNG9_qQ) so that you an work with Github.

### Add SSH Key to Github Account

Now watch the video for [adding your SSH key to your Github account](https://youtu.be/8hlmIObpMd4).
