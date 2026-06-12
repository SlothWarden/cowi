#Cow interactive
This is a simple bash file that will create a interactive experience for cowsay!
It requires cowsay and lolcat(if you plan on using the feature).

##How to run
To run it all you have to do is run the following command:
source <(curl -s https://slothwarden.github.io/repo-for-resources/cows.sh)
##Simplifying it
If you want to make it easier to type do this for a zsh shell:
nano .zshrc
Then make sure to find a spot where it won't hurt other configurations, like sdkman if you have it
Then simply right "alias cowi="source <(curl -s https://slothwarden.github.io/repo-for-resources/cows.sh)"
After that save your changes, once your back into the terminal type source ~/.zshrc
And you're done! To run the script type cowi
