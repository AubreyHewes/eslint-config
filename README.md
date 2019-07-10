[![Known Vulnerabilities](https://snyk.io//test/github/AubreyHewes/eslint-config/badge.svg?targetFile=package.json&style=flat-square)](https://snyk.io//test/github/AubreyHewes/eslint-config?targetFile=package.json&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/AubreyHewes/eslint-config.svg?style=flat-square)
![GitHub tag (latest by date)](https://img.shields.io/github/tag-date/AubreyHewes/eslint-config.svg?style=flat-square)
![npm](https://img.shields.io/npm/v/@hewes/eslint-config.svg?style=flat-square)
![npm](https://img.shields.io/npm/dm/@hewes/eslint-config.svg?style=flat-square)
[![Beerpay](https://beerpay.io/AubreyHewes/eslint-config/badge.svg?style=flat-square)](https://beerpay.io/AubreyHewes/eslint-config)

# eslint-config

This is a basic eslint config used by me.

To install and use do the following:

```
yarn add --dev @hewes/eslint-config eslint prettier
```

And configure eslint to extend `@hewes/eslint-config`

```json
{
  "extends": "@hewes/eslint-config"
}
```

That should do it!

Also I recommend a deviant prettier configuration as we no longer live in he 80s and github is not the one ring:

```json
{
  "printWidth": 120
}
```
