# MongoDB Sharded Rancher

Shard MongoDB Rancher Template

## Install

Dentro de Rancher UI **Admin/Settings** Agregar un nuevo catálogo personalizado:

| Name            | URL                                                   | Branch |
| --------------- | ----------------------------------------------------- | ------ |
| Shard MongoDB-4 | https://github.com/spedroza82/*.git | master |

## Templates

* **mongodb**: MongoDB Sharded for production environment

## Docker Images

* **mongo-config**:
Docker image used as sidekick container of all mongodb containers to provide secrets and scripts.
