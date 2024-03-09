__Guide to setup:__
Link [here](https://cloud.google.com/architecture/distributed-load-testing-using-gke#proxy-ssh-tunnel)

- Follow the proxy and ssh option to access locust UI
- Scale num of workers
<br/>
  `kubectl scale deployment/locust-worker --replicas=20`
