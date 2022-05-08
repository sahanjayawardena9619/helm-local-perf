# helm-local-perf
Helm Chart Tree
    helm_perf_charts
        - index.yaml
        - <all other packages>

1. Created Directory - helm_perf_charts
2. Create Packages - helm package .\1-jenkins\  -d <destination> .\helm_perf_charts\
3. Add Index Files to store the Charts Metadata - helm repo index <destination>

Kind Container List Temp
    e2ea13b3b3e4, 5d00dd524e43, 297425fd4365