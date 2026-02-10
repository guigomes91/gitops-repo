🚀 gitops-repo — GitOps Lab com ArgoCD e Kubernetes (Kind)

Este repositório faz parte do meu laboratório prático de GitOps e Continuous Delivery, criado para demonstrar boas práticas modernas de entrega de aplicações em Kubernetes, utilizando ArgoCD como motor de sincronização declarativa.

O objetivo principal é mostrar, na prática, como Git se torna a fonte única da verdade para aplicações e infraestrutura, garantindo consistência, rastreabilidade e automação no processo de deploy.

Conceito de GitOps

Neste laboratório, aplico o conceito de GitOps, onde:

O Git é a fonte única da verdade

Toda mudança de infraestrutura ou aplicação é feita via commit

O ArgoCD garante que o cluster esteja sempre convergente com o que está declarado no repositório

🧱 Arquitetura do Laboratório

Kind — Cluster Kubernetes local

ArgoCD — Observa o repositório e mantém o estado desejado

Git — Fonte única da verdade

Manifests Kubernetes — Deploy declarativo das aplicações

🎯 Objetivo do Repositório

Demonstrar GitOps na prática

Simular ambientes reais de CI/CD

Estudar boas práticas de entrega contínua

Facilitar rollback e rastreabilidade

Evitar mudanças manuais no cluster
