### Working with files is why Git exists - it makes it easier than saving because you can revert to previous files when you need to!

### We'll get there soon enough - but first let's work on __getting__ files you want. 

1. Let's say you want a fresh copy of a document you found - for example, [this repo!](https://github.com/be-ns/git-basics.git)
 * `git clone https://github.com/be-ns/git-basics.git` - creates a nifty copy from an online source - a la Github or Bitbucketgit  
 * you'll need to fork on Github in order to get a copy you can commit to and keep for yourself. 
2. If it's a local file you want (meaning on your own computer), you'll use `clone /path/to/repository`  
### Let's Talk resetting files 
1. `git checkout HEAD filename`: Discards changes in the working directory.
2. `git reset HEAD` filename: Unstages file changes in the staging area.
3. `git reset SHA`: Can be used to reset to a previous commit in your commit history
