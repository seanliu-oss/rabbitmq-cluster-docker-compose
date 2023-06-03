# rabbitmq-cluster-docker-compose
Sample docker compose for creating a 3 node rabbitmq cluster
- Cluster name: rabbit@test-ha
- Cluster node names: rabbitmq1, rabbitmq2, rabbitmq3
- Enabled plugins: management
- Port forwarding
- 25001, 25002, 25003 to 5672 for rabbitmq1, rabbitmq2, rabbitmq3, respectively.
- 35001, 35002, 25003 to 15672  for rabbitmq1, rabbitmq2, rabbitmq3, respectively.

- Run "docker-compose up -d" to start cluster.
- Run "doker-compose build" if you change docker config files

