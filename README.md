# HelloCharts

Helm chart for hello app.

## Resources

- [Docker Image](https://hub.docker.com/repository/docker/ahmedaidev/hello)
- [Helm Chart Repo](https://github.com/ahmedaidev/hellocharts)

## Prerequisites

- [git](https://git-scm.com/)
- [Helm](https://helm.sh/)

## Run

```
git clone https://github.com/ahmedaidev/devops-task
cd devops-task
helm install hello ./hellochart-1.0.1.tgz
```

OR

```
helm repo add hellocharts https://ahmedaidev.github.io/hellocharts/
helm install hello hellocharts/hellochart
```

