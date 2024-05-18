# Galonline FE and BE
POC for Java Spring Boot ☕🌱 + Grafana Loki 📊 + Open Tracing 🔍 + SigNoz 📈 + Docker 🐳.

## Overall Specification
- Node v20 LTS
- PNPM >= v7
- Java v17
- Maven v3.9.6
- Docker
- SigNoz
- Pickle (Pkl)
- Grafana Loki
- Open Telemetry
- Spring Boot v3.2.5

## Objective
My objective is to make a service have **Observability**, **Maintainability** and **Scalability** capabilities.
This is used to help understand a performance issue, logging, error / crash tracking a process in a service, so that can make us easier to analyze the deficiencies in the service when it is used.

## Problems
- Forgot a configuration rules.
- Debug manual when api take so-much time.
- Debug manual when api crash or errors.
- Debug manual resource check cpu, memory.
  
## Questions
- How to centralize my configuration and make it alive and more expressive?
- How to keep track flow request on each process and sub-process?
- How to centralize a logs error and find it easily?
- storage when service got high traffic, How to centralize my monitoring so i can notify my resource is enough?
