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

## git-branch
Using the git branch -a command will give you all of your local branches and give you an indicator which branch you are on ... well if you have 100+ branches then its often times not useful. 
// Lets not get in to why there are 100+ branches 

```git-branch```

returns just the name of the current branch you are on 

## kill-port 
`kill-port 8080`
If you running node and it doesn't shut down properly then you can get processes stuck running on port 3000 or 8080 ... you can use this command to kill the processes without having to remember the individual commands