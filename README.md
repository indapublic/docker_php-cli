```shell
make PHP_VERSION=8.5 build
```

Publish is handled by GitHub Actions on tag push:

```shell
git tag 8.5
git push origin 8.5
```
