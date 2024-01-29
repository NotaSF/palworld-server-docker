# Setup Palworld in kubernetes

Use the following commands to setup this Palworld container in Kubernetes:

* `kubectl apply -f pvc.yaml`
* `kubectl apply -f configmap.yaml`
* `kubectl apply -f secret.yaml`
* `kubectl apply -f service.yaml`
* `kubectl apply -f deployment.yaml`


Use the folllowing commands to setup a daily reboot Cronjob in Kubernetes:

* `cd cronjob-reboot`
* `kubectl apply -f cm.yaml`
* `kubectl apply -f role.yaml`
* `kubectl apply -f rolebinding.yaml`
* `kubectl apply -f serviceaccount.yaml`
* `kubectl apply -f cronjob.yaml`
