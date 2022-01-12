# MonSwarm
A Repository Containing Docker stack for Docker Swarm Setup


## Deploy
```bash
env $(cat stack.env | grep ^[A-Z] | xargs) docker stack deploy -c stack.yaml MonSwarm
```