<div align="center">
  <h1>Rui Moura</h1>
  <p><strong>Software Engineer · Finance & Operations background</strong></p>
  <p>
    Software engineer with a background in finance and operations. Completed the <strong>42 Lisboa Common Core</strong>,
    building systems software in C, Go and Python. Before that, managed liquidity on bank treasury desks and ran
    production for a factory of 80 people, automating manual work and turning operational problems into working tools.
  </p>
  <p>
    <a href="https://linkedin.com/in/rui-moura"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:rui2103moura@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://leetcode.com/u/ruimouradev/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode" /></a>
    <img src="https://img.shields.io/badge/Lisbon,%20Portugal-555?style=flat-square" alt="Lisbon" />
  </p>
</div>

---

### 🛠️ Tech Stack

<div align="center">

| Category | Technologies |
| :--- | :--- |
| **Languages** | <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" /> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" /> |
| **Robotics & Edge AI** | <img src="https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white" /> <img src="https://img.shields.io/badge/Gazebo-F58113?style=flat-square" /> <img src="https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white" /> <img src="https://img.shields.io/badge/Model%20Quantization-8A2BE2?style=flat-square" /> <img src="https://img.shields.io/badge/Computer%20Vision-FF6F00?style=flat-square" /> |
| **AI & LLMs** | <img src="https://img.shields.io/badge/AI%20Agents-8A2BE2?style=flat-square" /> <img src="https://img.shields.io/badge/RAG-FF6F00?style=flat-square" /> <img src="https://img.shields.io/badge/Function%20Calling-008080?style=flat-square" /> <img src="https://img.shields.io/badge/vLLM-000000?style=flat-square" /> <img src="https://img.shields.io/badge/MCP-4B0082?style=flat-square" /> |
| **Backend & Infra** | <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" /> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" /> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" /> |
| **Tools** | <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" /> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/Make-000000?style=flat-square&logo=gnu&logoColor=white" /> <img src="https://img.shields.io/badge/GDB-000000?style=flat-square" /> <img src="https://img.shields.io/badge/Valgrind-000000?style=flat-square" /> |

</div>

---

### 🌟 Highlighted Projects

#### 🃏 [ft_transcendence](https://github.com/ruimouradev/ft_transcendence)
> Real-time multiplayer Uno web app. Team of 4, role: Project Manager.

* Built the game core: a server-side rules engine that validates every move, so clients only ever see what they are allowed to see.
* Designed the typed wire protocol between server and browser over WebSockets.
* Built the monitoring stack: Prometheus metrics, Grafana dashboards and alert rules.
* **Stack:** <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />

<br>

#### 🐉 [TAP · The Answer Protocol](https://github.com/ruimouradev/TAP)
> Multiplayer game server over TCP implementing a custom RFC protocol. Team of 2.

* Built the server core: a Hub/Actor concurrency model where a single goroutine owns all world state and clients talk to it over channels, with no mutexes.
* Metadata-driven command dispatcher, combat and quest logic, rate limiting and back-pressure handling, plus the CLI client.
* **Stack:** <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" /> <img src="https://img.shields.io/badge/TCP-Custom%20Protocol-555?style=flat-square" /> <img src="https://img.shields.io/badge/Goroutines%20%26%20Channels-00ADD8?style=flat-square" />

<br>

#### 🤖 [Agent Smith](https://github.com/ruimouradev/Agent_Smith)
> Autonomous coding agent (Thought → Code → Observation loop) evaluated on MBPP and SWE-bench. Team of 2.

* Built the agent loop and the LLM provider layer with key rotation and retries across providers.
* Token and time budgeting, sandboxed execution with an import allowlist and hard resource limits, tools exposed over MCP.
* Benchmark harness comparing 18 models across 4 providers.
* **Stack:** <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/AI%20Agents-8A2BE2?style=flat-square" /> <img src="https://img.shields.io/badge/MCP-4B0082?style=flat-square" /> <img src="https://img.shields.io/badge/SWE--bench-008080?style=flat-square" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

<br>

#### 🧠 [RAG against the machine](https://github.com/ruimouradev/RAG)
> End-to-end Retrieval-Augmented Generation pipeline over the vLLM codebase.

* Ingestion, chunking, BM25 retrieval, generation with Qwen3 served through vLLM, and an evaluation loop.
* **Stack:** <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/RAG-FF6F00?style=flat-square" /> <img src="https://img.shields.io/badge/BM25-008080?style=flat-square" /> <img src="https://img.shields.io/badge/vLLM-000000?style=flat-square" />

<br>

#### ⚡ [CallMeMaybe](https://github.com/ruimouradev/CallMeMaybe)
> LLM function calling with constrained decoding and JSON-schema validation.

* Forces a local open-source model to emit only valid tool calls at the token-sampling level, eliminating structural hallucination.
* **Stack:** <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Constrained%20Decoding-4B0082?style=flat-square" /> <img src="https://img.shields.io/badge/JSON%20Schema-008080?style=flat-square" />

---

### 📁 All Repositories

| Project | Description | Stack |
| :--- | :--- | :---: |
| [**Codexion**](https://github.com/ruimouradev/Codexion) | pthread concurrency simulation: mutex ordering, fairness scheduling and starvation prevention under timing deadlines. | <img src="https://img.shields.io/badge/C-POSIX%20Threads-A8B9CC?style=flat-square&logo=c&logoColor=white" /> |
| [**Pacman**](https://github.com/ruimouradev/Pacman) | Arcade game with configurable levels, BFS-driven ghost AI and persistent highscores. | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> |
| [**A-Maze-ing**](https://github.com/ruimouradev/A-Maze-ing) | Maze generation and pathfinding toolkit. | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> |
| [**push_swap**](https://github.com/ruimouradev/push_swap) | Stack sorting with a restricted instruction set and minimal operation count. | <img src="https://img.shields.io/badge/C-Algorithms-A8B9CC?style=flat-square&logo=c&logoColor=white" /> |
| [**get_next_line**](https://github.com/ruimouradev/get_next_line) | Buffered line reader supporting multiple file descriptors simultaneously. | <img src="https://img.shields.io/badge/C-Memory%20Mgmt-A8B9CC?style=flat-square&logo=c&logoColor=white" /> |
| [**ft_printf**](https://github.com/ruimouradev/ft_printf) | Reimplementation of the C standard `printf` with format flags. | <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" /> |
| [**libft**](https://github.com/ruimouradev/libft) | Foundational C library: memory, strings and linked lists. | <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" /> |

---

<div align="center">
  <sub>Open to conversations about robotics software, embedded AI, distributed systems and agent architectures.</sub>
</div>
