#USAGE
1. Copy the script and place it in your-repo/.git/hooks/prepare-commit-msg
2. Make it an executable file using the chmod command: chmod +x your-repo/.git/hooks/prepare-commit-msg

* The branch name must be something like `tg-123-my-branch-name` or `tg-123-tg-456-my-branch-name`, the prepare-commit-msg will
generate the [TG-123] or [TG-123 | TG-456] in your commit message. You hust have to commit like `git commit -m 'My awesome feature'`
