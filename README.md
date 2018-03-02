# GitCompletion

- Clone the repository into your home directory ```~/```
- add the folowing code to your ```.bashrc``` or ```.bash_profile```

```
if [ -f ~/GitCompletion/git-completion.bash ]; then
  source ~/GitCompletion/git-completion.bash
fi
if [ -f ~/GitCompletion/git-prompt.sh ]; then
  source ~/GitCompletion/git-prompt.sh
fi

GIT_PS1_SHOWDIRTYSTATE=true
export PS1='\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w$(__git_ps1)\[\033[m\]\$ '
```

- open a new console
