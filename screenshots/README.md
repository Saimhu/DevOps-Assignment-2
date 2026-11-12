# DevOps Assignment 2

## Overview
This assignment demonstrates the installation and configuration of DevOps tools on two Microsoft Azure Ubuntu virtual machines.

## Virtual Machine 1 — Jenkins, Docker and Git
- Operating System: Ubuntu 24.04 LTS
- Java: OpenJDK 21
- Jenkins: 2.580.2
- Docker: 29.1.3
- Git: 2.43.0

**Verification:** Jenkins dashboard accessed successfully, Docker hello-world container executed, and Git configured.

## Virtual Machine 2 — SonarQube and PostgreSQL
- Operating System: Ubuntu 24.04 LTS
- Java: OpenJDK 21
- PostgreSQL: 16
- SonarQube Community Build: 26.11.0

**Verification:** PostgreSQL service enabled, SonarQube dashboard accessible, and SonarQube configured as an automatic startup service.

## Screenshots
Installation and verification screenshots are available in the `screenshots` folder.

## Access
Jenkins and SonarQube were accessed securely through SSH port forwarding.

- Jenkins: `http://localhost:8080`
- SonarQube: `http://localhost:9000`

These localhost addresses work only when the appropriate SSH tunnels are active.
