# Lemoncode1 Git lab
Laboratory made for quick and simple git practice. (Repo title has a typo, my bad)

## Requirements:
Installing Git - DONE
Using a GitHub account - DONE

## Objectives:
__1. Create a local repository__
- I made a folder for this project, then I opened git bash and moved to it via *cd Downloads/LEMONCODE/REPOS/*
- Then I made a folder right there using *mkdir Lemoncode1-Git_lab*

__2. Upload the repository to GitHub__
- I used git init to create a repository there, though I realized right after that I should just use *git clone (url)* to create the repo locally and did so right away.
- I made sure everything was working properly on GitHub

__3. Commit and Push__
- I created a file via *touch TestFile.txt* and wrote in it through *nano TestFile.txt*
- Then I staged it using *git add .*
- And I finally made my first commit for these Lemoncode assignments via *git commit -m "Uploading TestFile.txt to GitHub"*

__4. Creating a branch__
- I made a new branch using *git branch development*
- Then I swapped branches through *git checkout development*
- I edited TestFile.txt again...
- And I ran *git add .* and *git commit -m "Modified TestFile.txt"*, again.

__5. Merging__
- I swapped back into main through *checkout main*
- Then I ran *merge development*. It wasn't complicated, just a clean fast forward.

Lastly, I edited this very file you are reading. Good day
