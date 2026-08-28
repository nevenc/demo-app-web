# demo-web-app

Simple Spring Boot App for showcasing patch upgrades. Start version Spring Boot 3.5.16 with pinned versions of `log4j-api:2.25.5` and `jackson-databind:2.21.6`.

## Generate SBOM

```
advisor build-config get
jq '.sbom' target/.advisor/build-config.json  > sbom-3.5.16-with-pins.cdx.json
```

## Patch Upgrade

```
advisor patch apply
```

## Generate SBOM again

```
advisor build-config get
jq '.sbom' target/.advisor/build-config.json  > sbom-3.5.17-with-pins.cdx.json
```

## Application Upgrade

```
advisor upgrade-plan get
advisor upgrade-plan apply --squash=3
```

## Generate SBOM again

```
advisor build-config get
jq '.sbom' target/.advisor/build-config.json  > sbom-4.1.1.cdx.json
```


