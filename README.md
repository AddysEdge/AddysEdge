# Hi, I'm Aditya

**CS @ California State University, Long Beach · May 2028**

**Seeking Summer 2027 software engineering internships**

I build backend systems and tools for testing how they behave when things fail.
I'm also an undergraduate research assistant working on multithreaded performance in Java and C++.

### Selected projects

| Project | Problem and implementation | Stack |
|---|---|---|
| [**TaskForge**](https://github.com/AddysEdge/Task_forge) | Distributed job execution with a transactional outbox, atomic claims, worker leases, retries and crash recovery. [Build and integration tests](https://github.com/AddysEdge/Task_forge/actions/workflows/ci.yml). | Java, Spring Boot, PostgreSQL, Kafka, Redis, Docker |
| [**DeployGuard**](https://github.com/AddysEdge/deployguard) | Replays one API workload against baseline and candidate releases, then blocks behavioral or repeated p95 latency regressions. Includes a fixture demo and [CI](https://github.com/AddysEdge/deployguard/actions/workflows/ci.yml). | Go, HTTP, GitHub Actions |
| [**FaceAuth**](https://github.com/AddysEdge/ai-face-auth) | Offline CPU face-authentication research prototype: frame-quality checks, blink liveness and encrypted templates. [Tests](https://github.com/AddysEdge/ai-face-auth/actions/workflows/ci.yml) and [security analysis](https://github.com/AddysEdge/ai-face-auth/actions/workflows/codeql.yml). | Python, OpenCV, ONNX Runtime, LiteRT |
| [**Interface Lab**](https://github.com/AddysEdge/interface-lab) | UI component sharing with an editor, sandboxed previews, authentication, likes and threaded comments. | Next.js, React, Clerk, Supabase |

### Engineering case studies

- [TaskForge: recovering work after a process crash](projects/taskforge.md)
- [DeployGuard: making an API regression block a release](projects/deployguard.md)
- [FaceAuth: checking privacy boundaries in a local prototype](projects/faceauth.md)

### Try a project

[Download DeployGuard](https://github.com/AddysEdge/deployguard/releases/latest) for Linux,
macOS or Windows. Each bundle includes the CLI, a fixture server and a sample workload;
no Go installation, API key or database is needed.

To build and run the demo from source, use Go 1.27+, Bash and curl:

```bash
git clone https://github.com/AddysEdge/deployguard.git
cd deployguard
bash scripts/release-gate.sh
bash scripts/release-gate.sh regressed   # expected: regression detected, exit 1
```

FaceAuth is a research prototype with documented spoofing limitations; it does not replace Windows sign-in.
Each repository documents its setup, current scope and engineering trade-offs.

### Tools I use

Java · Go · Python · JavaScript · SQL · C++ · Spring Boot · PostgreSQL · Kafka · Redis · Docker · React · Next.js · GitHub Actions

### Contact

[LinkedIn](https://www.linkedin.com/in/adityarana07) · [GitHub projects](https://github.com/AddysEdge?tab=repositories)
