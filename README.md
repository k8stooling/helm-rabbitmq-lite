# helm-rabbitmq-lite
A lite helm chart to install rabbitmq

Bitnami helm chart is great, just as the rabbitmq operator.

But what if you need only a simple installation without too much hassle?

# TODO

- cluster initialization
- on node 1 there is an error popping up from time to time

```
 [error] <0.5206.0> ** Connection attempt from node 'rabbit@rabbitmq-0' rejected. Invalid challenge reply. **
```

Although erlang cookie is consistent. Despite this error, message queue and cluster works as expected.