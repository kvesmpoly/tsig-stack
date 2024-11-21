# TIG Stack Deployment with ArgoCD

Este proyecto contiene los manifiestos necesarios para desplegar un stack TIG (Telegraf, InfluxDB, Grafana) en Kubernetes utilizando ArgoCD.

## Estructura del Proyecto

- `argo-application.yaml`: Define la aplicación de ArgoCD.
- `influxdb/`: Manifiestos de InfluxDB.
- `telegraf/`: Manifiestos y configuración de Telegraf.
- `grafana/`: Manifiestos de Grafana.
- `README.md`: Este archivo.

## Pasos para Desplegar

1. Clonar el repositorio.
2. Revisar y, si es necesario, modificar los manifiestos para adaptarlos a tu entorno.
3. Subir los cambios al repositorio Git.
4. Aplicar `argo-application.yaml` en el clúster.
5. Acceder a ArgoCD para verificar que la aplicación se sincroniza correctamente.

## Configuración de Dispositivos Cisco IOS XR

Asegúrate de configurar tus dispositivos para enviar telemetría a Telegraf según las instrucciones proporcionadas.

## Contacto

kmarmol@telconet.net