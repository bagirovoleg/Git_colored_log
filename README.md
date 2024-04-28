# Git colored log
> [!NOTE]
> Create a alias for colored logt.

> [!TIP]
> git config --global alias.logshort "log --pretty=format:'%C(yellow)%h %Cred%ad %Creset| %Cgreen%s%d %Cblue(%an)' --graph --date=short".
> 	logshort = log --pretty=format:'%h %ad | %s%d (%an)' --graph --date=short
>	  logcolor = log --pretty=format:'%C(red)%h %C(white)- %C(magenta)%ad:%C(yellow)%d %C(cyan)| %C(white)%s %C(cyan)| %C(cyan)(%cr) %Cblue(%an)' --graph --date=short

> [!IMPORTANT]
> code ~/.gitconfig.

![ ](https://github.com/bagirovoleg/Git_colored_log/blob/main/COLOR_LOG.png)
