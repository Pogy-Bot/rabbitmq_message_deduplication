**might not work if your erlang version is different than now**

```bash
git clone https://github.com/Pogy-Bot/rabbitmq_message_deduplication
cd rabbitmq_message_deduplication/
sudo mkdir -p /usr/lib/rabbitmq/plugins/
sudo cp * /usr/lib/rabbitmq/plugins/
sudo chmod 644 /usr/lib/rabbitmq/plugins/*
sudo rabbitmq-plugins enable rabbitmq_message_deduplication
```
