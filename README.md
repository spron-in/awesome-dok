# Awesome Data on Kubernetes [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of Data on Kubernetes projects and solutions. It can be a project that allows you to provision your own data storage on k8s, or operator for databases, or great course or book about DoK.

Contributions to this list are welcome. Before submitting your suggestions, please review the [Contribution Guidelines](CONTRIBUTING.md) to ensure your entries meet the criteria. Add links through [pull requests](https://github.com/spron-in/awesome-dok/pulls) or create an [issue](https://github.com/spron-in/awesome-dok/issues) to start a discussion.

## Contents

- [Communities](#communities)
- [Databases](#databases)
- [Storage](#storage)
- [Reading materials](#reading)
- [Cources and videos](#courses-and-videos)
- [Adopters](#adopters)

## Communities

* [Data on Kubernetes](https://dok.community/) - facilitate the creation and sharing of best practices to help users advance in their DoK journey.
* [Percona Kubernetes Squad](https://percona.com/k8s) - newsletter, Ask-Me-Anything sessions and content tailored around Databases on k8s.

## Databases

### PostgreSQL

* [Bitnami Helm Chart](https://github.com/bitnami/charts/tree/main/bitnami/postgresql) - does its job to deploy PostgreSQL with a simple helm chart.
* [Zalando PostgreSQL Operator](https://github.com/zalando/postgres-operator) - one of the first Operators for PostgreSQL, open-source, used by [Zalando](https://www.zalando.com/) internally and loved by Community.
* [Percona Operator for PostgreSQL](https://github.com/percona/percona-postgresql-operator) - 100% open source operator from [Percona](https://percona.com) with HA, cross-cluster replication and many more features, has official support.
* [CloudNative PG](https://github.com/cloudnative-pg/cloudnative-pg) - an open source operator from [EnterpriseDB](https://www.enterprisedb.com/), donated to the community, lots of great features, flexible and does the job.
* [StackGres](https://github.com/ongres/stackgres) - an open source operator with web UI on top of it, supports 100+ extensions, written in Java.
* [CrunchyData PGO](https://github.com/CrunchyData/postgres-operator) - actively developed Operator from [CrunchyData](https://www.crunchydata.com/).
* [Tembo](https://github.com/tembo-io/tembo) - Operator powering PostgreSQL platform - [Tembo](https://tembo.io/) Cloud.
* [KubeDB](https://kubedb.com/kubernetes/databases/run-and-manage-postgres-on-kubernetes/) - swiss army knife Operator to manage various databases, including PostgreSQL.

### MySQL

* [Bitnami Helm Chart](https://github.com/bitnami/charts/tree/main/bitnami/mysql) - does its job to deploy MySQL with a simple helm chart.
* [Bitpoke MySQL Operator](https://github.com/bitpoke/mysql-operator) - known as PressLabs Operator, one of the first operators for MySQL, not actively developed.
* [Percona Operator for MySQL (PXC)](https://github.com/percona/percona-xtradb-cluster-operator) - 100% open source operator from [Percona](https://percona.com), based on [Percona XtraDB Cluster](https://www.percona.com/mysql/software/percona-xtradb-cluster).
* [Percona Operator for MySQL (PS)](https://github.com/percona/percona-server-mysql-operator) - another one for MySQL from Percona, but based on Percona Server for MySQL - provides group and async replication, currently in Alpha stage.
* [Oracle MySQL Operator](https://github.com/mysql/mysql-operator) - official operator from Oracle that installs MySQL InnoDB Cluster with group replication underneath.
* [MOCO](https://github.com/cybozu-go/moco) - manage MySQL clusters using GTID-based semi-synchronous replication.
* [KubeDB](https://kubedb.com/kubernetes/databases/run-and-manage-mysql-on-kubernetes/) - swiss army knife Operator to manage various databases, including MySQL. Also supports Percona XtraDB Cluster.
* [Vitess](https://github.com/vitessio/vitess) - k8s operator developed by [PlanetScale](https://planetscale.com/) to deploy and manage Vitess - middleware to implement sharding for MySQL.

### MongoDB

* [Bitnami Helm Chart](https://github.com/bitnami/charts/tree/master/bitnami/mongodb) - does its job to deploy MongoDB with a simple helm chart.
* [MongoDB Community Kubernetes Operator](https://github.com/mongodb/mongodb-kubernetes-operator) - open source solution from [MongoDB Inc.](https://www.mongodb.com/), has features for simple use cases.
* [MongoDB Enterprise Kubernetes Operator](https://www.mongodb.com/docs/kubernetes-operator/stable/) - an enterprise version from MongoDB Inc., feature rich, can be used for production-grade deployments.
* [Percona Operator for MongoDB](https://github.com/percona/percona-server-mongodb-operator) - 100% open source operator from [Percona](https://percona.com), feature rich and production-grade, powered by [Percona Server for MongoDB](https://www.percona.com/mongodb/software/percona-server-for-mongodb).
* [KubeDB](https://kubedb.com/kubernetes/databases/run-and-manage-mongodb-on-kubernetes/) - swiss army knife Operator to manage various databases, including MongoDB.

### Redis

* [KubeDB](https://kubedb.com/kubernetes/databases/run-and-manage-redis-on-kubernetes/) - wiss army knife Operator to manage various databases, including Redis.
* [Redis Operator](https://github.com/spotahome/redis-operator) - Open source solution, creates/configures/manages high availability redis with sentinel automatic failover atop Kubernetes.
* [Redis Enterprise Operator](https://docs.redis.com/latest/kubernetes/architecture/operator/) - Operator from Redis Ltd, delivers all production grade features for Redis.

### Other

* [Altinity Clickhouse Operator](https://github.com/Altinity/clickhouse-operator) - Creates, configures and manages ClickHouse clusters running on Kubernetes.
* [K8ssandra](https://k8ssandra.io/) - Platform for running Apache Cassandra® NoSQL database on Kubernetes.
* [Strimzi](https://strimzi.io/) - Provides a way to run an Apache Kafka cluster on Kubernetes in various deployment configurations.

## Storage

* [MinIO](https://github.com/minio/minio) - High Performance Object Storage compatible with Amazon S3 cloud storage service.
* [OpenEBS](https://github.com/openebs/openebs) - turns local Kubernetes worker nodes' storage into Persistent Volume Claims.
* [Rook](https://github.com/rook/rook) - open source cloud-native storage orchestrator for Kubernetes, providing the platform, framework, and support for Ceph storage.
* [Portworx](https://portworx.com/) - feature rich block storage for Kubernetes, can work with network attached volumes and local storage.
* [Lightbits](https://www.lightbitslabs.com/) - uses NVMe SSD powered machines to create network block storage that can be used in Kubernetes through PVCs.
* [Kubestr](https://kubestr.io/) - collection of tools to discover, validate and evaluate your kubernetes storage options.
* [NetApp Trident](https://netapp.io/persistent-storage-provisioner-for-kubernetes/) - Container Storage Interface that enables consumption and management of storage resources across NetApp platforms.

## Reading

### 

## Courses and Videos

## Adopters

List the end-user companies who adopted Data on Kubernetes. Vendor agnostic section, mention only the technology in use.
