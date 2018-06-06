# MacBook Setup
Some people have asked me questions about my system setup. Which apps do I use and with what settings. Putting together this document to help answer those questions for anyone who wants a usable, productive & beautiful development experience. 

If you find something useful here, free free to share and ⭐️ the repo. Also, if you feel I am missing interesting things, put it on the [issues](https://github.com/praveenpuglia/mac-setup/issues) and I'll definitely try it out. 

---

## Terminal
![Terminal Setup](./images/Screen Shot 2018-06-06 at 10.16.31 AM.png)
I use [iTerm2](https://www.iterm2.com/) with the following settings for a pleasant terminal eperience.

- 🎨 Color Theme : [iTerm2 Snazzy](https://github.com/sindresorhus/iterm2-snazzy)
- 🔠 Font : [Dank Mono](https://dank.sh/), **15pt**, Anti Aliased, 110% Vertical Character Spacing. 
- 🗄 List Files : [Exa](https://github.com/ogham/exa). With `alias ls=exa` in `.zshrc`.
- 🖥 Prompt : [Pure Prompt](https://github.com/sindresorhus/pure). Minimal, Pretty, Useful.
- 🐚 Shell : [Zsh](http://www.zsh.org/) with [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) & this [.zshconfig](https://github.com/praveenpuglia/dotfiles/blob/master/.zshrc)
- 📝 Shell Text Editor : [Micro](https://github.com/zyedidia/micro). Yeah! Skipping the Vim vs Emacs war altogether. 😎
- 🗂 Working Directory : ✅ Reuse previous session's directory.

## Code Editor
![Visual Studio Code - Insiders](images/Screen Shot 2018-06-06 at 10.22.32 AM.png)
I use VS Code. Currently my favourite & the only one I use. 💖 

Why? Because it's fast. It has great extensions & also because I contributed to the CSS Language Service. So 🤟. 
- 🎨 Monokai Pro : [Monokai Pro Official Website](https://www.monokai.pro/vscode/)
- 🔌 Extensions
    - [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
    - [Debugger For Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
    - [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
    - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    - [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    - [IntelliSense for CSS class names](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
    - [JSON Tools](https://marketplace.visualstudio.com/items?itemName=eriklynd.json-tools)
    - [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
    - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    - [Rainbow Brackets](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets)
    - [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
    - [Text Pastry](https://marketplace.visualstudio.com/items?itemName=jkjustjoshing.vscode-text-pastry)
    - [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
    - [TypeScript Hero](https://marketplace.visualstudio.com/items?itemName=rbbit.typescript-hero)
    - [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
    - [VS Code CSS Comments](https://marketplace.visualstudio.com/items?itemName=ashhitch.vs-code-css-comments)
- 💅 Icon Theme : Seti (Visual Studio Code) - Comes preinstalled.
- 🔠 Font : [Dank Mono](https://dank.sh/). Freaking amazing font.
- ⚙️ User Settings 
    ```json
    {
        "editor.fontFamily": "Dank Mono",
        "editor.fontLigatures": true,
        "editor.fontSize": 15,
        "editor.lineHeight": 30,
        "editor.multiCursorModifier": "ctrlCmd",
        "editor.wordWrap": "on",
        "html.format.wrapAttributes": "force-aligned",
        "prettier.proseWrap": true,
        "prettier.singleQuote": true,
        "terminal.external.osxExec": "iTerm.app",
        "tslint.autoFixOnSave": true,
        "terminal.integrated.fontSize": 14,
        "terminal.integrated.fontFamily": "SF Mono"
    }
    ```

## Notes & To-dos
I recently switched to [Notion](https://www.notion.so/) and I don't think I am ever going back. I have tried gazillions of apps that help me do notes & todos but nothing has been this good. Try it out and you'll know why.

**UPDATE:** Couldn't afford to buy Notion. I miss it but have moved on to [Typora](https://typora.io/). It's not as fancy as Notion but it's the best Markdown editor I have ever found.

## Browsers
- Chrome 🤩
- Firefox Developer Edition 😌
- Safari 🙂
- Opera 🕵️‍♂️

Chrome is my primary browser and I maintain different profiles for work & personal accounts. I love it because well, it's fast, supports a lot of web standards much earlier( even though in their experimental versions ) & they have a phenomenal DevTools. 

I use the following extensions with their different browser counterparts. These are spread across different profiles.
- Awesome Screenshot
- ColorPick Eyedropper
- Element Screenshot
- uBlock Origin
- Vue Devtools
- Octotree
- JSONView
- Allow-Control-Allow-Origin: *
- Page Ruler
- Redux Devtools
- Vue Devtools

## Mail
I use [Airmail Beta](https://rink.hockeyapp.net/recruit/32ae0ef725bd451f97ea05260dfa0f28). Never liked the default Mail app and I was using [Nylus N1](https://www.nylas.com/) but they have gone full blown enterprise. Somehow Nylus was extremely slow for me even though I really liked the interface & it's support for Gmail account features like labels & stars. 

So I looked for a native app that would be fast, could sync faster & have intuituve UI. Airmail sits right on that spot. The best part is that I never even had to go to Airmail settings after installing it and adding an account. The defaults are good enough. 

## Window Management
Window management on Mac sucks by default. I had tried [Spectacle](https://www.spectacleapp.com/) and the likes but really settled on to [Magnet](https://itunes.apple.com/in/app/magnet/id441258766?mt=12). Yes it's not free but it can't be cheaper than this. Magnet supports both keyboard shortcuts & mouse drags. It works with multiple screens too. 

## Utilities
### Developer Utilities
- [Docker](https://www.docker.com/) : No need for introduction. Amazing piece of software. Why isn't the entire world dockerized yet? 🤔
- [Studio 3T](https://studio3t.com/) : For anything related to MongoDB 🍃.
- [Helm](https://itunes.apple.com/us/app/helm-hosts-file-manager/id1099472017?mt=12) : For multiple `hosts` configurations & quick switching. 😎
- [Skitch](https://evernote.com/products/skitch) I put it in developer utilities becase that's when I use it the most. While finding & annotating bugs or in communicating with Design. 📸
### General Purpose Utilities
- [KeepingYouAwake](https://github.com/newmarcel/KeepingYouAwake) : To prevent Mac from going into sleep. ☕️
- [Homebrew](https://brew.sh/) : I don't think I need to explain this. 🍻
- [GIF Brewery 3](http://gifbrewery.com/) : To quickly record screen and make high resolution, high quality GIFs out of that. 📹
- [Mounty](http://enjoygineering.com/mounty/) : To run NTFS (Windows) formatted HDDs on Mac. 💽
