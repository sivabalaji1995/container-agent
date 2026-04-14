First create the docker registry secrets using below command 

```
kubectl create secret docker-registry ghcr-secret \
  --docker-server=ghcr.io \
  --docker-username=sivabalaji1995 \
  --docker-password=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 \
  --docker-email=sivanimmakayala07@gmail.com
```

