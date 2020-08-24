# ShellLearner
Another useful thing to learn. When I first started, Shamith asked me to count how many files. I didn't know why to do that in command line. It turns out to be `ls -l folder | wc -l`. So the `ls -l` shows all the files and `wc -l` to count how many lines they have.

## Important
My story tells that command line could help you a lot when you want to work effectively. When you know how to work with Emacs and command line well, I believe you will be a good coder at least.

## Setup (Zsh)
I'd like to use zsh as the terminal tool as it looks pretter. I would like to set up a **random theme** when I open zsh every time which makes changes to my coding life I think. Also, I would highly recommand the **alias setting** which give you a short key to call a thing. **`export PATH=$PATH:\path`** could help you to load the packages or tools you've installed.
By adding those lines inside `~/.zshrc`, you can unlock those useful and interesting functions.
- random theme: `ZSH_THEME="random"`
- alias: 
  - `em` - emacs example: `alias em='emacs'`
  - `open` - to open file manager: `alias open='nautilus ./'`
- export: eg. meme - `export PATH=/home/jh2259/meme/bin:/home/jh2259/meme/libexec/meme-5.1.1:$PATH`
