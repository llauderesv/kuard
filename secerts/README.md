# Secrets

Creating a secret using kubectl

`$ kubectl create secret generic kuard-tls \
  --from-file=kuard.crt \
  --from-file=kuard.key`