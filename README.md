# Skywalkingzulu

Rust and Python builder in Johannesburg. I ship products that run in production, and I dig into the
compilers and CPU underneath them when they are too slow.

## Selected work

**[PreTxSim](https://github.com/Skywalkingzulu1/pretxsim-mcp)** — a pre-execution firewall for agent
commerce. An MCP server that validates every checkout before a payment is signed: intent match, price
anomaly, session cap, tax surface. Amazon Developer Hackathon 2026, Alexa+ track. Rust, `rmcp`,
streamable HTTP, 9 tests, MIT.

**[Doctors on Wheels](https://docsonwheels.co.za)** — live mobile clinic platform for South African
healthcare: sessional rooms, funding dashboard, patient intake. ([repo](https://github.com/Skywalkingzulu1/Doctorsonwheels))

**[Sandton Index](https://skywalkingzulu1.github.io/sandton-index/)** and
**[Gauteng Index](https://skywalkingzulu1.github.io/gauteng-index/)** — every business in Sandton with
hours, maps and contact details, generated and served as a static index. Python.

**[Impilo LLM](https://github.com/Skywalkingzulu1/impilo-llm)** — on-device isiZulu/English health LLM
for rural South African clinics, ADTC 2026 Laptop LLM Challenge.

**[Agentic Daily / Cascade](https://github.com/Skywalkingzulu1/agentic-daily)** — a daily thread puzzle
game for Reddit built on Devvit Web.

## Currently

CPU inference and codegen for LLMs: measuring and fixing the reduce lowering in tinygrad so a
single-core llama-1B forward pass beats torch. L2-resident probes, generated-C/asm audits, CI-only
measurement.

## Stack

Rust · Python · TypeScript · Solidity · Postgres/Supabase · EVM (revm, Monad, Stellar/Soroban) ·
MCP and AI agents
