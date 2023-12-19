# help
git remote add origin url
git push --set-upstream origin branchname

.github/workflows
YAML or YML
name:Github Actions Demo
on:push
jops:
  Explore-Github-Actions
    runs-on:ubuntu-latest
    steps:
      -name:print the trigg
      run:echo "the jop was trig by ${{github.eventname}}." //share scrpit
