```shell
make PHP_VERSION=8.4 build
make PHP_VERSION=8.4 publish
```

Publish is handled by GitHub Actions on tag push:

```shell
git tag 8.4
git push origin 8.4
```
