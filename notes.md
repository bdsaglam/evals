## Setup

```
pip install -e .
```

### Snowflake

https://snowflake.localstack.cloud/getting-started/installation/

1. Set `LOCALSTACK_AUTH_TOKEN` in `.env`.

2. Run localstack:
```
docker compose up -d
```

3. Set `SNOWFLAKE_ACCOUNT`, `SNOWFLAKE_DATABASE`, `SNOWFLAKE_USERNAME`, and `SNOWFLAKE_PASSWORD` in `.env`.

## Usage

```sh
EVALS_THREADS=4 oaievalset deepseek-r1-llama-8b test
```