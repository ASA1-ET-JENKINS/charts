# Chart Mirror

## Add chart

package a chart folder and add it to the docs folder. Reindex our helm repo and push all. finish
```
$ helm package bitnami/redis
$ mv redis-19.6.4.tgz docs
$ helm repo index docs --url https://asa1-et-jenkins.github.io/charts
$ git add -i
$ git commit -av
$ git push origin master
```
