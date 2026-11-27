# ansible-rabbitmq

Setups RabbitMQ.

## Requirements

- `ansible-core` 2.19 or newer.
- The `community.rabbitmq` collection.

### Example playbook
```yaml
---
- hosts: myserver
  roles:
    - role: sunfoxcz.rabbitmq
```

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
