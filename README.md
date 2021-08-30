# working-with-data-on-k8s

Challenge: Working with data on Kubernetes by Daniel Dersch (from "The Cloud Resume challenge" Forrest Brazeal)

## Goal

Deploy a workload to Kubernetes to pull public data and import it into an analysis tool.
For this specific project, we will be getting some sort of popularity score for a hashtag on Twitter (we will be using the #100DaysOfCloud).

## The current status

1. [Install local Kubernetes](./steps/1-install-k8s.md)

* [x] Install Kubernetes on the local machine
* [x] Install Kubernetes tools (kubectl, kubeadm)

2. Choose a public time series data set

Here is some inspiration

* [https://data.humdata.org](https://data.humdata.org)
* [https://www.data.gov/](https://www.data.gov/)
* [List of awesome public datasets](https://github.com/awesomedata/awesome-public-datasets)

1. Install Prometheus and Grafana

2. Write your importer program