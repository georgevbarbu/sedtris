A small tetris game cloned from uuner on github.
If cloning the repository on windows and then porting it to Linux, you need to use the sed command in order to remove the \r from the newline caracter in windows.
Like so:
sed $'s/\r$//' ./sedtris.sed >sedtrisU.sed
sed $'s/\r$//' ./sedtris.sh >sedtrisU.sh

Usefull link working on 27.10.2020: 
https://stackoverflow.com/questions/29045140/env-bash-r-no-such-file-or-directory