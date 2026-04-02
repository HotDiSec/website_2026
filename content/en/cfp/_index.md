---
title: "Call for Papers"
# menu:
#   main:
#     weight: 10
---

__Authors are invited to submit original papers in PDF format to the [submission website](TBD).__

## 📃 Submission Type

HotDiSec provides a premier platform for sharing high-impact research, rigorous critiques, and forward-looking discussion papers. We invite researchers and practitioners to submit contributions in the following categories:
- **Full or short research papers:** providing thorough insights into technical challenges, novel attacks, and robust defenses in the design and deployment of distributed ML systems. Full papers should be limited to *16 pages* (excluding refrences and appendices), while short papers should be limited to *6 pages* (excluding references and appendices).
- **Position papers:** offering constructive critiques of the security assumptions in state-of-the-art distributed ML frameworks or their implementation in adversarial real-world scenarios.
- **Experimental evaluation papers:** presenting empirical studies on the (un)successful or unexpected performance of security primitives (e.g., trusted execution environments, multi-party computation, homomorphic encryption, etc.) in distributed learning.
- **System and report papers:** presenting valuable "lessons learned" from deploying secure distributed ML in production or large-scale testbeds.

## 📋 Submission Guidelines

HotDiSec follows the submission standards of the main conference. The guidelines in a nutshell are:
- Sumbissions should be in **[ESORICS Latex LNCS format](https://www.springer.com/gp/computer-science/lncs/conference-proceedings-guidelines)**;
- Submissions must be exported in PDF format;
- Submissions must not exceed **16 pages (excluding references and appendicies) and 20 pages upmost**;
- Submissions must be anonymised for **double-blind** review.

## 🔬 Topics of Interest

We invite submissions on "hot" topics solicited as position papers, "lessons learned" from negative results, and novel research contributions on topics including, but not limited to:
1. **Attacks and defenses in distributed ML**
    - Data poisoning in federated and split learning
    - Model poisoning in federated and split learning
    - Backdoor attacks in federated and split learning
    - Sybil attacks against decentralized learning
    - Consensus vulnerabilities in decentralized learning systems
    - Evasion attacks targeting distributed inference
    - Byzantine-robust aggregation protocols 
    - Fault-tolerant learning
    - Robustness of foundation models and LLMs over distributed networks
 
2. **Privacy-preserving distributed ML**
    - Gradient leakage attacks in federated learning
    - Model inversion attacks in federated learning
    - Differential privacy in distributed settings
    - Secure multi-party computation for distributed ML
    - Homomorphic encryption for distributed ML
    - Trusted execution environments for distributed ML
    - Hardware-assisted security for edge training
    - Zero-trust architectures distributed ML
    - Scalability of cryptographic protocols in federated learning

3. **Distributed ML for Security Applications**
    - Distributed intrusion detection systems
    - Collaborative malware detection
    - Collaborative threat intelligence
    - Privacy-preserving anomaly detection

## 📝 Reviewing Format

Each submission, regardless of type, will undergo a traditional double-blind review process. Additionally, all papers will go through the standard assessment in which reviwers will be asked to consider the submission focusing on its:
- **scope:** is the paper on-topic w.r.t. the workshop’s track or theme?
- **significance:** is the proposed idea relevant for the community?
- **soundness:** is the approach proposed in the paper correct and robust? Are experiments (if any) well-designed?
- **clarity:** is the paper clear and well organized? Is the discussion complete?
- **contextualization:** is relevant background and related literature being adequately referenced?
- **novelty:** is the contribution novel either from a conceptual or technical perspective?

<!-- ## 📖 Camera-ready papers

> Accepted papers will be included in the workshop proceedings __only if__ the authors explicitly agree to do so. 
In this way, works which are not mature enough for publication, as well as works which have already been published elsewhere can be presented and discussed at the workshop.

### Web-site CR

__All__ papers will have to produce a _web-site_ camera-ready version addressing reviewers' comments.
Updated PDFs will have to be submitted on EasyChair by updating the original submission.

The purpose here is to create a shared folder for all accepted papers,
to be accessed by all (and only) the workshop participants.

No need to perform any big stylistic change, and no need to be strict about page limitations in this phase.

### Proceedings CR 

The workshop will publish its own proceedings as [CEUR-WS](https://ceur-ws.org/) volume.
All accepted papers' authors will be asked if they agree to include their paper in the proceedings.
Default is **yes**.

In any case, proceedings production will occur __after__ the workshop,
so that authors will be able to incorporate feedback received during the event.

#### Important details for typesetting your paper for publication

Page limitations constraints are mild on CEUR,
but the authors who are willing to include their papers in the proceedings
will have to adhere to the [formatting guidelines specified by CEUR-WS](https://ceur-ws.org/HOWTOSUBMIT.html).

1. Use the CEUR template, last version. The only admissible sources are:
    - [Overleaf template](https://www.overleaf.com/latex/templates/template-for-submissions-to-ceur-workshop-proceedings-ceur-ws-dot-org/wqyfdgftmcfw)
    - [GitHub](https://github.com/yamadharma/ceurart)

2. Use the __2 column__ layout. In other words, your class definition in LaTeX should be:
    ```latex
    \documentclass[twocolumn]{ceurart}
    ```

3. Recall to set the Copyright Clause correctly in the LaTeX source files:
    ```latex
    \copyrightyear{2025}
    \copyrightclause{Copyright for this paper by its authors.
    Use permitted under Creative Commons License Attribution 4.0 International (CC BY 4.0).}
    ```

4. Recall to set the conference name as follows:
    ```latex
    \conference{
       ANSyA 2025: $1^{st}$ International Workshop on Advanced Neuro-Symbolic Applications,
       co-located with ECAI 2025.
    }
    ```

5. Capitalize your titles (there including section titles) coherently, and capitalize all major words. Example:
    - ✅ Good Title: `A Study on the Impact of X on Y`
    - ❌ Bad Title: `A study on the impact of x on y`

6. Prefer vectorial formats for pictures (e.g., SVG, PDF) over raster formats (e.g., PNG, JPEG).

7. Pay attentions to your bibliography section: prefer DOIs over URLs, and only use one of them if both are available.

8. Let the corresponding author prepare a signed copy of the [copyright form](https://ceur-ws.org/ceur-author-agreement-ccby-ntp.pdf)
    - _do not compile it digitally_: __you must print it, sign it, and then scan it as a PDF file__. -->