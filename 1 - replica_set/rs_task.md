# ReplicaSet Worksheet:

__Task 1, step 7: Enter the command you used for scaling the replica set:__
```
kubectl scale replicaset nginx-replica --replicas=3

```

__Task 1, step 9: What happened after applying another pod with matching selectors as the ReplicaSet?__
```
kubectl get pods -l app_name=nginx,env=dev

```
