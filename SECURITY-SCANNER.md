# App Security Scanning 

## Prerequisites

We could use various security scanners:
* Snyk
* OSV Scanner
* Grype
* Trivy

## Prepare SBOM

```
advisor build-config get
jq '.sbom' target/.advisor/build-config.json  > sbom-3.5.16-with-pins.cdx.json
```

## Scanning App - Spring Boot 3.5.16 with pins (log4j and jackson)

```
snyk test --sbom=sbom-3.5.16-with-pins.cdx.json 
```

```
osv-scanner -L sbom-3.5.16-with-pins.cdx.json
```

```
grype sbom:sbom-3.5.16-with-pins.cdx.json
```

```
trivy sbom sbom-3.5.16-with-pins.cdx.json
```

## Patch Upgrade with Spring App Advisor

```
advisor patch apply
```

## Prepare new SBOM

```
advisor build-config get
jq '.sbom' target/.advisor/build-config.json  > sbom-3.5.16-with-pins.cdx.json
```

## Scanning Upgraded App - Spring Boot 3.5.17 with pins (log4j and jackson)

```
snyk test --sbom=sbom-3.5.17-with-pins.cdx.json
```

```
osv-scanner -L sbom-3.5.17-with-pins.cdx.json
```

```
grype sbom:sbom-3.5.17-with-pins.cdx.json
```

```
trivy sbom sbom-3.5.17-with-pins.cdx.json
```

