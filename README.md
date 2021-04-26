# Elastica from facebook production data
Because facebook love data, we love it too...

## Setup

### To install
- Docker-compose (& docker)
- Logstash

Execute `docker-compose up -d` to setup elasticsearch environment.

### Docker info
Kibana url : http://localhost:5601
Main elasticsearch instance : http://localhost:9200/

### Load data

Copy/paste `Kibana_Dev-tools_Console.txt` content to kibana dev tools console & run create index command.

Update logstash.config with your own config.

Run
```bash
$ sudo logstash -f logstash.config
```

Wait 5 minutes and kill command with (ctrl+C) because logstash still watching file changes

## Where can I found facebook leak data
Ask me or make som research on google
