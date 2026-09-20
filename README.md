### Hi there 👋, [Ivan][website] is here

<p>
My primary interests lie in Software Engineering as well as SRE, SecDevOps and SDLC
</em>
</p>

<em><a href="https://github.com/kubernetes">kubernets member</a>

<em><a href="https://github.com/kubernetes-sigs">kubernets-sigs member</a>

<em><a href="https://github.com/kubernetes-sigs/external-dns">external-dns maintainer</a>

### Connect with me:

[![Linkedin: ivankatliarchuk](https://img.shields.io/badge/-ivankatliarchuk-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ivankatliarchuk/)][linkedin]
[![Medium Badge](https://badgen.net/badge/icon/medium?icon=medium&label&color=green)][medium]
[![GitHub Ivan](https://img.shields.io/github/followers/ivankatliarchuk?label=follow&style=social)][github]

---

### **Fun Facts**

- My first coding achievement
  * 1990, OMK Software, Buran game for DOS operating system. Reverse engineer code from cassette tape to a paper.
- 1995 tried Windows 95

---

### **Platform Engineering & SRE Milestones**

- **2011** – Early adoption of Pivotal Cloud Foundry (PCF) & BOSH for cloud-native platforms for on-prem and early days hyperscalers.
- **2015** – Led the first production proof-of-concept (PoC) comparing Kubernetes and Pivotal Platform.
- **2018** – Scaled to **1,000+ applications** running across multiple Kubernetes clusters.
- **2020** – Established platforms supporting **1,000+ customers**, managing multi tenant environments.
- **2023** – Empowered **thousands of customers** to create on-demand Kubernetes clusters **as effortlessly as deploying an application**.

---

### **SecDevOps work**

- System security audits
- Defined custom system security controls and where possible automated them with Policies as Code
- Supply chain security (SLSA, NIST, ....)

---

**How I do Pull Request Reviews**
- If you tag me on pull request - you get banned for month. Tag me twice - permanent ban. This process is automated.
- Author Understanding: Code is cheap now, AI writes it and makes the tests pass, and that's not a problem, it's the process working as intended. What matters is that whoever opens the PR can explain what the code does and why. If you can't answer a question about your own PR, it's not ready.
- Evidence It Runs: Green CI is not proof. Infrastructure and test suites behave unpredictably often enough that passing checks alone don't earn trust. Show the code actually running, logs, output, a screenshot, whatever proves it works beyond the pipeline saying so.
- Simplicity: Each PR still addresses a single purpose. Focused changes are easier to review and release, whether a human or an agent wrote them
- Test Coverage: Tests matter, but as a floor, not the finish line. Passing tests plus a human who understands the change is the actual bar.

If you not agree, someone else could approve your code.

### What is wrong with AI It writes the test and the implementation in the same breath, from the same assumptions. So the test agrees with the code.

Concretely, what breaks:

  1. Shared blind spots. Any misunderstanding of the spec, edge case, or requirement gets baked into both the code and the test at the same time, by the same reasoning. The
     test can't catch what the author didn't think of, because it didn't think of it either.
  2. Tests verify implementation, not intent. Writing test and code together tends to produce a test that asserts "the code does what the code does" rather than "the code
     does what it's supposed to do." If you accidentally implement the wrong thing, the test happily confirms the wrong thing.
  3. No adversarial pressure. A test's value comes partly from someone trying to break the code, or at least approaching it skeptically, asking "what could go wrong here,
     what did I not handle." Writing both at once removes that friction, since you already believe the code works before the test exists.
  4. False confidence signal. Green tests look like verification but are actually closer to a tautology. This is dangerous specifically because it looks identical to real
     coverage from the outside, so it erodes trust in the test suite once the gap is discovered.
  5. Refactoring loses its safety net. The whole point of tests is to let you change implementation while keeping behavior fixed. If the test was derived from the
     implementation rather than the spec, it will often break on any refactor, correct or not, or worse, pass through actual regressions that happen to preserve the same
     accidental shape.

[Styleguide](https://google.github.io/styleguide/go/) and [effective-go](https://go.dev/doc/effective_go) that I use for Go projects

[PR strategies I usually follow](https://artsy.github.io/blog/2021/03/09/strategies-for-small-focused-pull-requests/)

**Recent Posts:**

 <a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@ivan.katliarchuk/0"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@ivan.katliarchuk/0" alt="Recent Article 0">

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@ivan.katliarchuk/1"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@ivan.katliarchuk/1" alt="Recent Article 1">

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@ivan.katliarchuk/2"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@ivan.katliarchuk/2" alt="Recent Article 2">

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@ivan.katliarchuk/3"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@ivan.katliarchuk/3" alt="Recent Article 3">

**Languages and Tools I Use:**

![Metrics](https://github.com/ivankatliarchuk/ivankatliarchuk/blob/metrics/github-metrics.svg)

![](https://visitor-badge.glitch.me/badge?page_id=ivankatliarchuk.ivankatliarchuk)

<!--END_SECTION:waka-->

<!--
**ivankatliarchuk/ivankatliarchuk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

[website]: https://ivankatliarchuk.github.io
[medium]: https://medium.com/@ivan.katliarchuk
[linkedin]: https://www.linkedin.com/in/ivankatliarchuk
[github]: https://github.com/ivankatliarchuk
