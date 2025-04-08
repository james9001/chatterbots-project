# chatterbots-project

Documentation under construction!

## Getting Started

- Create `./localdev/data` directory
- Once containers are running, open the Chatterbots Frontend and navigate to Settings. Configure the "OpenAI-Compatible API endpoint" setting. If you are using the provided Docker networking IPAM configuration from `docker-compose.yml`, the host machine can be accessed at `172.33.0.1` (i.e. the "gateway" config key)

### Local Development

- `pre-commit install` to install hooks
- Install the Pip3 package `xmlformatter` i.e. `pip3 install xmlformatter`
- Run this to exec all the pre-commit hooks on the entire project: `pre-commit run --all-files`
