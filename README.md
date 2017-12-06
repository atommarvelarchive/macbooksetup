# macbooksetup
A guide to setting up a macbook to develop on


# Intro
SHINY NEW AND EXCITING!!!!!!

Let's get you all set up! I make the assumption that you are installing these things in order.

# General mac usage tips
Here is a detailed list of keyboard shortcuts on mac:
https://www.danrodney.com/mac/

Here are some pieces to get you started:

* (⌘) represents the command key which is to the left and right of the space bar
* (⌥) represents the option key which is next to both of the command keys (it just says option on it)
* (⌘ + X/C/V/Z) is how you cut/copy/paste/undo in most apps
* (⌘ + TAB) to switch between apps like (alt+tab) on windows
* (⌘ + \`) to switch between multiple instances of the same app
    * \` is the key to the left of 1
    * For example: if you had multiple chrome windows open, that is how you switch between them.
* Using 3 fingers to swipe up on the trackpad shows you all your current windows on your desktop. 
    * You can then click on a window to bring it into focus
    * You can also swipe down with 3 fingers to go back to the previous view that you came from
    * This feature is called 'Mission Control' in case you need to Google questions
* (⌘ + spacebar) opens spotlight
   * It's like the equvalent of using the search in the start menu in windows
   * You can type the names of applications in this to easily find and open them.
   * You can also see a list of apps by pressing the f4 button (it has a grid icon on it)
* The App called [Finder](https://support.apple.com/en-us/HT201732) is the equvalient to windows file explorer

[Get a full list of useful common shortcuts here!](https://www.danrodney.com/mac/)

# [Magnet](https://itunes.apple.com/us/app/magnet/id441258766?mt=12)
### What
Here's the description from the App Store:
> Every time you move a content from one app to the other, compare data side by side or multitask in any other way, you need all the windows arranged accordingly. Magnet makes this process clean and simple.

> In one drag to the edge, you size a window into half of your screen. And by dragging windows to the corners, you snap them into quarters. Slide them to the bottom edge of your display to create thirds. Taking advantage of such arrangements eliminates app switching and greatly enhances workspace efficiency.

> Magnet supports keyboard shortcuts as well, for every command it has to offer. There is that little icon sitting in the Menu Bar where you can find a predefined set or create yours.
### Why
Organizing windows is not that great in MacOS, so this app makes it easy.
### How
[Go to this link.](https://itunes.apple.com/us/app/magnet/id441258766?mt=12) On the left side, click the blue button that says 'View in Mac App Store'. It'll cost a few bucks, but just send a venmo request :). 

# Google Chrome
[Just go here and follow instructions](https://www.google.com/chrome/browser/desktop/index.html)

# [iTerm2](https://www.iterm2.com/)
### What
A terminal that is more fully featured than the one that comes with macOS by default.
### Why
Just a quality of life thing. I also assume that this is the terminal you are using.
### How
[Just download it here!](https://www.iterm2.com/downloads.html) You probably just have to open whatever it downloads

# [Homebrew](https://brew.sh/)
### What
> The missing package manager for macOS.
### Why
 An easy way to install packages. Like programming languages and libraries.
### How
Just run the following line in iTerm2 which will download a script and execute it.
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# Z Shell
### What
Zsh is a shell designed for interactive use, although it is also a powerful scripting language.
### Why
Z Shell + Oh-My-ZSH (which is what we will install next) gives you a better overall terminal experience!
### How
Run this in iTerm2. This is your first time using homebrew to install something!
```
brew install zsh zsh-completions
```

# [Oh-My-ZSH](http://ohmyz.sh/)
### What
From the website:
> Oh-My-Zsh is an open source, community-driven framework for managing your ZSH configuration. It comes bundled with a ton of helpful functions, helpers, plugins, themes, and a few things that make you shout...
> “Oh My ZSH!”
### Why
Better terminal usage.
### How
Just run the following in iTerm2
```
$ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
Then you will probably need to close and re-open iTerm2 to see the changes

# nvm
### What
It stands for *Node* *Version* *Manager*! [The github repo is here.](https://github.com/creationix/nvm)
### Why
It simplifies installing and updating (in the future) node.js. We use this instead of just trying to install node directly.
### How
Just run this line in iTerm2. This downloads a script then executes it which takes care of installation.
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.6/install.sh | bash
```
Next run this to make sure that nvm is working:
```
source ~/.zshrc # This loads the nvm shortcut
nvm --help # This should show you a list of nvm commands you can run
```

# [Node](https://nodejs.org/en/)
### What
From the website:
> Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient. Node.js' package ecosystem, npm, is the largest ecosystem of open source libraries in the world.
### Why
It's what we use for our backends.
### How
We are going to use nvm to install it.
```
nvm install v8.9.2
```

# [WebStorm (via Toolbox App)](https://www.jetbrains.com/webstorm/)
### How
[Just install the toolbox app](https://www.jetbrains.com/toolbox/app/?fromMenu) which is also used to keep it up to date. When you open the toolbox, sign in with my account and install webstorm through it.

# Plex Player
### Why
It's just a nice desktop app to watch plex on.
### How
[Try this link or I can do it (I might need to sign in).](https://www.plex.tv/downloads/)

# Slack
[Install here](https://itunes.apple.com/us/app/slack/id803453959?mt=12)

# Sketch
### What
This is the software we used for designing the website.
### Why
So you can design on your own and access the sketch files yourself.
### How
[Download the free trial here.](https://www.sketchapp.com/) I think my Sketch can be active on two computers at a time, so I'll send you my key.

