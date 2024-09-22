# confluent-kubernetes

# Deployment
Create jass config pass through secret
kubectl create -n operator secret generic pass-through-internal --from-file=oauth-jass.conf=oauth_jass_internal.txt
kubectl create -n operator secret generic pass-through-repl --from-file=oauth-jass.conf=oauth_jass_repl.txt
