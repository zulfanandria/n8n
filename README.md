# Deploy n8n on Render

This template defines a `render.yaml` file you can use to deploy [n8n](https://n8n.io/) on Render. Click **Use this template** in the upper right to copy this template into your account as a new repo.

View full deployment instructions in the [Render docs](https://render.com/docs/deploy-n8n).

The `render.yaml` file defines the following resources:

- A web service that pulls and runs the official n8n Docker image
- A Render Postgres database that stores n8n data

Each of the above uses the smallest paid instance type by default.
