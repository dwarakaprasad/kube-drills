1. Problem
  1. Create a pod named basic-pod running the nginx image.
  2. Verify if the pod is running.
  3. Delete the pod.

2. Problem
   1. Create a pod named named-pod running the nginx image with label running
   2. Verify if the pod is running.
   3. Delete the pod
  
3. Problem
   1. Create a pod named command-pod using the busybox image that echos I am running
   2. verify the log
   3. delete the pod
  
4. Problem
   1. Create a pod named not-good using busybox image and make it fail with a non zero return code.
   2. The container shoiuld be tried to be re-started
   3. See if it gets restarted and note the number of times
  
5. Problem
   1. Create a pod named nginx-port with image nginx and expose it in port 8080
   2. verify that its running
   3. delete the pod
