# Diagrama da Arquitetura Pública / Public Architecture Diagram

[Português](#português) | [English](#english)

---

## Português

Este diagrama apresenta uma visão segura e pública da arquitetura conceitual do Cérebro Tendoshk.

Ele não representa a implementação privada completa e não expõe mecanismos internos sensíveis.

```mermaid
flowchart TD
    A[Camada de Entrada<br/>Conversas, ideias, documentos, decisões] --> B[Camada de Curadoria<br/>Filtrar, classificar, preservar ou descartar]
    B --> C[Camada de Memória Útil<br/>Registros reutilizáveis e decisões preservadas]
    C --> D[Camada de Continuidade<br/>Retomar projetos sem recomeçar do zero]
    D --> E[Camada Pública<br/>Documentação sanitizada e modelos fictícios]

    P[Núcleo Privado<br/>Material operacional e sensível] -. fronteira protegida .- E
    P -. não espelhado publicamente .- C
```

### Leitura do diagrama

- A camada de entrada recebe materiais brutos.
- A camada de curadoria decide o que tem valor durável.
- A camada de memória útil organiza o que pode apoiar retomadas futuras.
- A camada de continuidade protege o fio de projetos vivos.
- A camada pública mostra apenas documentação sanitizada.
- O núcleo privado permanece separado por design.

---

## English

This diagram presents a safe public view of the Cérebro Tendoshk conceptual architecture.

It does not represent the complete private implementation and does not expose sensitive internal mechanisms.

```mermaid
flowchart TD
    A[Input Layer<br/>Conversations, ideas, documents, decisions] --> B[Curation Layer<br/>Filter, classify, preserve, or discard]
    B --> C[Useful Memory Layer<br/>Reusable records and preserved decisions]
    C --> D[Continuity Layer<br/>Resume projects without restarting from zero]
    D --> E[Public Layer<br/>Sanitized documentation and fictional templates]

    P[Private Core<br/>Operational and sensitive material] -. protected boundary .- E
    P -. not publicly mirrored .- C
```

### How to read the diagram

- The input layer receives raw material.
- The curation layer decides what has durable value.
- The useful memory layer organizes what can support future resumption.
- The continuity layer protects the thread of living projects.
- The public layer shows only sanitized documentation.
- The private core remains separated by design.
