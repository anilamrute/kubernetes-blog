# Kubernetes Components: Worker/Data Plane and Master/Control Plane

![Diagram](K8s.png)


## Worker/Data Plane Components:
1. **Kubelet**: Ensures pods are always running and provides information if there’s a failure.
2. **Kube-proxy**: Handles networking, IP addresses, and load balancing.
3. **Container Runtime**: Allows containers to run on Kubernetes (e.g., Docker, containerd, CRI-O).

## Master/Control Plane Components:
1. **API Server**: Exposes the Kubernetes API and handles external requests.
2. **Scheduler**: Schedules pods onto nodes based on resource availability.
3. **etcd**: Stores cluster data in a key-value format.
4. **Controller Manager**: Manages controllers to maintain the desired cluster state.
5. **Cloud Controller Manager**: Integrates with cloud providers and supports custom implementations.
