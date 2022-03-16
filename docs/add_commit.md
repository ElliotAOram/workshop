```bash
git status  # Gives you the status of all the files in your local repository
git add .   # This will tell git that you want to add all changes to the next commit. 
            # You can be more specific with git add path/to/file/or/directory to add only a file or directory at a time.
            # e.g. git add ~/workshop/code
git commit -m "My hello world"  # This will tell git that we want to package all of the added files into a commit.
                                # The -m options means add a message. This is the text between the double quotes


# This pushes the branch back to github (the origin). 
# Up until now everything has been on your local machine except when we cloned the repository at the beginning. 
# The origin doesn't know about your branch or your code at this point so we have to tell it where to put our branch when we push it.
# The --set-upstream part of the command say push our branch to the origin with the branch name <your branch name>
git push --set-upstream origin <your branch name>
```
