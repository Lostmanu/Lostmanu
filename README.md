<h1 align="center">Hi, I'm Manuel</h1>

<p align="center">
  <b>Electronics and control engineer · Spain</b><br>
  I measure AI evaluation suites against the papers they implement, and send the fixes.
</p>

---

I read evaluation code next to the benchmark it claims to implement. When a scorer, a sample id or a declared count doesn't match, I reproduce the gap with the real code, measure both directions (what it wrongly accepts and what it wrongly rejects) and open the fix upstream.

### Open-source fixes

| project | what was wrong | status |
|---|---|---|
| [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/pull/2507) (UK AI Security Institute) | `worldsense` never evaluated a single `FALSE` or `IMPOSSIBLE` answer | **merged** |
| [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/pull/2489) | `apps` declared 5,000 samples and loaded 3,000 | **merged** |
| [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/pull/2491) | `bbh` scored answers by suffix match | open |
| [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/pull/2490) | `bbh` declared 250 samples and loads 6,509 | open |
| [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness/pull/4215) (EleutherAI) | BBH few-shot answers of `(Q)` could never score | open |
| [evalscope](https://github.com/modelscope/evalscope/pull/1773) (ModelScope) | BBH `dyck_languages` lost its brackets | open |

### Selected work

- **[Ninety-Three Wrong Claims](https://github.com/Lostmanu/ninety-three-wrong-claims)**: a research programme on crypto perpetual-futures microstructure that found no edge, published with the register of the 93 claims it got wrong and who or what caught each one.
- **[quant-system](https://github.com/Lostmanu/quant-system)**: the laboratory behind it, with 476 tests and a mutation harness that proves each guard actually fails when it should.
- **[ifs-aifs-siar](https://github.com/Lostmanu/ifs-aifs-siar)**: ECMWF IFS and AIFS solar radiation forecasts against 34 SiAR ground stations in Spain.

### How I work

I preregister what counts as success before the data exists, and I build controls that have to prove they bite. I work with AI coding agents, and I keep a public record of every claim that turned out to be false, theirs and mine.

---

<h3 align="center">Languages</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge" alt="MATLAB">
  <img src="https://img.shields.io/badge/Simulink-E16737?style=for-the-badge" alt="Simulink">
  <img src="https://img.shields.io/badge/PLC-IEC%2061131--3%20Structured%20Text-2E7D32?style=for-the-badge" alt="PLC (IEC 61131-3 Structured Text)">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white" alt="CSS">
</p>

<h3 align="center">Tools</h3>

<p align="center">
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
</p>

---

<h3 align="center">Get in touch</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/manuel-beardo-campo-804a9b201/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCc%2BPHBhdGggZmlsbD0nd2hpdGUnIGQ9J00yMC40NSAyMC40NWgtMy41NnYtNS41N2MwLTEuMzMtLjAyLTMuMDQtMS44NS0zLjA0LTEuODUgMC0yLjE0IDEuNDUtMi4xNCAyLjk0djUuNjdIOS4zNVY5aDMuNDF2MS41NmguMDVjLjQ4LS45IDEuNjQtMS44NSAzLjM3LTEuODUgMy42IDAgNC4yNyAyLjM3IDQuMjcgNS40NnY2LjI4ek01LjM0IDcuNDNhMi4wNiAyLjA2IDAgMSAxIDAtNC4xMyAyLjA2IDIuMDYgMCAwIDEgMCA0LjEzek03LjEyIDIwLjQ1SDMuNTZWOWgzLjU2djExLjQ1ek0yMi4yMiAwSDEuNzdDLjc5IDAgMCAuNzcgMCAxLjczdjIwLjU0QzAgMjMuMjMuNzkgMjQgMS43NyAyNGgyMC40NWMuOTggMCAxLjc4LS43NyAxLjc4LTEuNzNWMS43M0MyNCAuNzcgMjMuMiAwIDIyLjIyIDB6Jy8%2BPC9zdmc%2B" alt="LinkedIn">
  </a>
  <a href="mailto:manuel.beardo115@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>
</p>
