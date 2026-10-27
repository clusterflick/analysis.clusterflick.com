# analysis.clusterflick.com

> **[Clusterflick](https://clusterflick.com)** is a free, open-source site
> listing every film showing in London, from 450+ venues in one search.
>
> This repository is a build of the original Clusterflick site, kept for
> reviewing the combined data. See the
> [Clusterflick organisation](https://github.com/clusterflick) for how the
> pieces fit together.

It is published at
[analysis.clusterflick.com](https://analysis.clusterflick.com) and rebuilt by
the `generate_site` workflow each time
[data-combined](https://github.com/clusterflick/data-combined) publishes a new
release.

## Development

```bash
npm install
./scripts/get-latest-release-assets.sh  # download and process the latest combined and matched data
npm run dev
```
