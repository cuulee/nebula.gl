# Contributing

## Publishing to npm

To publish to npm, make sure you're using the public registry (`npmrc public`) and publish using `publish-prod`:

```
npmrc public && yarn run publish-prod
```

Versioning is done using [Semantic Versioning](https://semver.org/).

## Generating Changelog

Changelog can be generated using `./scripts/changelog.sh`
