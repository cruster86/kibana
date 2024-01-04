### Структура репозитория

Настройки для кластеров находятся в: `deplo/helm/conf/${CLUSTER_NAME}/values.yaml`

Конфигурация деплоя находится в: `.gitlab-ci.yaml`

Особенности установки:

  - RBAC-манифесты не применяются
  - параметры доступа к elasticsearch задаются через deployment, дополнительные configmap'ы не используются 

---

Upstream проект: https://github.com/elastic/helm-charts/tree/main/kibana