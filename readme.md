# ajeffer's Bash Scripts
### Don't be `bash`full ... feel free to contribute ;-)


Here is the article that got me up and running on creating my own bash scripts to 

src: https://www.taniarascia.com/how-to-create-and-use-bash-scripts/


# Bash Script Usage 

## git-log
I find that for a quick scan the typical log is a bit verbose
this makes it more readable and easier to grab a particular hash

* I want to get a way to alias this as you have to call the full filename currently. We could just rename the file to `git-l` and get the shortened syntax as well 

## git-commit
If you find yourself frequently doing 
```git add . ```
``` git commit -m "feat: cool new fet" ```

then this is i nice shortcut to get that done quicly. 
Now you should NOT use this if you need to stage and commit specific files that you have changed. 

This also helps devs on your team follow a semantic commit message patter that I have found very usefule 

src: https://seesparkbox.com/foundry/semantic_commit_messages
