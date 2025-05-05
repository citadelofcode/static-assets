# Static Assets

This repository contains static assets for all projects built in the `Citadel of Code` organization. These static assets will in turn be deployed to the Cloudflare CDN service to make it accessible in all the projects.

## How does it work?

Every time a new commit is made to the `main` branch of this repository, a CI-CD action task is invoked in Cloudflare to deploy all the files in the latest commit to the CDN service.
