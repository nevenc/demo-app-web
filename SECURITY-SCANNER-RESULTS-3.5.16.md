# Security Scanner Results with 3.5.16 - August 27

## Snyk

```
snyk test --sbom=sbom-3.5.16-with-pins.cdx.json
```

```

╭──────────────────────────────────────────────────────────────────╮
│ 🚧  EARLY ACCESS                                                 │
│ This command is in Early Access. Performance, stability,         │
│ and behavior are subject to change.                              │
│ Your feedback helps us improve! Learn more:                      │
│ https://docs.snyk.io/developer-tools/snyk-cli/commands/sbom-test │
╰──────────────────────────────────────────────────────────────────╯


Testing  (sbom-3.5.16-with-pins.cdx.json) ...

Tested 63 dependencies for known issues, found 18 issues, 18 vulnerable paths.

Security issues: 18

 ✗ [LOW] Improper Neutralization
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267437
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267437
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
   Risk Score: N/A

 ✗ [MEDIUM] Open Redirect
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267433
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267433
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
   Risk Score: N/A

 ✗ [MEDIUM] Open Redirect
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267099
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267099
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
   Risk Score: N/A

 ✗ [MEDIUM] HTTP Response Splitting
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267076
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267076
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19
   Risk Score: N/A

 ✗ [MEDIUM] Cross-site Scripting (XSS)
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267094
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267094
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
   Risk Score: N/A

 ✗ [MEDIUM] Improper Authorization
   Finding ID: SNYK-JAVA-ORGAPACHETOMCATEMBED-17733895
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17733895
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
   Risk Score: N/A

 ✗ [MEDIUM] Always-Incorrect Control Flow Implementation
   Finding ID: SNYK-JAVA-ORGAPACHETOMCATEMBED-17734715
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17734715
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
   Risk Score: N/A

 ✗ [MEDIUM] Always-Incorrect Control Flow Implementation
   Finding ID: SNYK-JAVA-ORGAPACHETOMCATEMBED-17734718
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17734718
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
   Risk Score: N/A

 ✗ [HIGH] Sensitive Cookie in HTTPS Session Without "Secure" Attribute
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267079
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267079
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19
   Risk Score: N/A

 ✗ [HIGH] Allocation of Resources Without Limits or Throttling
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267075
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267075
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19 > spring-expression@6.2.19
   Risk Score: N/A

 ✗ [HIGH] Detection of Error Condition Without Action
   Finding ID: SNYK-JAVA-ORGAPACHETOMCATEMBED-17733746
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17733746
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
   Risk Score: N/A

 ✗ [HIGH] Allocation of Resources Without Limits or Throttling
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267072
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267072
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19 > spring-beans@6.2.19
   Risk Score: N/A

 ✗ [HIGH] Expression Injection
   Finding ID: SNYK-JAVA-CHQOSLOGBACK-17675439
   Info: https://snyk.io/vuln/SNYK-JAVA-CHQOSLOGBACK-17675439
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-test@3.5.16 > org.springframework.boot:spring-boot-starter@3.5.16 > org.springframework.boot:spring-boot-starter-logging@3.5.16 > ch.qos.logback:logback-classic@1.5.34 > logback-core@1.5.34
   Risk Score: N/A

 ✗ [HIGH] Improper Authentication
   Finding ID: SNYK-JAVA-ORGAPACHETOMCATEMBED-17732890
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17732890
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
   Risk Score: N/A

 ✗ [HIGH] Cross-site Scripting (XSS)
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267078
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267078
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19
   Risk Score: N/A

 ✗ [HIGH] Allocation of Resources Without Limits or Throttling
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267077
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267077
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19
   Risk Score: N/A

 ✗ [HIGH] Allocation of Resources Without Limits or Throttling
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267073
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267073
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19 > spring-expression@6.2.19
   Risk Score: N/A

 ✗ [CRITICAL] Arbitrary Code Injection
   Finding ID: SNYK-JAVA-ORGSPRINGFRAMEWORK-19267098
   Info: https://snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267098
   Introduced by: com.example:demo-app-web@0.0.1-SNAPSHOT
   Introduced through: com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
   Risk Score: N/A

Issues to fix by upgrading:
                           
  Upgrade org.springframework.boot:spring-boot-starter-web@3.5.16 to org.springframework.boot:spring-boot-starter-web@4.0.0 to fix
  ✗ Improper Authorization [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17733895] in tomcat-embed-core
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
  ✗ Allocation of Resources Without Limits or Throttling [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267077] in spring-web
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19
  ✗ Allocation of Resources Without Limits or Throttling [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267075] in spring-expression
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19 > spring-expression@6.2.19
  ✗ Allocation of Resources Without Limits or Throttling [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267073] in spring-expression
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19 > spring-expression@6.2.19
  ✗ Improper Authentication [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17732890] in tomcat-embed-core
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
  ✗ Always-Incorrect Control Flow Implementation [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17734715] in tomcat-embed-core
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
  ✗ Detection of Error Condition Without Action [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17733746] in tomcat-embed-core
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
  ✗ Open Redirect [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267099] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
  ✗ Allocation of Resources Without Limits or Throttling [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267072] in spring-beans
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19 > spring-beans@6.2.19
  ✗ Sensitive Cookie in HTTPS Session Without "Secure" Attribute [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267079] in spring-web
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19
  ✗ Always-Incorrect Control Flow Implementation [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGAPACHETOMCATEMBED-17734718] in tomcat-embed-core
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > org.springframework.boot:spring-boot-starter-tomcat@3.5.16 > tomcat-embed-core@10.1.55
  ✗ Open Redirect [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267433] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
  ✗ Cross-site Scripting (XSS) [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267094] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
  ✗ Arbitrary Code Injection [Critical Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267098] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
  ✗ Cross-site Scripting (XSS) [High Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267078] in spring-web
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19
  ✗ Improper Neutralization [Low Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267437] in spring-webmvc
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-webmvc@6.2.19
  ✗ HTTP Response Splitting [Medium Severity] [https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORK-19267076] in spring-web
    introduced by com.example:demo-app-web@0.0.1-SNAPSHOT > org.springframework.boot:spring-boot-starter-web@3.5.16 > spring-web@6.2.19

╭──────────────────────────────────────────────────────────╮
│ Test Summary                                             │
│                                                          │
│   Organization:      firstname.lastname                  │
│   Test type:         open-source                         │
│   Project path:      .                                   │
│                                                          │
│   Total security issues: 18                              │
│   Ignored: 0 [ 0 CRITICAL  0 HIGH  0 MEDIUM  0 LOW ]     │
│   Open   : 18 [ 1 CRITICAL  9 HIGH  7 MEDIUM  1 LOW ]    │
╰──────────────────────────────────────────────────────────╯
💡 Tip

   To view ignored issues, use the --include-ignores option.
```

## Grype

```
grype sbom:sbom-3.5.16-with-pins.cdx.json
```

```
 ✔ Scanned for vulnerabilities     [0 vulnerability matches]  
   ├── by severity: 0 critical, 0 high, 0 medium, 0 low, 0 negligible
   └── by status:   0 fixed, 0 not-fixed, 0 ignored 
No vulnerabilities found
```

## OSV

```
osv-scanner -L sbom-3.5.16-with-pins.cdx.json
```

```
Starting filesystem walk for root: /
Scanned /Users/user/demo-app-web/sbom-3.5.16-with-pins.cdx.json file and found 63 packages
End status: 0 dirs visited, 1 inodes visited, 1 Extract calls, 1.468583ms elapsed, 1.469ms wall time

No issues found
```

## Trivy

```
trivy --quiet sbom sbom-3.5.16-with-pins.cdx.json
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

