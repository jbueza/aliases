## Services
<pre><code>
alias mysqlstart='sudo /opt/local/lib/mysql5/bin/mysqld_safe &' 
alias mysqlstop='sudo killall mysqld'

alias apachedit='mate /opt/local/apache2/conf/httpd.conf'
alias apachestop='sudo /opt/local/apache2/bin/apachectl stop'
alias apachestart='sudo /opt/local/apache2/bin/apachectl restart'
</code></pre>

## General

<pre><code>
alias ll='ls -al'
alias search=grep
alias ..='cd ..'
alias ...='cd ../..'
alias rm='rm -i'
alias df='df -h'

alias glo='git log --oneline --decorate'
alias gst='git status'
alias gci='git commit'
alias gp='git push'
alias gpom='git pull origin master'
alias gco='git checkout'
alias gl='git pull'
alias gd='git diff'
alias gb='git branch'
alias gba='git branch -a'
alias gbd='git branch -d'

alias sup='svn up'
alias sci='svn ci'
alias sad='svn add'
alias sme='svn merge'

alias finder='open -a Finder'
alias fox='open -a Firefox'
</code></pre>