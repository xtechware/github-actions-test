To do git operations use remote
git remote add origin "https://$GITHUB_ACTOR:${{secrets.GITHUB_TOKEN}}@github.com/$GITHUB_REPOSITORY.git"