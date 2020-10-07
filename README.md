# Replication-controller-Kubernetes
Created a sample replication controller yaml file in kubernetes.
Container pods were created using the nginx image used in the yaml file by availing AWS services.
These pods were exposed to the internet by creating a sample service yaml file.
nodeport is used to expose the container to internet. 
I have used nodeport: 31333  (NodePort range is 30000-32767)
Any nodeport in the available range mentioned above can be used.
