#Git bash assignment

####Alex McClymont

##1. When should you use git for a project?

*When multiple people are working on one code document 
*When you want your code to be accessible remotely
*When you want to save previous versions of your code that you can revert to if you make a mistake later on.
*Keeping track of changes in your code

##2. What types of files should be saved or not saved to a git repository?

Saved: project code, data files, readme descriptions

Not saved: sensitive information including passwords, anything that should not be 
publicly accessible

##3. What are the commands to undo a commit?

'git checkout HEAD ~1'

*OR*

'git checkout {commit identifier}'

*OR*

'git revert {commit identifier}'

##4. How do you fix being in a detached HEAD state?

'git checkout master'

##5a. Pros and cons of using git for your research project

  *Pros: a remote repository for your codes that will save all versions of your code 
in 
case you want to revert to a previous version or you lose all your local code in a 
horrible incident 

  *Cons: doesn't support large data files 

##5b: Pros and cons of hosting a project in a public repository

  *Pros: people can collaborate and fix issues in your code, make suggestions

  *Cons: anyone can see your code and use it for their own purposes

##5c: Pros and cons of hosting a project in a private repository

  *Pros: All the benefits of hosting in a public repository, but no one can see it

  *Cons: costs $$
