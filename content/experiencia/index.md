# Experiencia
---

### Instituto de automática e informática industrial (Ai2)

Diciembre 2022 - Julio 2023

Durante mi estancia en el Instituto Ai2, tuve el placer de desarrollar tareas mayoritariamente enfocadas al Devops y a la Administración de Sistemas.

- Contenerización y despliegue de microservicios mediante Deployments, Services e Ingress en Kubernetes (simulaciones de robots y hosting de páginas webs).

- Despliegue y configuración de una instancia de Jenkins.
- Creación de una pipeline en Jenkins que dado un commit a un repositorio de Git, generaba una imagen nueva, y actualizaba el pod que la ejecutaba.
- Creación de un dashboard de Grafana que, mediante el scraper de métricas de Prometheus, permitía visualizar el estado de la memoria, el uso de cpu y de gpu de cada uno de los nodos del clúster.
- Desarrollo de mi TFM: "Implementación de un sistema homogéneo de autenticación y autorización de un clúster de Kubernetes en el ámbito de la investigación".
    - En este Trabajo de Fin de Master, fui capaz de desarrollar un sistema de autenticación y autorización de Single Sign-On (SSO) permitiendo a los usuarios que puedan utilizar las credenciales de la UPV (Universitat Politècnica de València), para un clúster de Kubernetes de uso computacional. Se desarrolló autenticación a nivel de microservicios y a nivel del CLI de Kubernetes (kubectl), mediante el uso de Keycloak y Oauth2 Proxy, y autorización de uso de recursos del clúster mediante roles de RBAC.

Tecnologías: Docker, Kubernetes, Keycloak, Oauth2 Proxy, Helm, Jenkins, Grafana, Prometheus.