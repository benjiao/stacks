# Homepage
A homepage dashboard for all my self-hosted apps.

![Homepage Screenshot](images/homepage.png)

## Config
Reference: https://gethomepage.dev/installation/docker/#using-environment-secrets

> [!TIP]
> I initially had trouble using environment variables for my API keys. Homepage requires variables to have the `HOMEPAGE_VAR_` prefix and variables should enclosed in double handlebars `{{ HOMEPAGE_VAR_API_TOKEN }}` instead of `${ ... }`.