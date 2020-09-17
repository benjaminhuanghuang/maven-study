## Life cycle
- Default: main lifecycle, for build and deploymnet
- Clean: clean the target foler
- Site: generate project doc


## Phase
- Validation
- compile
- test
- package
- verify
- install
- deploy

## Goals
triggle a goale
```
  mvn dependency:analyze
```

## Plugins
- deploy plugin: deploy the artifact that is installed in local .m2 repo to the central repository

- release plugin: relase the artifact to Maven Central