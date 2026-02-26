# DevOps vs SRE: Diferenças e Conceitos

## O que é DevOps?

DevOps (Development + Operations) é uma filosofia e conjunto de práticas que focam em:

- **Integração Contínua (CI)**: Automatizar testes e builds
- **Entrega Contínua (CD)**: Automatizar deployments
- **Infraestrutura como Código (IaC)**: Gerenciar infraestrutura de forma programática
- **Monitoramento e Logs**: Observabilidade contínua
- **Colaboração**: Eliminar silos entre desenvolvimento e operações

### Responsabilidades do DevOps Engineer

- Implementar pipelines CI/CD
- Gerenciar infraestrutura em nuvem
- Automatizar processos operacionais
- Configurar e manter sistemas de monitoramento
- Trabalhar com containerização (Docker, Kubernetes)
- Implementar IaC (Terraform, Ansible, CloudFormation)
- Suportar o time de desenvolvimento em deployment

---

## O que é SRE?

SRE (Site Reliability Engineering) é uma abordagem operacional que se concentra em:

- **Confiabilidade do Sistema**: Maximizar uptime e performance
- **Automação**: Eliminar tarefas repetitivas através de automação
- **SLI/SLO/SLA**: Definir e manter objetivos de confiabilidade
- **Incident Management**: Responder e aprender com incidentes
- **Toil Reduction**: Reduzir trabalho manual e repetitivo

### Responsabilidades do SRE

- Definir SLOs (Service Level Objectives) e SLIs (Service Level Indicators)
- Gerenciar incidentes e post-mortems
- Implementar automação para reduzir toil
- Melhorar a confiabilidade e performance dos serviços
- Realizar capacity planning
- Implementar disaster recovery e backup strategies
- Participar ativamente de on-call rotations

---

## Principais Diferenças

| Aspecto | DevOps | SRE |
|--------|--------|-----|
| **Foco** | Automatizar processos de desenvolvimento e deployment | Garantir confiabilidade e performance |
| **Origem** | Mindset de colaboração | Prática de engenharia |
| **Métrica Principal** | Velocidade de entrega | Confiabilidade (SLO) |
| **Tarefas Típicas** | CI/CD, Infraestrutura, Ferramentas | Incident response, Automação, Monitoring |
| **Mindset** | "Como entregar mais rápido?" | "Como manter o sistema confiável?" |
| **Relacionamento com Dev** | Parceria para melhorar delivery | Parceria para melhorar confiabilidade |
| **Prioridades** | Velocidade + Qualidade | Confiabilidade + Performance |

---

## Complementaridade

Na prática, DevOps e SRE são complementares:

- **DevOps** fornece as ferramentas e processos
- **SRE** usa essas ferramentas para manter a confiabilidade

Uma organização moderna geralmente tem:
- **DevOps Engineers**: Construindo pipelines e infraestrutura
- **SREs**: Monitorando, respondendo a incidentes e melhorando confiabilidade

Juntos, criam uma cultura de responsabilidade compartilhada entre desenvolvimento e operações.

---

## Recursos Adicionais

- [Google SRE Book](https://sre.google/books/)
- [The Phoenix Project](https://itrevolution.com/the-phoenix-project/)
- [DevOps Handbook](https://itrevolution.com/the-devops-handbook/)

---

**Último update**: 2026-02-26
