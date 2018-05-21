
```
fly -t lite set-pipeline -p elasticsearch-tile -c pipeline.yml -l secret.yml
fly -t lite unpause-pipeline -p elasticsearch-tile
```