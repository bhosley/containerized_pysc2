# containerized_pysc2
 Containerizing the PySC2 environment to run on a cluster


null  Normal  Scheduled    Successfully assigned ace-hub/e-bgbfbjbn-5ctsw-0 to ovechkin
2024-01-30T17:12:06Z  Normal  Pulled    Container image "docker.io/bitnami/git:2" already present on machine
2024-01-30T17:12:06Z  Normal  Created    Created container git-init
2024-01-30T17:12:06Z  Normal  Started    Started container git-init
2024-01-30T17:12:07Z  Normal  Pulled    Container image "reg.git.act3-ace.com/ace/hub/user-proxy:v0.5.5" already present on machine
2024-01-30T17:12:07Z  Normal  Created    Created container ssh-init
2024-01-30T17:12:07Z  Normal  Started    Started container ssh-init
2024-01-30T17:12:08Z  Normal  Pulling    Pulling image "git.antcenter.net:4567/nyielding/acehub-tensorflow-image:latest"
2024-01-30T17:12:08Z  Normal  Pulled    Successfully pulled image "git.antcenter.net:4567/nyielding/acehub-tensorflow-image:latest" in 226.04712ms
2024-01-30T17:12:08Z  Normal  Created    Created container main
2024-01-30T17:12:08Z  Normal  Started    Started container main
2024-01-30T17:12:08Z  Normal  Pulled    Container image "reg.git.act3-ace.com/ace/hub/user-proxy:v0.5.5" already present on machine
2024-01-30T17:12:08Z  Normal  Created    Created container tcp-proxy
2024-01-30T17:12:09Z  Normal  Started    Started container tcp-proxy
2024-01-30T17:12:09Z  Normal  Pulling    Pulling image "reg.git.act3-ace.com/ace/hub/label-sidecar:v1.0.0"
2024-01-30T17:12:09Z  Normal  Pulled    Successfully pulled image "reg.git.act3-ace.com/ace/hub/label-sidecar:v1.0.0" in 415.675404ms
2024-01-30T17:12:09Z  Normal  Created    Created container ace-label-sidecar
2024-01-30T17:12:10Z  Normal  Started    Started container ace-label-sidecar
2024-01-30T17:12:00Z  Normal  SuccessfulCreate    create Claim workspace-e-bgbfbjbn-5ctsw-0 Pod e-bgbfbjbn-5ctsw-0 in StatefulSet e-bgbfbjbn-5ctsw success
2024-01-30T17:12:00Z  Normal  SuccessfulCreate    create Pod e-bgbfbjbn-5ctsw-0 in StatefulSet e-bgbfbjbn-5ctsw successful
