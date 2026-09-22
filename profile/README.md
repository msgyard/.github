Independent, community-built tools for message brokers — authentication, access analytics and day-to-day operations. Every tool runs on unmodified official releases, works on its own, and is free to use.

| Project | What it does | Status |
|---|---|---|
| [rabbitmq-auth-backend-aoptoken](https://github.com/msgyard/rabbitmq-auth-backend-aoptoken) | RabbitMQ auth backend: log in with a pre-issued signed token alongside ordinary passwords, with an audit event for every verified token | Released |
| [rabbitmq-access-insight](https://github.com/msgyard/rabbitmq-access-insight) | RabbitMQ plugin for access analytics: who connects, from where, how they authenticate, which accounts are unused — [website](https://msgyard.bitey.ai/rabbitmq-access-insight/) | Released |
| access-insight-server | Optional broker-neutral service for long-term history, cross-cluster reports and event forwarding | Planned |
| access-insight-spec | The shared API, record format and access event convention | Planned |

Plugins and specifications are licensed under MPL-2.0, standalone services under AGPL-3.0. Contributions use a DCO sign-off (`git commit -s`).

More at [msgyard.bitey.ai](https://msgyard.bitey.ai).

<sub>msgyard is an independent community project, not affiliated with, endorsed or sponsored by Broadcom or the RabbitMQ team. RabbitMQ is a trademark of Broadcom Inc. and its subsidiaries.</sub>
