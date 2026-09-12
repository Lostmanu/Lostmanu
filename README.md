<h1 align="center">Manuel Beardo Campo</h1>

<p align="center">
  <b>Independent researcher · Spain</b><br>
  I run small research programmes and try to break my own results before anyone else can.
</p>

<p align="center">
  <a href="https://github.com/Lostmanu/ninety-three-wrong-claims">
    <img src="https://img.shields.io/badge/reproducible-clone%20and%20run-2E7D32?style=for-the-badge" alt="reproducible">
  </a>
  <img src="https://img.shields.io/badge/null%20results-published-455A64?style=for-the-badge" alt="null results published">
</p>

---

## 📌 Ninety-Three Wrong Claims

A six-month quantitative research programme on crypto perpetual-futures microstructure. It asked whether a
slow participant could extract systematic edge, and **it could not**. So I published the other thing it
produced: a register of every claim the programme made that later turned out to be false, with the person or
instrument that caught each one named.

```bash
git clone https://github.com/Lostmanu/ninety-three-wrong-claims
cd ninety-three-wrong-claims
python tools/recuento_auditoria.py --check
```

That command parses the register's own tables and prints the count. Nobody types the number: a tool
regenerates it, and refuses to run if two entries share an id. That control exists because the count once
said three different figures at once in the same document.

| who or what caught it | entries |
|---|---:|
| an external human reviewer | 35 |
| the author, on re-measuring | 25 |
| an automated adversarial review | 12 |
| the mutation harness | 9 |
| ten further labels | 12 |
| **total** | **93** |

The programme's single positive estimate, about +18 basis points, met a review protocol that had been frozen
months earlier. All eight of its lenses returned a threat that applies and the verdict was destroyed. The
estimate was retired. That is in the repository too, with the dates.

**[→ Read the register, the paper and the tool](https://github.com/Lostmanu/ninety-three-wrong-claims)**

---

## 🔧 What I work with

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
</p>

Those are the tools the work above actually used: a data collector running unattended on a rented Linux
server, an analysis tree in Python with 476 tests, and a continuous-integration job that runs six checks in
72 seconds and fails closed.

---

## 🧪 How I work

- **Preregistration before data.** What counts as success is written and committed before the numbers exist.
- **Controls that prove they bite.** Every guard has a row that breaks one line of source and requires a
  named test to fail. If no test fails, the guard is decorative and the harness says so.
- **The number is not typed by the person reporting it.** A tool emits it with the command that produced it.
- **The register.** Every claim of mine that turned out to be false gets written down, before it is fixed,
  with who caught it. Including the ones nobody would ever have known about.

I work with AI systems, which write code and audit it. Most of the entries in that register are theirs. That
is the point of keeping it.

---

## 📫 Contact

<p>
  <a href="https://www.linkedin.com/in/manuel-beardo-campo-804a9b201/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:manuel.beardo115@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

<p align="center"><sub>Everything here is unfunded, unaffiliated and not peer reviewed. The register is the honest part.</sub></p>
