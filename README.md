# k8-task2

Create YAML formatted Kubernetes manifests for below tasks and push them to your GitHub repository

A)Create a Replicaset off of nginx container with 3 replicasExpose Replicaset at port 81, use NodePortservice, call it "k8-service"

B)Create a ReplicationController"jenkins-test", expose it with NodePort service. Service should listen on port 80, name of the service has to be "jenkins-svc".Note: use jenkins image for the above task

C)Run a single instance of Pod in every node of Kubernetes cluster with ubuntuimage. Do not override any taints currently in place. Use DaemonSets to complete this task and use "ubuntu-ds"as DaemonSet name.

D)Check to see how many nodes are ready (not including nodes tainted NoSchedule)

E)Create a ReplicaSetas follows:•Name: nginx-dns•Pods running as a part of this ReplicaSet should use the nginx image•Exposed via a service: nginx-dns
