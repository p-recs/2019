---
title: ''
feature_text: |
  ## P-RECS 2019
  2nd International Workshop on Practical Reproducible Evaluation of 
  Computer Systems.

  June 25, 2018. In conjunction with [HPDC'18](http://hpdc.org/2018/). 
  In cooperation with:

  ![[In cooperation with ACM](http://www.acm.org)](assets/acm-in-cooperation.png)      ![[In cooperation with SIGHPC](http://www.sighpc.org)](assets/sighpc.png)
feature_image: ""
excerpt: "This workshop is going to be fun."
---

This workshop will focus heavily on practical, actionable aspects of 
reproducibility in broad areas of computational science and data 
exploration, with special emphasis on issues in which community 
collaboration can be essential for adopting novel methodologies, 
techniques and frameworks aimed at addressing some of the challenges 
we face today. The workshop will bring together researchers and 
experts to share experiences and advance the state of the art in the 
reproducible evaluation of computer systems, featuring contributed 
papers and invited talks.

## Topics

We expect submissions from topics such as, but not limited to:

  * Experiment dependency management.
  * Software citation and persistence.
  * Data versioning and preservation.
  * Provenance of data-intensive experiments.
  * Tools and techniques for incorporating provenance into publications.
  * Automated experiment execution and validation.
  * Experiment portability for code, performance, and related metrics.
  * Experiment discoverability for re-use.
  * Cost-benefit analysis frameworks for reproducibility.
  * Usability and adaptability of reproducibility frameworks into already-established domain-specific tools.
  * Long-term artifact archiving for future reproducibility.
  * Frameworks for sociological constructs to incentivize paradigm shifts.
  * Policies around publication of articles/software.
  * Blinding and selecting artifacts for review while maintaining history.
  * Reproducibility-aware computational infrastructure.

## Submission

Submit (single-blind) via 
[EasyChair](https://easychair.org/conferences/?conf=precs18). We look 
for two categories of submissions:

  * **Position papers**. This category is for papers whose goal is to 
    propose solutions (or scope the work that needs to be done) to 
    address some of the issues outlined above. We hope that a research 
    agenda comes out of this and that we can create a community that 
    meets yearly to report on our status in addressing these problems.

  * **Experience papers**. This category consists of papers reporting 
    on the authors' experience in automating one or more 
    experimentation pipelines. The committee will look for submissions 
    reporting on their experience: what worked? What aspects of 
    experiment automation and validation are hard in your domain? What 
    can be done to improve the tooling for your domain? As part of the 
    submission, authors need to provide a URL to the automation 
    service they use (e.g., [TravisCI](https://travis-ci.org), 
    [GitLabCI](https://about.gitlab.com/gitlab-ci/), 
    [CircleCI](https://circleci.com), 
    [Jenkins](https://jenkins-ci.org), etc.) so reviewers can verify 
    that there is one or more automated pipelines associated to the 
    submission.

### Format

Authors are invited to submit manuscripts in English not exceeding 5 
pages of content. The 5-page limit includes figures, tables and 
appendices, but does not include references, for which there is no 
page limit. Submissions must use the [ACM Master 
Template](https://www.acm.org/publications/proceedings-template) 
(please use the `sigconf` format with default options).

### Proceedings

The proceedings will be archived in both the ACM Digital Library and 
IEEE Xplore through SIGHPC.

### Tools

These tools can be used used to automate your experiments (not an 
exhaustive list): [CWL](http://commonwl.org), 
[Popper](https://github.com/systemslab/popper), 
[ReproZip](http://reprozip.org), [Sciunit](http://sciunit.run), 
[Sumatra](https://github.com/open-research/sumatra).

<!--
## Accepted Papers

* Abdulqawi Saif, Alexandre Merlin, Lucas Nussbaum, and Ye-Qiong Song. 
  _MonEx: An Integrated Experiment Monitoring Framework Standing on 
  Off-The-Shelf Components_.

* Quan Pham, Tanu Malik, Dai Hai Ton That, and Andrew Youngdahl. 
  _Improving Reproducibility of Distributed Computational 
  Experiments_.

* Victoria Stodden, Matthew S. Krafczyk, and Adhithya Bhaskar. 
  _Enabling the Verification of Computational Results: An Empirical 
  Evaluation of Computational Reproducibility_.

* Michael A. Sevilla and Carlos Maltzahn. _Popper Pitfalls: 
  Experiences Following a Reproducibility Convention_.

* David Wilkinson, Luís Oliveira, Daniel Mossé, and Bruce Childers. 
  _Software Provenance: Track the Reality Not the Virtual Machine_. 

* Luís Oliveira, David Wilkinson, Daniel Mossé, and Bruce Childers. 
  _Supporting Long-term Reproducible Software Execution_.

## Program

### Schedule

| |
|-|
| `07:30-08:45` - Breakfast |
| `08:45-09:00` - Welcome |
| `09:00-10:00` - Keynote (Dr. Fatma Deniz) |
| `10:00-10:30` - Coffee break |
| `10:30-10:45` - Lightning talks |
| `10:45-12:00` - Paper Presentations 1 |
| `12:00-13:00` - Lunch (hosted by HPDC) |
| `13:00-14:30` - Paper Presentations 2 |
| `14:30-15:00` - Coffee break |
| `15:00-16:00` - Panel (Moderator: Victoria Stodden) |
| `16:00-17:00` - Poster session |

### Paper Session 1 (chair: Jay Lofstead)

 1. Abdulqawi Saif, Alexandre Merlin, Lucas Nussbaum, and Ye-Qiong 
    Song. An Integrated Experiment Monitoring Framework Standing on 
    Off-The-Shelf Components.
 2. Luís Oliveira, David Wilkinson, Daniel Mossé, and Bruce Childers. 
    Supporting Long-term Reproducible Software Execution.
 3. Quan Pham, Tanu Malik, Dai Hai Ton That, and Andrew Youngdahl. 
    Improving Reproducibility of Distributed Computational 
    Experiments.

### Paper Session 2 (chair: Carlos Maltzahn)

 1. Jay Jay Billings. Applying Distributed Ledgers to Manage Workflow 
    Provenance.
 2. David Wilkinson, Luís Oliveira, Daniel Mossé, and Bruce Childers. 
    Software Provenance: Track the Reality Not the Virtual Machine.
 3. Victoria Stodden, Matthew S. Krafczyk, and Adhithya Bhaskar. 
    Enabling the Verification of Computational Results: An Empirical 
    Evaluation of Computational Reproducibility.
 4. Michael A. Sevilla and Carlos Maltzahn. Popper Pitfalls: 
    Experiences Following a Reproducibility Convention.

### Keynote Address

{% include figure.html image="assets/fatma.png" position="left" %}

<small>
**Abstract**: Establishing generalizable findings from systematic 
empirical observations is at the core of the modern scientific method. 
Reproducible research practices can help scientists arrive at results 
that flourish new theories and technological advances. Importantly, it 
enables the scientific community to corroborate published results and 
theories. In my talk, I will start by introducing reproducibility and 
what it means to aim reproducible research practices. I will then 
present technical tools and data science practices that can 
incorporate reproducible research in a scientist’s everyday workflow. 
I will discuss how we can use these tools and practices to conduct 
large-scale data exploration and computational science by introducing 
case studies from data-intensive sciences. I will finish my talk by 
providing my account of reproducible research, where I will present a 
web-based replication engine 
(<https://boldpredictions.gallantlab.org>) that uses data derived from 
naturalistic neuroimaging experiments to simulate a variety of 
language experiments.
</small>
<small>
**Bio**: [Dr. Fatma 
Deniz](https://bids.berkeley.edu/people/fatma-imamoglu) is a 
Moore-Sloan Data Science Fellow in [Berkeley Institute for Data 
Science](http://bids.berkeley.edu/), a Postdoctoral-Fellow in [Dr. 
Jack Gallant’s laboratory](http://gallantlab.org/) ([Helen Wills 
Neuroscience Institute](http://neuroscience.berkeley.edu/)) at the 
University of California, Berkeley and a visiting scientist at the 
Technical University Berlin. She is interested in how sensory 
information is encoded in the brain and uses machine-learning 
approaches to fit computational models to large-scale brain data. Her 
current work focuses on cross-modal language representation in the 
human brain. She did her PhD in [Dr. John-Dylan Haynes’s 
laboratory](https://sites.google.com/site/hayneslab/home) at Bernstein 
Center for Computational Neuroscience and Technical University Berlin, 
where she studied functional connectivity changes during conscious 
perception in humans. She got a bachelor’s and master’s degrees in 
Computer Science from the Technical University Munich. During her 
master’s work, Dr. Deniz worked with [Dr. Christof 
Koch](http://www.klab.caltech.edu/koch) at Caltech, where she studied 
visual saliency and automated text detection. As an advocate of 
reproducible research practices, she is the editor of the book titled 
“The Practice of Reproducible Research”. In addition, she works on 
improving Internet security applications using knowledge gained from 
cognitive neuroscience and Mooney images 
([mooneyauth.org](http://mooneyauth.org/)). Her work is at the 
intersection between computer science, human cognition, and 
neuroscience. She is a passionate coder, baker and loves playing the 
cello.
</small>

## Registration

To register for the workshop, go to the [HPDC registration 
page](http://www.hpdc.org/2018/registration/).

## Important Dates

  * Submissions due: ~~April 2~~ April 9, 2018 (AoE)
  * Acceptance notification: April 30, 2018
  * Camera-ready paper submission: May 8, 2018
  * Workshop: June 11, 2018
-->

## Organizers

  * [Ivo Jimenez](http://ivotron.me), UC Santa Cruz
  * [Carlos Maltzahn](https://users.soe.ucsc.edu/~carlosm/), UC Santa 
    Cruz
  * [Jay Lofstead](http://www.lofstead.org), Sandia National 
    Laboratories

## Program Committee

**TBD**

## Contact

Please address workshop questions to <ivo@cs.ucsc.edu>.

