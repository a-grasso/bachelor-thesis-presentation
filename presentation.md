---
marp: true
theme: uncover
class: invert
----

presentation 09.03.2023

# Construction of a software solution for detection of end-of-support dependencies

---

- ***Context***: 
dependency management
<br>
- ***Goal***:
tooling to problem-solve
<br>
- ***Demarcation***:
not full-fletched, rather pioneering

---

# Problem Definition

---

- ***Focus***:
end-of-support dependencies

---

- ***Why***:
risk, expense & cost
in management, development & planning

---

... e.g. **issues** with, and **concerns** about
<br>
- common vulnerabilities and exposures
    - compliance
- stability
    - bugs without fixes or patches
- compatibility
    - out-datedness and actuality

<br>

***-> risk***

---

... **consequenting** 
<br>
- replacement

- upgrades

- independent fixes and patches

<br>

***-> expense & cost***

---

- ***Solution***:
mitigating the impact of consequences 
from end-of-support dependency

---

# Methods

---

- ***What***:
a software solution 
to detect end-of-support dependencies

---

- ***How***:
conception &rarr; requirements &rarr; design &rarr; implementation &rarr; evaluation

---

# Results

---

- Theoretical Concept 
<br>
- Requirements Analysis
<br>
- Technical Concept
<br>
- ***deprec*** / ***deprec-cli***

---

# Theoretical Concept

---

***EOS Abstraction Framework***
<br>

![width:1000px](images/eos-factors.png)

---

***EOS Factor*** |&rarr; ***Statements*** |&rarr; ***Signals & Metrics***

---

# Requirements Analysis

---

- applicability in practice
<br>
- suitability for effective use
<br>

***-> project-based & automation***

---

- achieve continuance
<br>
- enable further proceedings
<br>

***-> independence***

---

# Technical Concept

---

- software bill of materials (sboms)
&rarrhk; [CycloneDX](https://cyclonedx.org/)

---

- extraction

---

![width:1000px](images/extraction.png)

---

- data model

---

- combination and conclusion

( EOS Abstraction Framework )

---

# deprec

---

- integrating the **theoretical** concept
<br>
- implementing the **technical** concept

---

# [open source](https://github.com/a-grasso/deprec)

---

written in
<br>

![width:500px](images/golang.png)

---

supporting dependencies
from
<br>

![width:800px](images/maven.png)

---

extracting data
from
<br>

![width:300px](images/github.svg)
## GitHub

---

extracting data
from
<br>

![width:1000px](images/sonatype.png)

---

# deprec-cli

---

```bash
$> deprec-cli <sbom> <opts>
```

---

# [open source](https://github.com/a-grasso/deprec-cli)

---

written in
<br>

![width:500px](images/golang.png)

--- 

# THANKS 
