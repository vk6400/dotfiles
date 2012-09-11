kevinSuttle/Dotfiles
========

I present my humble list of dotfiles. If you haven't experienced the freedom that comes from versioning your dotfiles, check out Github's dedicated [dotfile page](http://dotfiles.github.com).

Big thanks to [@holman](http://twitter.com/holman) for the [inspiration](http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/),         
to [@mathias](http://twitter.com/mathias) for his [legendary collection](https://github.com/mathiasbynens/dotfiles/blob/master/.osx) of OSX dotfiles,    
to [@pengwynn](http://twitter.com/pengwynn) for his [dotfile](http://wynnnetherland.com/journal/dotfiles-discovery) [creativity](http://wynnnetherland.com/journal/dotfiles-discovery) and to     
[@tyrmored](http://twitter.com/tyrmored) for the [implemenation details](http://blog.sanctum.geek.nz/managing-dot-files-with-git/). 

## Sublime Text Config
Thanks to [@PaulIrish](http://twitter.com/paulirish) for this tip. Sublime doesn't ship knowing about *every* dotfile, so we can help it out a bit by editing it's Shell language configs. 

1. Go here in your Terminal of choice

    `cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/ShellScript/`

2. Edit the file '*Shell-Unix-Generic.tmLanguage*' by adding the following lines. 

[Paul's](https://github.com/paulirish/dotfiles#syntax-highlighting):

                <string>.aliases</string>
                <string>.bash_prompt</string>
                <string>.brew</string>
                <string>.exports</string>
                <string>.functions</string>
                <string>.git</string>
                <string>.gitattributes</string>
                <string>.gitconfig</string>
                <string>.gitignore</string>
                <string>.inputrc</string>
                <string>.osx</string>
                <string>.vim</string>
                <string>.vimrc</string>    

My additions:
                
                <string>.zshrc</string>
                <string>.zlogin</string>
                <string>.conf</string>
                <string>.screenrc</string>
                <string>.hushlogin</string>