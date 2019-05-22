# MongoDB Sharded Rancher Template

Template para crear un shard de mongoDB

## Instalación

Dentro de Rancher UI **Admin/Settings** Agregar un nuevo catálogo personalizado:

| Name            | URL                                                   | Branch |
| --------------- | ----------------------------------------------------- | ------ |
| Shard MongoDB-4 | https://github.com/spedroza82/mongodb4_Sharded-rancher-template.git | master |

## Docker Images

* **mongo-config**:
Imagen Docker usada como un sidekick container para proveer scripts y secrets
