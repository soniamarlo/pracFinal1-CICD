# CI/CD Pipeline for Laravel Kubernetes Example App

Este repositorio contiene un pipeline de CI/CD configurado con CircleCI para la aplicación Laravel tomada del repositorio [laravel-kubernetes-example-app](https://github.com/chris-cmsoft/laravel-kubernetes-example-app.git).

## Descripción

La finalidad de este proyecto es implementar un pipeline de integración y despliegue continuo (CI/CD) para la aplicación de ejemplo en Laravel que se despliega en un clúster de Kubernetes. El pipeline realiza las siguientes tareas:

- Instalación de dependencias
- Ejecución de pruebas
- Análisis de cobertura de código
- Generación y publicación de artefactos
- Escaneo de seguridad con herramientas como SonarCloud y GitGuardian
- Despliegue en Kubernetes usando ArgoCD

## Créditos

Todos los derechos de la aplicación Laravel pertenecen a [Chris](https://github.com/chris-cmsoft), autor del repositorio original. Este proyecto únicamente adapta su aplicación para propósitos educativos en un entorno de CI/CD.

## Requisitos

Para ejecutar este pipeline, asegúrate de tener configurado lo siguiente:

- Cuenta en CircleCI
- Token de autenticación para GitHub (para publicar artefactos)
- Configuración de ArgoCD para despliegues automáticos en Kubernetes

## Licencia

Este proyecto no modifica la aplicación original y solo realiza configuraciones sobre el pipeline CI/CD para fines educativos. La propiedad intelectual de la aplicación original es de [Chris](https://github.com/chris-cmsoft).
