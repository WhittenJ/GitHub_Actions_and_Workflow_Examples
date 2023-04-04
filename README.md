# GitHub Actions and Workflow Examples

The purpose of this repo is to keep track of the different ways to approach and access GitHub workflows and actions.  Also to serve as a storage repo for generalized GitHub workflows that I have developed.

One of the largest things to note is for `template_docker` and `template_script`.  The *.sh files must be made executable, `chmod +x [filename.sh]`

```
git update-index --chmod=+x .github/actions/template_script/goodbye.sh
git add .
git commit -m "Fix executable"
git push
```
