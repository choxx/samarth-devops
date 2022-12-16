Devops for Samarth

## Posthog
Zookeeper cleanup logs: https://github.com/apache/zookeeper/blob/master/zookeeper-docs/src/main/resources/markdown/zookeeperTools.md#zkcleanupsh

Example cron added on docker stack service: `7 20 * * * docker exec -it posthog1_zookeeper_1 /apache-zookeeper-3.7.0-bin/bin/zkCleanup.sh -n 5 >/dev/null`