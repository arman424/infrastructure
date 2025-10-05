# Running RabbitMQ

## Prerequisites

- Docker installed and running

## Steps

1. **Clone this repository** (if not already done):

   ```sh
   git clone https://github.com/arman424/infrastructure
   cd infrastructure
   ```

2. **Start RabbitMQ using Docker:**

   ```sh
   docker compose up -d
   ```

   - The management UI will be available at [http://localhost:15672](http://localhost:15672)
   - Default username/password: `guest` / `guest`

3. **Stop RabbitMQ:**

   ```sh
   docker stop rabbitmq
   docker rm rabbitmq
   ```

## Notes

- The default AMQP port is `5672`.
- The management UI port is `15672`.

