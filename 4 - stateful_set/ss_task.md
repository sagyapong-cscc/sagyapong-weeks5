# StatefulSet Worksheet

__Task 5, step 3: Describe what happened and what you noticed about the pods and the volumes for them.__

```
Three voulmes and three pods were created. the pods were in pending states waiting for the persistentvolume claim to be created out of the persistentvolume.
```

__Task 5, step 4: Did anything change? Why or why not?__

```
There wasn't any change. the version number didn't changed to version 2. this is because updateStrategy type is OnDelete and it can only be updated when the pod is manually deleted.
```

__Task 5, step 6: What happened and why?__

```
The delete pod version number was updated from version 1 to 2 whiles the other remain on version 1. 
```

__Task 5, step 9: What happens this time?__

```
The verion numbers for all three pods were updated to version 3 without manually deleting the pods
```

__Task 5, step 11: Repeat step 10. Was everything deleted? Why or why not?__

```
All three pods  except the pvc and pv were deleted.
```
