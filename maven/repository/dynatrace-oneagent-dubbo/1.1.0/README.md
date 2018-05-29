# Dynatrace OneAgent SDK for Dubbo

## Requirements

- JRE 1.6 or higher
- Dynatrace OneAgent (required versions see below)

|OneAgent SDK for Java|Required OneAgent version|
|:------|:--------|
|1.1.0  |>=1.143  |
|1.0.3  |>=1.135  |

## How to use 

1. add "dynatrace-oneagent-dubbo-1.1.0.jar" to maven repository

- `groupId`: com.dynatrace
- `artifactId`: dynatrace-oneagent-dubbo
- `version`: 1.1.0


2. add to projecct pom.xml
```
  <dependency>
     <groupId>com.dynatrace</groupId>
     <artifactId>dynatrace-oneagent-dubbo</artifactId>
     <version>1.1.0</version>
     <scope>runtime</scope>
  </dependency>
```
