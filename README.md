# helm-prometheus-pve-exporter

Base on docker https://github.com/prometheus-pve/prometheus-pve-exporter

## Configuration
The following table lists the configurable parameters of the helm-prometheus-pve-exporter chart and their default values.

| Parameter                                    | Description                                                                                  | Default                                              |
| -------------------------------------------- | -------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| `image.repository`                                      |  image repository.                                                                    | `prompve/prometheus-pve-exporter`                                              |
| `image.tag`                                   |  image tag.                                                                           | `2.0.3`                                             |
| `pve.name`                              | User name for Proxmox node                                                                  | `prometheus@pve`                                            |
| `pve.password`                                | Password for Proxmox node                                                                         | `sEcr3T!`     