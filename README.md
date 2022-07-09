# ideal-carnival
# Kubernetes - practice
# Taints and Toleration commit, 
yaml Name: nginx-tolerations-definition-NoSchedule.yaml 
The definition file has the example of how Taints and Toleration works in kubernetes with effect type as NoSchedule: There is No guarantee that the pod will be created on the Node if pod can tolerate the taint. [If there are other nodes without taints] 

yaml Name:  nginx-tolerations-definition-PreferNoSchedule.yaml:
This will prefer to create the pod to be created on the Node which matches the tolerations set on the pods and the taints on the Node, but again this also doesn't guarantee the pod creation on the Node.
