# FROM rabbitmq:3.8.14
FROM rabbitmq:3.8.14-management
RUN rabbitmq-plugins enable autocluster --offline
RUN rabbitmq-plugins --offline enable rabbitmq_peer_discovery_consul
