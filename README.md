# ODMB User Developments

This is a repositories to host the development code for individual ODMB developers,
featuring individual testbench implementations in the learning phase.

This repository is to be served as a code sharing / evaluation platfrom, where each
submodule is to be linked to the personal repo of the developers.

## To link to personal development repo add submodule

Under the main folder
```bash
git submodule add git@github.com:<username>/<reponame>.git <dirname>
```

And every time (or frequently) when new commit(s) were pushed to the linked repo,
you will need to come to this repo, do

```bash
cd <dirname>
git pull
git commit -a -m "Update with updates from <dirname>" 
git push
```
