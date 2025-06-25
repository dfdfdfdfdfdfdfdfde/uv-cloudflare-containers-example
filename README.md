# uv-cloudflare-containers-example

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/charliermarsh/uv-cloudflare-containers-example)

Deploying a FastAPI application to [Cloudflare Containers](https://developers.cloudflare.com/containers/) with [uv](https://docs.astral.sh/uv/).

## Usage

From the `./app` subdirectory, run the FastAPI server locally with:

```bash
uv run fastapi dev
```

From the repository root, deploy to Cloudflare with:

```bash
npx wrangler deploy
```
