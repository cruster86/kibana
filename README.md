<details><summary>Состав проекта:</summary>

    ├── .gitlab-ci.yml
    ├── README.md     
    ├── deploy
    │   └── helm
    │       ├── Chart.yaml
    │       ├── conf
    │       │   ├── corp
    │       │   │   └── values.yaml
    │       │   ├── cpm
    │       │   │   └── values.yaml
    │       │   ├── cpm-dev
    │       │   │   └── values.yaml
    │       │   ├── sirius
    │       │   │   └── values.yaml
    │       │   └── univ
    │       │       └── values.yaml
    │       ├── templates
    │       │   ├── _helpers.tpl
    │       │   ├── deployment.yaml
    │       │   ├── service.yaml
    │       │   ├── secret.yaml
    │       │   └── ingress.yaml
    │       └── values.yaml
    └── scripts
        └── helm_deploy_and_wait.sh
</details>

<details><summary>Настройки:</summary>

  - Настройка параметров: `conf/${CLUSTER_NAME}/values.yaml`
</details>
