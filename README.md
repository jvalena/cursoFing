# Helm chart para desplegar una aplicación en 3 capas.
Este chart despliega [nginx] como front-end, [phpmyadmin] como capa de aplicación y [mysql] como base de datos.

Prerequisitos

- Kubernetes 1.27+
- helm 3.13+

## Instalando el chart
Para instalar el chart con el nombre my-chart ejecute:
```shell
$ helm install my-chart .
```

## Actualizar el chart
Para aplicar las modificaciones al chart my-chart realizadas en los archivos yaml
```shell
$ helm upgrade my-chart .
```

## Para desinstalar el chart
Desinstalar el deployment del chart con nombre my-chart:
```shell
$ helm uninstall my-chart
```

