# Manage Two GitHub repositories

## Add a remote
```
# show current remotes
git remote -v

# add a new remote
git remote add origin git@github.com:you/private-repo.git

# add another remote (e.g., your public repo)
git remote add public git@github.com:you/public-repo.git

# verify
git remote -v
```

## Push to public repository
```
git push public <private_branch>:<public_branch>
```