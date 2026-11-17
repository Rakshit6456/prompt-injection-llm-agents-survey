# Indirect Prompt Injection in LLM Agents: A Review of Attacks, Defences and Evaluation

Evidence repository for a survey paper written for the course *Foundations of Cyber Security* (CSE25305), School of Computer Science and Engineering, IILM University, Gurugram.

The paper reviews 25 works posted between 2023 and 2026 on indirect prompt injection against LLM agents. They are grouped into attacks and exploitation, benchmarks, model-level defences, system-level defences and critiques of evaluation. This repository holds the records behind the review.

## Files

| File | What it holds |
|---|---|
| `literature_matrix_25_papers_v2.csv` | One row per work read: reference, year, venue, problem, method, test bed, measure, key result and limitation. The "Ref in paper" column matches the paper's reference numbers. |
| `references.bib` | The 25 references in BibTeX (`ref01` to `ref25`, same order as the paper). |
| `search_log.csv` | Every search string, date and hit count, and the selection steps. |

## How the works were selected

- **Source searched:** arXiv through its public API, on 26 Oct 2026 and again on 15 Nov 2026. IEEE Xplore and Google Scholar were checked on 16 Nov 2026 for coverage only; their results were not screened.
- **Selection counts:** 2,402 records identified; 2,070 after duplicates were removed; 41 screened; 25 included (3 surveys and 22 primary studies).
- **Inclusion:** posted or published 2023 to 2026, peer reviewed or a marked preprint, written in English, and about prompt injection against LLM applications or agents. Full criteria are in Table II of the paper.

## The 25 reviewed works

| Ref. | Title | Year | Link |
|---|---|---|---|
| [1] | Not what you've signed up for: Compromising real-world LLM-integrated applications with indirect prompt injection | 2023 | [arXiv:2302.12173](https://arxiv.org/abs/2302.12173) |
| [2] | EchoLeak: The first real-world zero-click prompt injection exploit in a production LLM system | 2025 | [arXiv:2509.10540](https://arxiv.org/abs/2509.10540) |
| [3] | The landscape of prompt injection threats in LLM agents: From taxonomy to analysis | 2026 | [arXiv:2602.10453](https://arxiv.org/abs/2602.10453) |
| [4] | A systematic literature review on LLM defenses against prompt injection and jailbreaking: Expanding NIST taxonomy | 2026 | [arXiv:2601.22240](https://arxiv.org/abs/2601.22240) |
| [5] | Jailbreak attacks and defenses against large language models: A survey | 2024 | [arXiv:2407.04295](https://arxiv.org/abs/2407.04295) |
| [6] | The attacker moves second: Stronger adaptive attacks bypass defenses against LLM jailbreaks and prompt injections | 2025 | [arXiv:2510.09023](https://arxiv.org/abs/2510.09023) |
| [7] | Adaptive attacks break defenses against indirect prompt injection attacks on LLM agents | 2025 | [arXiv:2503.00061](https://arxiv.org/abs/2503.00061) |
| [8] | Ignored, not refused: What low prompt-injection success rates hide in small tool-using agents | 2026 | [arXiv:2610.23254](https://arxiv.org/abs/2610.23254) |
| [9] | Formalizing and benchmarking prompt injection attacks and defenses | 2023 | [arXiv:2310.12815](https://arxiv.org/abs/2310.12815) |
| [10] | Benchmarking and defending against indirect prompt injection attacks on large language models | 2025 | see DOI in references.bib |
| [11] | InjecAgent: Benchmarking indirect prompt injections in tool-integrated large language model agents | 2024 | [arXiv:2403.02691](https://arxiv.org/abs/2403.02691) |
| [12] | AgentDojo: A dynamic environment to evaluate prompt injection attacks and defenses for LLM agents | 2024 | [arXiv:2406.13352](https://arxiv.org/abs/2406.13352) |
| [13] | Agent Security Bench (ASB): Formalizing and benchmarking attacks and defenses in LLM-based agents | 2025 | [arXiv:2410.02644](https://arxiv.org/abs/2410.02644) |
| [14] | WASP: Benchmarking web agent security against prompt injection attacks | 2025 | [arXiv:2504.18575](https://arxiv.org/abs/2504.18575) |
| [15] | JailbreakBench: An open robustness benchmark for jailbreaking large language models | 2024 | [arXiv:2404.01318](https://arxiv.org/abs/2404.01318) |
| [16] | Defending against indirect prompt injection attacks with spotlighting | 2024 | [arXiv:2403.14720](https://arxiv.org/abs/2403.14720) |
| [17] | The instruction hierarchy: Training LLMs to prioritize privileged instructions | 2024 | [arXiv:2404.13208](https://arxiv.org/abs/2404.13208) |
| [18] | StruQ: Defending against prompt injection with structured queries | 2024 | [arXiv:2402.06363](https://arxiv.org/abs/2402.06363) |
| [19] | SecAlign: Defending against prompt injection with preference optimization | 2025 | see DOI in references.bib |
| [20] | Meta-SecAlign: Training LLMs against prompt injection for robust agents | 2025 | [arXiv:2507.02735](https://arxiv.org/abs/2507.02735) |
| [21] | Defeating prompt injections by design | 2025 | [arXiv:2503.18813](https://arxiv.org/abs/2503.18813) |
| [22] | Progent: Securing AI agents with privilege control | 2025 | [arXiv:2504.11703](https://arxiv.org/abs/2504.11703) |
| [23] | Design patterns for securing LLM agents against prompt injections | 2025 | [arXiv:2506.08837](https://arxiv.org/abs/2506.08837) |
| [24] | ARGUS: Defending LLM agents against context-aware prompt injection | 2026 | [arXiv:2605.03378](https://arxiv.org/abs/2605.03378) |
| [25] | Adaptive evaluation of out-of-band defenses against prompt injection in LLM agents | 2026 | [arXiv:2606.26479](https://arxiv.org/abs/2606.26479) |


