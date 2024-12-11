# remote-test-1 (is the source)
# remote-test-2 (is the origin)
git branch --set-upstream-to=origin/24-issue 24-issue
git pull <внешний-репозиторий> <ветка>
git config pull.rebase false  # merge
git config --list (видим pull.rebase=false)