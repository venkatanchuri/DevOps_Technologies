# Assume we are in your home directory
cd ~/

# Clone the repo from GitLab using the `--mirror` option
$ git clone --mirror git@your-gitlab-site.com:mario/my-repo.git

# Change into newly created repo directory
$ cd ~/my-repo.git

# Push to GitHub using the `--mirror` option.  The `--no-verify` option skips any hooks. 
$ git push --no-verify --mirror git@github.com:mario/my-repo.git

# Set push URL to the mirror location
$ git remote set-url --push origin git@github.com:mario/my-repo.git

# To periodically update the repo on GitHub with what you have in GitLab
git fetch -p origin
git push --no-verify --mirror
