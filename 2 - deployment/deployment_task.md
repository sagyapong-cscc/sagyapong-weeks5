# Deployment Worksheet

__Task 2, step 6: After completing step 5 of task 2, what do you notice about the `ReplicaSet` - what is this used for?__
hint: use ` kubectcl get rs --show-labels`

```
it list  the replicaSets in the kubernetes cluster and displays their labels
```

__Task 2, step 7: what command did you use to scale the deployment?__

```
kubectl scale deployment nginx-deployment --replicas=3

```

__Task 3, step 2: Why are there two replica sets but only one deployment?__

```
because it is showing the history
```

__Task 3, step 6: What command did you use to roll back the deployment?__

```
kubectl rollout undo  deployment nginx-deployment --to-revision=1

```
