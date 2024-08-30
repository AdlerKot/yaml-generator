| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| app.yaml | Create app.yaml with pod name app with image gcr.io/week5-434112/demo:v2.0.0 and http port 8000, labels run demo and app demo | Pod with lables, image and port 8000  | --- |
| app-livenessProbe.yaml | pod name app with livness probe to check 8080 port with image gcr.io/week5-434112/demo:v2.0.0 | Add probes to check 8080 port | --- |
| app-readinessProbe.yaml | pod name app with livness & readiness probe to check 8080 port with image gcr.io/week5-434112/demo:v2.0.0 | Readiness probes to check pod | --- |
| app-volumeMounts.yaml | pod name app with 8080 port with image gcr.io/week5-434112/demo:v2.0.0 and mount data-volume to /data/ | mount data-volume to pod | --- |
| app-cronjob.yaml | Cronjob to print Hi-there every 1 min | Print some message every 1 minute | --- |
| app-job.yaml | job with rsync some data to /data/input | rsync data from source to destination folder | --- |
| app-multicontainer.yaml |  Create pod name app with 2 containers, image gcr.io/week5-434112/demo:v2.0.0 and http port 8000, 9090, liveness & readiness probes labels run demo and app demo | 2 containers with differents ports | --- |
| app-resources.yaml | pod name app with 8080 port with image gcr.io/week5-434112/demo:v2.0.0, liveness readiness probes and resources: requests 50m 50Mi, limits 100m 100Mi  | Add Limits to pod | --- |
| app-secret-env.yaml | pod name app with 8080 port with image gcr.io/week5-434112/demo:v2.0.0, secrets secret1 username1 secret2 username2 | Pod with secrets | --- |