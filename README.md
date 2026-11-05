# Kortix compose files

Docker Compose files for [Kortix](https://kortix.com), used by the Kortix template in
[Easypanel](https://easypanel.io). Each Kortix release is tagged `kortix-<version>`;
templates pin a tag.

- `kortix/docker-compose.yml`: the full self-hosted stack (web app, API, LLM gateway,
  Supabase). Every value comes from the service's `.env` (`${VAR}`), which the template fills in:
  generated secrets, the three public URLs, `PLATINUM_API_KEY` and `KORTIX_ADMIN_EMAIL`.

Generated from the Kortix deploy-templates stack. Don't edit by hand.
