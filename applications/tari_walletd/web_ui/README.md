# Getting Started

Copy the `.env.example` file to `.env` and edit the correct environment variable values.
The example sets `VITE_DAEMON_JRPC_ADDRESS` to `http://localhost:9000`. A wallet daemon started
without `--listen-on` listens on `http://127.0.0.1:5100`.

```shell
pnpm install
pnpm run dev
```