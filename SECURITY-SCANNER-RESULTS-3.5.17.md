# Security Scanner Results with 3.5.17 - August 27

## Snyk

```
snyk test --sbom=sbom-3.5.17-with-pins.cdx.json
```

```

╭──────────────────────────────────────────────────────────────────╮
│ 🚧  EARLY ACCESS                                                 │
│ This command is in Early Access. Performance, stability,         │
│ and behavior are subject to change.                              │
│ Your feedback helps us improve! Learn more:                      │
│ https://docs.snyk.io/developer-tools/snyk-cli/commands/sbom-test │
╰──────────────────────────────────────────────────────────────────╯


Testing  (sbom-3.5.17-with-pins.cdx.json) ...

Tested 63 dependencies for known issues, found 12 issues, 12 vulnerable paths.

Security issues: 12

 ✗ [LOW] Improper Neutralization
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267437
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267437
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
   Risk Score: N/A

 ✗ [MEDIUM] Open Redirect
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267433
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267433
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
   Risk Score: N/A

 ✗ [MEDIUM] Open Redirect
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267099
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267099
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
   Risk Score: N/A

 ✗ [MEDIUM] Cross-site Scripting (XSS)
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267094
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267094
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
   Risk Score: N/A

 ✗ [MEDIUM] HTTP Response Splitting
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267076
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267076
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20
   Risk Score: N/A

 ✗ [HIGH] Allocation of Resources Without Limits or Throttling
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267075
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267075
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20 > spring-expression@6.2.20
   Risk Score: N/A

 ✗ [HIGH] Sensitive Cookie in HTTPS Session Without "Secure" Attribute
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267079
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267079
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20
   Risk Score: N/A

 ✗ [HIGH] Cross-site Scripting (XSS)
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267078
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267078
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20
   Risk Score: N/A

 ✗ [HIGH] Allocation of Resources Without Limits or Throttling
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267073
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267073
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20 > spring-expression@6.2.20
   Risk Score: N/A

 ✗ [HIGH] Allocation of Resources Without Limits or Throttling
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267072
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267072
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20 > spring-beans@6.2.20
   Risk Score: N/A

 ✗ [HIGH] Allocation of Resources Without Limits or Throttling
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267077
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267077
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20
   Risk Score: N/A

 ✗ [CRITICAL] Arbitrary Code Injection
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267098
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267098
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
   Risk Score: N/A

Issues to fix by upgrading:
                           
  Upgrade org.springframework.boot:spring-boot-starter-web@3.5.17 to org.springframework.boot:spring-boot-starter-web@4.0.0 to fix
  ✗ Allocation of Resources Without Limits or Throttling [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267075] in spring-expression
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20 > spring-expression@6.2.20
  ✗ Improper Neutralization [Low Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267437] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
  ✗ Sensitive Cookie in HTTPS Session Without "Secure" Attribute [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267079] in spring-web
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20
  ✗ Open Redirect [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267433] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
  ✗ Cross-site Scripting (XSS) [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267078] in spring-web
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20
  ✗ Open Redirect [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267099] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
  ✗ Allocation of Resources Without Limits or Throttling [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267073] in spring-expression
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20 > spring-expression@6.2.20
  ✗ Arbitrary Code Injection [Critical Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267098] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
  ✗ Allocation of Resources Without Limits or Throttling [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267072] in spring-beans
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20 > spring-beans@6.2.20
  ✗ Cross-site Scripting (XSS) [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267094] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-webmvc@6.2.20
  ✗ Allocation of Resources Without Limits or Throttling [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267077] in spring-web
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20
  ✗ HTTP Response Splitting [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267076] in spring-web
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.17 > spring-web@6.2.20

╭──────────────────────────────────────────────────────────╮
│ Test Summary                                             │
│                                                          │
│   Organization:      firstname.lastname                  │
│   Test type:         open-source                         │
│   Project path:      .                                   │
│                                                          │
│   Total security issues: 12                              │
│   Ignored: 0 [ 0 CRITICAL  0 HIGH  0 MEDIUM  0 LOW ]     │
│   Open   : 12 [ 1 CRITICAL  6 HIGH  4 MEDIUM  1 LOW ]    │
╰──────────────────────────────────────────────────────────╯
💡 Tip

   To view ignored issues, use the --include-ignores option.
```

## Grype

```
grype sbom:sbom-3.5.17-with-pins.cdx.json
```

```
 ✔ Scanned for vulnerabilities     [0 vulnerability matches]  
   ├── by severity: 0 critical, 0 high, 0 medium, 0 low, 0 negligible
   └── by status:   0 fixed, 0 not-fixed, 0 ignored 
```

## OSV

```
osv-scanner -L sbom-3.5.17-with-pins.cdx.json
```

```
Starting filesystem walk for root: /
Scanned /Users/user/demo-app-web/sbom-3.5.17-with-pins.cdx.json file and found 63 packages
End status: 0 dirs visited, 1 inodes visited, 1 Extract calls, 1.40825ms elapsed, 1.408ms wall time

No issues found
```

## Trivy

```
trivy --quiet sbom sbom-3.5.17-with-pins.cdx.json
```

```

Report Summary

┌────────┬──────┬─────────────────┐
│ Target │ Type │ Vulnerabilities │
├────────┼──────┼─────────────────┤
│ Java   │ jar  │        0        │
└────────┴──────┴─────────────────┘
Legend:
- '-': Not scanned
- '0': Clean (no security findings detected)

```

