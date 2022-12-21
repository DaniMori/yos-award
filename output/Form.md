---
title: Yerun Open Science Award form
editor_options:
  markdown:
    canonical: false
---

# Team

Roberto Mediavilla has a PhD in psychology and coordinates epidemiological and
intervention studies to reduce the mental health burden of the COVID-19 pandemic
among vulnerable groups. He submits this application on behalf of the World
Health Organization Collaborating Centre for Mental Health Services Research and
Training, a research group lead by José Luis Ayuso-Mateos and based at the
Department of Psychiatry, Universidad Autónoma de Madrid (Spain). 
Our main motivation is to keep working together on producing fully reproducible
scientific outputs and processes. To achieve this aim, our group comprises the
following collaborators from our research lab:
María Cabello-Salmerón. Psychologist and PhD in psychiatry. She is an
international expert in analysing the impact of mental disorders on work
disability. She is also working on bridging digital skills gaps in people with
severe mental disorders.
Daniel Morillo-Cuadrado. PhD in Clinical Psychology, with a focus in
quantitative methods; he also has a degree in telecom engineering, and some
experience in the private sector working with frontend development, relational
databases, and linux-based servers. 
Cristina Rodríguez-Prada. MSc in quantitative methods in Psychology and mental
health research and works as a research assistant doing database processing with
programming software (e.g., R, Stata). 
Lea Francia. PhD candidate. She explores how to improve the pharmacological care
of people with depression based on an analysis of the adequacy of prescriptions
and diagnostic tools. 
Jesús Sierralaya. MSc on statistical methods applied to behavioural research. He
uses this knowledge to build behavioural and cognitive models using R.


# Description: What is the Open Science practice/initiative about?

*Please provide information as to the following aspects (as applicable):*

-   [*Introduction*]{.underline}\*: short overview of the initiative. What are
    its key Open Science objectives (and others, if applicable)? Who are the
    target groups? What are the main activities organised?*

-   [*Context*]{.underline} *in which the initiative was implemented: What
    prompted you to develop this initiative?*

-   [*Obstacles and solutions*]{.underline}*: What challenges, if any, were
    encountered? Were they/how were they solved?*

The European Commission has started to adhere to open access guidelines. Our
group is or has been involved in nearly ten international projects funded by the
European Union. We have developed our methodology for reproducibility in two
recent projects, with the aim of standardizing it, and disseminate it to other
groups. Therefore, our target audience will ultimately be the whole scientific
community.

Our proposal consists of implementing a full open science workflow, reusable
across research projects and exportable to other groups. The aim is not only to
produce reproducible research outputs, but to make the whole scientific
production process reproducible: We want to make the historical of the
scientific process itself completely transparent and reproducible by documenting
all the progress and decisions made along the way. We implement this using three
technologies: open data management, literate computing, and version control.
Open data management is implemented by means of the Opal technology (a
Linux-based server), which enables data sharing with a controlled interface
without disclosing sensitive, personal data. Literate computing is implemented
with the Rstudio environment and associated components ("de facto" standards
such as the Rmarkdown format and the Knitr engine). It allows editing all
research outputs in text format, combining data analyses and natural language to
produce e.g. manuscripts. Version control is implemented via Git (and Github
service) by using text files exclusively.

Although these technologies made it possible to manage projects in a completely
reproducible way, some challenges still remain. First, both Opal and Git require
a high level of expertise. Consequently, we often consult with experts in other
fields or investigate our own solutions, and we are currently implementing
training sessions on literate computing ecosystem and version control
management. Second, the literate computing framework does not ensure full
automation, and requires both evaluating the level of automation and documenting
the manual steps required for reproducing the output (if not automated) -in a
previous work, we managed to achieve 99% of automation, with only four minor
steps performed manually before submitting a manuscript to a scientific journal.
Last, many researchers are reluctant to adopt these technologies. When this
happens, we adapt our workflows to the needs of the other researchers involved,
while putting formative actions in place to help bridge that resistance gap.

# Outputs: What has the initiative achieved so far?

*Please provide information as to the following aspects (as applicable):*

-   [*Benefits*]{.underline}*: What benefits were realised (to date) through
    this initiative, and for whom?*
-   [*Lessons learnt*]{.underline}*: What knowledge have you gained (so far)
    through your work?*

As an international research group and a World Health Organization's
collaborating centre, we
work daily with researchers and professionals living abroad. This requires tools
that help tracking exchanges between labs in a comprehensive way, such as
statistical code, manuscript drafts, or meeting minutes. By taking this
approach, we aim at developing a stronger open science practice not only within
our lab, but also across different research consortia in the European Union
(EU). We are currently in a test phase of implementing this open science way of
working in our research group. This may potentially spread through different
institutes in the region and improve reproducibility rates for the whole
research community. For example, in the EU-funded project RESPOND, we have
already published open-access manuscripts to inform mental and occupational
health policies for vulnerable populations during the COVID-19 pandemic,
especially HCWs. Soon, we will report the RCT results and make the code
available. This will allow researchers to have full access not only to the
results of the study but also to how the study developed.

In the context of the COVID-19 pandemic, preprints increased, journals had
open-access policies, etc. In a rapidly changing world, with the climate crisis,
wars, etc., research should (and will) move rapidly and collaboratively. This
requires training and collaboration, which is why we apply for this grant. One
powerful tool that makes national and international collaboration possible is
the Obiba Software. We currently use this open-source software on the RESPOND
project to conduct federated analyses of different epidemiological cohort
studies (software DataShield and R) while data is securely stored in local
servers (software Opal). In this project, we also anonymised our datasets to
comply with the General Data Protection Regulation of the EU.
Because a common anonymisation process across datasets was not possible due to
the sensitive nature of the data, we used scripts in R, Stata, and SPSS, to keep
the anonymisation as reproducible as
possible at all sites. One of the main benefits of developing this
practice is having a complete history accessible to all. This increases the
transparency of a study and facilitates communication. Moreover, it is an
interesting tool for researchers themselves. Indeed, having this history allowed
us to keep in writing what was done, what worked but also what led to mistakes.
This written trace allowed us both to save time and avoid reproducing the same
mistake.

# Reusability: What steps have been taken for others to reuse this initiative?

*Please provide information as to the following aspects (as applicable):*

-   *What are the steps you have taken/are taking to make the initiative
    available to others?*

-   *Is the practice, its structure and output, easily findable online? If yes,
    where?*
    
-   *Can the practice be reused in other departments or institutions?*

We will record all the steps taken so that anyone can use and/or adapt them,
regardless of their level of expertise We are currently training people in our
lab on tools that potentially increase transparency and overall compliance with
open science requirements in relation to our scientific production. These are
some examples:

-   We developed a template for R Studio projects that is used across different
    repositories (https://github.com/DaniMori/rproj-template).
-   We use version control provided by GitHub.
-   We use remote servers, including one hosted by the Scientific Computation
    Centre at the Universidad Autónoma de Madrid.
-   We use the free, open-source software Opal to host our datasets.
-   We use the free, open-source software DataShield to perform federated.
    analyses of multiple datasets while keeping sensitive data securely stored
    at each institution.

In this way, each member of the group knows how to implement changes to
manuscript versions and programming code, and where to look for track records of
changes, so that everything could be accounted for. We get this experience from
two projects, namely RESPOND (https://respond-project.eu/es/) and SYNCHROS
(https://synchros.eu/), and we try to use it at all research stages (e.g.,
from meetings' minutes to manuscript writing). Our latest project is this
application, which is currently being prepared on RStudio and Github and tries
to be as compliant as possible with the Open Science framework (see here:
https://github.com/CCOMS-UAM/yos-award).

Our knowledge and expertise may already help other research groups. We will
provide support by sharing the server, training other departments, or taking the
lead on initiatives to develop an enhanced open science framework for
collaborative work. There are already materials that can be provided for this
purpose (e.g., DataShield monthly drop-in sessions:
https://data2knowledge.atlassian.net/wiki/spaces/DSDEV/overview and
https://www.youtube.com/@datashield5702/videos).

# Follow-up: How do you intend to use the award?

-   *How would this award support you / your team in taking forward your current
    initiative, or would you like to initiate a new project with the financial
    resources from the award?*

Our aim is to embed all our scientific production within this workflow,
leveraging as much as possible on open science practices from beginning to end.
In order to this, we want to dig further into our understanding and know-how of
data access management with Opal (and the Obiba suite in general), literate
computing, and version control with git/GitHub. All these technologies enable
creating reliable reproducible workflows, but learning to navigate them is time-
and effort-consuming; we need to draw our knowledge from the field of software
engineering and computer science, and then adapt it and translate it to the
needs and particularities of scientific production.

We are currently in what we could call a "maturing" phase of our
skill-development process with these technologies. Before we are able to expand
our best practices outside our own group, we need to consolidate our knowledge,
for which we require further training. We would allocate the prize for training
in the use of these technologies. We would like to develop an expertise that can
then be translated into formative actions that can be exported to the rest of
lab members and research communities. Thus, we believe the prize may be a great
opportunity to invest in this first stage of specific, mid- to high-level
training. Courses related to using git / Github
(https://swcarpentry.github.io/git-novice/),
DataShield(https://data2knowledge.atlassian.net/wiki/spaces/DSDEV/pages/12943395/Beginners+Hub),
Opal administration (https://opaldoc.obiba.org/en/latest/cookbook/index.html)
and Linux server administration
(https://www.cbtnuggets.com/it-training/linux/server-administration). This
would be the first step towards taking a broader action that can be spread
throughout the scientific community.
