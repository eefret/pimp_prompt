# Pimp Prompt
> v0.1

Bash prompt pimp script

Want to have a beautifull, colorful and informativ bash prompt, just import this file into your home directory and add it to your .bashrc file adding the following to the bottom of the file:

    #CUSTOM PROMPT
    #if the file exists insert it here
    if [ -f ~/.prompt_custom ]; then
        . ~/.prompt_custom
    fi

And it will automatically change it to this:

![Alt text]

#### Features

* Git branch displaying
* Git diff display
* Dynamic Go version display (useful for gvm)


#### How to

If you have any more questions please read my blog [post](http://eefret.me/modifying-and-pimping-bash-prompt/). 
