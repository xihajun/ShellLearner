# ShellLearner
Another useful thing to learn. When I first started, Shamith asked me to count how many files. I didn't know why to do that in command line. It turns out to be `ls -l folder | wc -l`. So the `ls -l` shows all the files and `wc -l` to count how many lines they have.
**TODO: Eshell**
## Important
My story tells that command line could help you a lot when you want to work effectively. When you know how to work with Emacs and command line well, I believe you will be a good coder at least.

## setup
To setup you might worry about the terminal interface by using zsh and iterm2. Sometimes, you will have to refresh your ssh cache to connect to the remote server as something have changed already. Also, git tips would be useful if you are enjoying using terminal to do project management.

- [setup zsh](https://github.com/xihajun/ShellLearner/issues/3)
- [refresh ssh cache](https://github.com/xihajun/ShellLearner/issues/4)
- [git tips](https://github.com/xihajun/ShellLearner/issues/5)

## some useful commands
- view a large file (`q` to quit)
  - `less filename`
  - `cat filename | less`
- filter 20-40 lines for file*
  - `awk 'FNR>=20 && FNR<=40' file*` 
    - [YouTube](https://www.youtube.com/watch?v=_q6Uj4X_knc&ab_channel=MelvynDrag)

## TODO: tutorial to view (by 25th Aug)
[8 Useful Shell Commands For Data Science](https://www.datacamp.com/community/tutorials/shell-commands-data-scientist)
## TODO: file permision


## Reference
- [Linux命令行中的~、/、!!含义以及最常用的命令行总结](https://www.jianshu.com/p/d9bbcb45ac95)
- [Working with CSVs on the Command Line](https://bconnelly.net/posts/working_with_csvs_on_the_command_line/)
