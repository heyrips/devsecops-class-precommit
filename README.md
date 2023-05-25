# Precommit config

This validate any credentials or compliance violations in the code

## Commands

```
- git add .
- git commit "test"
- Changes will not commit until you fix the issues
- git push
```
#Install 
- https://pre-commit.com/
- * pre-commit --version
- -Add a pre-commit configuration
- * create a file named .pre-commit-config.yaml and copy the configuration
- install the git hook scripts
- * pre-commit install
- (optional) run against all the files
- *pre-commit run --all-files