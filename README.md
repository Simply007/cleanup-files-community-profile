# Mass repositories update

This repository is using [multi-gitter](https://github.com/lindell/multi-gitter) to cleanup meta files to use [fallback from .github repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

> Supposed to be used on UNIX like system

## Getting started

```sh
# clone the repo
git clone https://github.com/Simply007/cleanup-files-community-profile

cd cleanup-files-community-profile

chmod +x cleanup.sh start.sh

# install multi gitter https://github.com/lindell/multi-gitter#install
curl -s https://raw.githubusercontent.com/lindell/multi-gitter/master/install.sh | sh

# set env variable with GitHub token https://github.com/lindell/multi-gitter#token
export GITHUB_TOKEN=TOKEN

sh start.sh
```

> Comment out `--dry-run` from `start.sh` to push

## About

This repo is meant to be adjusted by the needs.