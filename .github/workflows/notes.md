To do git operations use remotes:  
git remote add origin `"https://$GITHUB_ACTOR:${{secrets.GITHUB_TOKEN}}@github.com/$GITHUB_REPOSITORY.git"`

The ${{ }} syntax defines an expression  
You can also use the `if` conditional on e.g. steps to control execution  
Common operators are also supported  
See functions also https://docs.github.com/en/actions/learn-github-actions/expressions#functions  
See here for more info https://docs.github.com/en/actions/learn-github-actions/expressions  

Contexts contain elements that you can use in your workflows, e.g. secrets,  you access them in expressions  
See here for more info https://docs.github.com/en/actions/learn-github-actions/contexts  