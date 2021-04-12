# MySQL server source
https://github.com/bitnami/charts/tree/master/bitnami/mysql

# PostgreSQL server source
https://github.com/bitnami/charts/tree/master/bitnami/postgresql

# MongoDB server source
https://github.com/bitnami/charts/tree/master/bitnami/mongodb

# Configuring Bitnami Helm charts
1. Install helm version 3
2. helm repo add bitnami https://charts.bitnami.com/bitnami

## Install MySQL database service
1. helm install db1 bitnami/mysql -f mysql/values.yaml

## Install PostgreSQL database service
1. helm install db2 bitnami/postgresql -f postgresql/values.yaml

## Install MongoDB database service
1. helm install db3 bitnami/mongodb -f mongodb/values.yaml
