## k8s sample
## [中文文档](http://docs.kubernetes.org.cn/)
## [kubernetes-handbook](https://jimmysong.io/kubernetes-handbook/)

### create docker registry key
```bash
kubectl create secret docker-registry docker-registry-key-jiaofuyun-1 --docker-server=registry.cn-beijing.ali
yuncs.com --docker-username={username} --docker-password={pwd} --docker-email={email}
```