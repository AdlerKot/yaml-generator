# Table with data of promts to generate manifests
| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| app.yaml | Create app.yaml with pod name app with image gcr.io/week5-434112/demo:v2.0.0 and http port 8000, labels run demo and app demo | Pod with lables, image and port 8000  | - [app.yaml](https://raw.githubusercontent.com/AdlerKot/yaml-generator/main/yaml/app.yaml) |
| app-livenessProbe.yaml | pod name app with livness probe to check 8080 port with image gcr.io/week5-434112/demo:v2.0.0 | Add probes to check 8080 port | - [app-livenessProbe.yaml](https://raw.githubusercontent.com/AdlerKot/yaml-generator/main/yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | pod name app with livness & readiness probe to check 8080 port with image gcr.io/week5-434112/demo:v2.0.0 | Readiness probes to check pod | - [app-readinessProbe.yaml](https://raw.githubusercontent.com/AdlerKot/yaml-generator/main/yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | pod name app with 8080 port with image gcr.io/week5-434112/demo:v2.0.0 and mount data-volume to /data/ | mount data-volume to pod | - [app-volumeMounts.yaml](https://raw.githubusercontent.com/AdlerKot/yaml-generator/main/yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml | Cronjob to print Hi-there every 1 min | Print some message every 1 minute | - [app-cronjob.yaml](https://raw.githubusercontent.com/AdlerKot/yaml-generator/main/yaml/app-cronjob.yaml) |
| app-job.yaml | job with rsync some data to /data/input | rsync data from source to destination folder | - [app-job.yaml](https://raw.githubusercontent.com/AdlerKot/yaml-generator/main/yaml/app-job.yaml) |
| app-multicontainer.yaml |  Create pod name app with 2 containers, image gcr.io/week5-434112/demo:v2.0.0 and http port 8000, 9090, liveness & readiness probes labels run demo and app demo | 2 containers with differents ports | - [app-multicontainer.yaml](https://raw.githubusercontent.com/AdlerKot/yaml-generator/main/yaml/app-multicontainer.yaml) |
| app-resources.yaml | pod name app with 8080 port with image gcr.io/week5-434112/demo:v2.0.0, liveness readiness probes and resources: requests 50m 50Mi, limits 100m 100Mi  | Add Limits to pod | - [app-resources.yaml](https://raw.githubusercontent.com/AdlerKot/yaml-generator/main/yaml/app-resources.yaml) |
| app-secret-env.yaml | pod name app with 8080 port with image gcr.io/week5-434112/demo:v2.0.0, secrets secret1 username1 secret2 username2 | Pod with secrets | - [app-secret-env.yaml](https://raw.githubusercontent.com/AdlerKot/yaml-generator/main/yaml/app-secret-env.yaml) |
### End















