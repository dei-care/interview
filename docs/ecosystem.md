# Ecosystem — repo → tech map

**Parent:** [`README.md`](./README.md)

How the repositories relate to the toolchains they run on. Every language is the best tool for its job — one toolchain per purpose, deliberately chosen.

```mermaid
flowchart LR
    subgraph REPOS[Repositories]
        GH[1-.github]
        DS[2-data-science]
        EXT[3-browser-extensions]
        AUTO[4-ai-agents]
        PS[5-problem-solving]
        GAMES[6-browser-games]
        SD[7-system-design]
        PKG[8-pkg-manager]
    end

    subgraph TOOLS[Toolchains]
        MD[Markdown]
        BASH[Bash]
        DOCKER[Docker]
        CPP[C++17]
        LA[LaTeX]
        MERMAID[Mermaid]
        TS[TypeScript]
        VJS[Vanilla JS]
        PY[Python]
        PANDAS[Pandas]
        REACT[React]
        RUSTW[Rust / WASM]
    end

    GH --> MD
    DS --> PY
    DS --> PANDAS
    DS --> VJS
    EXT --> TS
    EXT --> VJS
    AUTO --> BASH
    AUTO --> DOCKER
    PS --> MD
    PS --> CPP
    PS --> LA
    PS --> MERMAID
    GAMES --> RUSTW
    GAMES --> REACT
    GAMES --> TS
    SD --> MD
    SD --> MERMAID
    PKG --> BASH
    PKG --> DOCKER

    classDef repo fill:#e8f5e9,#66bb6a,stroke:#2e7d32,color:#111
    classDef tool fill:#e3f2fd,#42a5f5,stroke:#1565c0,color:#111
    class GH,DS,EXT,AUTO,PS,GAMES,SD,PKG repo
    class MD,BASH,DOCKER,CPP,LA,MERMAID,TS,VJS,PY,PANDAS,REACT,RUSTW tool
```

## Repo → tools

| Repo | Tools | Why |
|---|---|---|
| 1-.github | Markdown | Organization entry point — profile README + shared GitHub config. |
| 2-data-science | Python · Pandas · Vanilla JS | Collect and analyze stock market, lottery, and news data; render static dashboards. |
| 3-browser-extensions | TypeScript · Vanilla JS · Vite | Typed JS for the browser runtime, ships without a server. |
| 4-ai-agents | Bash · YAML · Markdown | AI agents — reusable dispatch stages and status tooling. |
| 5-problem-solving | Markdown · C++17 · LaTeX · Mermaid | Competitive-programming reference + behavioral prep. |
| 6-browser-games | Rust/WASM · React · TypeScript | One Rust codebase from engine (WASM) to backend; React where a SPA earns it. |
| 7-system-design | Markdown · Mermaid | Architecture examples, patterns, AWS drills, and 60-minute runbooks. |
| 8-pkg-manager | Bash · Docker · YAML · Markdown | The shell is the interface; one pinned Docker image per language toolchain. |
