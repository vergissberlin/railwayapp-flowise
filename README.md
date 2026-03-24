# Flowise for railway.app

![Template Header](./template-header.svg)

Deploy [Flowise](https://flowiseai.com/) on Railway using the official `flowiseai/flowise` image.

[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/new/template)

## Environment

See [Flowise environment variables](https://docs.flowiseai.com/configuration/environment-variables). Persist flows by mounting a volume or setting storage-related env vars.

## Local

```bash
docker build -t railwayapp-flowise .
docker run --rm -p 3000:3000 -e PORT=3000 railwayapp-flowise
```

<!-- footer -->
