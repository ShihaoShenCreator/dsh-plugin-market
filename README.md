# dsh-plugin-market
A plugin market for DeepSeek Harness.

## How to add

> [!NOTE]
>
> **RECOMMENDED**: Allow all build scripts for plugins.
>
> Add the following to `~/.dsh/profiles/<name>/pnpm-workspace.yaml`:
> ```yaml
> dangerouslyAllowAllBuilds: true
> ```

Enable `Custom plugin markets` plugin, click `Plugins -> Discover -> Add index source`, then paste the following URL:
```
https://raw.githubusercontent.com/ShihaoShenCreator/dsh-plugin-market/refs/heads/main/index.json
```

For users in China, use one of the following URLs for higher stability and speed:
```
https://sget.netlify.app/gh/ShihaoShenCreator/dsh-plugin-market/raw/refs/heads/main/index.json
https://xget.xi-xu.me/gh/ShihaoShenCreator/dsh-plugin-market/raw/refs/heads/main/index.json
https://gh-proxy.org/https://raw.githubusercontent.com/ShihaoShenCreator/dsh-plugin-market/refs/heads/main/index.json
```
