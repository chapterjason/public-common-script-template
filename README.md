
# public-common-script-template

This is a template for common scripts that can be used in any project.

## Installation

Ensure you have the following lines in your `.gitignore` file:

```gitignore
# Ignore all subdirectories under scripts (script-template folders)
scripts/*/
# Except for the hooks folder (allows to hook into several script-template scripts)
!scripts/hooks/
# Recursively ignore any file ending with .local.sh (local files which you wont want to commit)
scripts/*.local.sh
scripts/**/*.local.sh
```

```bash
git clone --depth 1 -b "master" "git@github.com:chapterjason/public-common-script-template.git" "scripts/public-common"
rm -rf "./scripts/public-common/.git"
```
