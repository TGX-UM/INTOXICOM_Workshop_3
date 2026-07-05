---
title: 'INTOXICOM Workshop Report: Making toxicology tools more accessible and interoperable'
title_short: 'INTOXIOM #3: FAIR toxicology tools'
tags:
  - computational toxicology
  - FAIR
  - toxicology
authors:
  - name: Meike&nbsp;Bünger
    affiliation: 1
    orcid: 0009-0002-7664-0058
  - name: Ola Spjuth
    affiliation: 2
  - name: Jonne&nbsp;Rietdijk
    affiliation: 3
    orcid: 0000-0003-3799-6684
  - name: Jente&nbsp;Houweling
    affiliation: 4, 11
    orcid: 0009-0005-3680-0645
  - name: Wolmar Nyberg Åkerström
    affiliation: 5, 6, 7
    orcid: 0000-0002-3890-6620
  - name: Penny&nbsp;Nymark
    affiliation: 8
    orcid: 0000-0002-3435-7775
  - name: Petru Niga
    affiliation: 9
    orcid: 0000-0003-0195-3850
  - name: Cleo Tebby
    affiliation: 10
    orcid: 0000-0003-3470-157X
  - name: Egon&nbsp;Willighagen
    affiliation: 11
    orcid: 0000-0001-7542-0286
affiliations:
  - name: Stichting Health-RI, Utrecht, NL
    index: 1
    ror: h8qdw
  - name: Uppsala University, Sweden
    index: 2
    ror: 048a87296
  - name: Dept of Pharmaceutical Biosciences and Science for Life Laboratory, Uppsala University, Uppsala, Sweden 
    index: 3
  - name: RIVM, Bilthoven, The Netherlands
    index: 4
  - name: National Bioinformatics Infrastructure Sweden
    index: 5
    ror: 00enajs79
  - name: Science for Life Laboratory, Sweden
    index: 6
    ror: 04ev03g22
  - name: Uppsala University, Uppsala, Sweden
    index: 7
    ror: 048a87296
  - name: Institute of Environmental Health, Karolinska Institutet, Stockholm, Sweden, Sweden
    index: 8
    ror: 056d84691
  - name: Chemical Processes and Pharmaceutical Development, RISE Research Institute of Sweden
    index: 9
  - name: Experimental and Modelling Team, Ineris, rue Jacques Taffanel, 60550 Verneuil-en-Halatte, France
    index: 10
  - name: Dept of Translational Genomics, Maastricht University, Maastricht, NL
    index: 11
    ror: 02jz4aj89
date: 26 march 2025
cito-bibliography: paper.bib
event: INTOXICOM
biohackathon_name: "INTOXICOM Workshops"
biohackathon_url:   "https://elixir-europe.org/internal-projects/commissioned-services/integrating-toxicology-community"
biohackathon_location: "Uppsala, 26-27 Mar 2025"
group: Workshop 3
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/TGX-UM/INTOXICOM_Workshop_3/
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Bünger \emph{et al.}
---


# Introduction

As part of the INTOXICOM Implementation Study for the ELIXIR Toxicology Community a series of workshops is organized [@citesAsRecommendedReading:citesAsEvidence:Martens2024INTOXICOM]. Here, we here report on the 3rd workshop, titled "Making toxicology tools more accessible and interoperable"
which was held from 26 to 27 March 2025 at the SciLifeLab at Uppsala University in Sweden.

The workshop welcomed 29 participants from Sweden, The Netherlands, Cyprus, Switzerland,
Italy, Greece, France, and Norway. This 3rd INTOXICOM workshop covered various aspects of making computational tools available and how they are used. Several projects, such
as NanoSolveIT [@obtainsBackgroundFrom:Afantitis2020NanoSolveIT],
ONTOX [@obtainsBackgroundFrom:Vinken2021Safer],
and VHP4Safety [@obtainsBackgroundFrom:Kienhuis2024Virtual],
already make computational toxicology services available, but the field of integrating
computional toxicology dates back much longer, such as Bioclipse developed at Uppsala 
University [@obtainsBackgroundFrom:Willighagen2011Computational], making it a perfect
location to have held this workshop.

## Presentations

Organizers and invited speakers held several presentation to provide information to
support the workshop, scheduled as part of sessions hosted by Ola Spjuth and
Egon Willighagen:

| Speaker | Talk Title  |
| --- | -------- |
| Egon Willighagen | ELIXIR Introduction |
| Jonne Rietdijk | User perspective: Morphological Profiling for Chemical Toxicity Assessment |
| Ivo Djidrovski | Large Language Model tools and AI-Agents  in toxicology research |
| Antreas Afantitis | NovaMechanics platforms:  NanoSolveIT, Enalos Cloud, Pharos DMS |
| Ziye Zheng | Toxicity prediction with regulatory relevance: predicting the CLP H-statement |
| Egon Willighagen | Toxicity prediction with regulatory relevance: predicting the CLP H-statement |
| Nikita Churikov | Sharing and serving ML models in toxicology research with SciLifeLab Serve |
| Jente Houweling | VHP4Safety project for data/tool integration |

# Results

After a *Welcome at SciLifeLab* by Ola Spjuth and an overview of ELIXIR Europe,
the INTOXICOM workshop, and the schedule of the workshop, the first session what
about *What tools for toxicology exist?*. The focus of this session was aimed
at relevent services indexed by the ELIXIR Toxicology Community on bio.tools
for computational tools and FAIRsharing for databases:

* [bio.tools records annotated with toxicology](https://bio.tools/t?page=1&q=%27Toxicology%27&sort=score)
* [FAIRsharing's toxicology collection](https://fairsharing.org/3496/)

The participants that several services were missing in the collection of 103
tools found in bio.tools, including [VHP4Safety services](https://cloud.vhp4safety.nl/),
[TXG-MAPr](https://txg-mapr.eu/), [BMDExpress](https://github.com/auerbachs/BMDExpress-3),
the [Enalos Cloud Platform](https://enaloscloud.novamechanics.com/all.html),
OPERA and VEGA, [EFSA tools](https://r4eu.efsa.europa.eu), and
https://www.parc-models.eu/tools/.

The FAIRsharing collection was already discussed at the second INTOXICOM workshop
[@citesForInformation:BonattoMinella2026INTOXICOM] and futher curated by Bonatto Minella
*et al.* [@citesForInformation:BonattoMinella2025]. During the workshop several
databases were found to be missing, including ToxVal, ToxRef, ToxCast,
[AOP-Wiki](https://aopwiki.org/), [ECHA CHEM](https://chem.echa.europa.eu/),
[Nanosafety Data Interface](https://enanomapper.adma.ai/), [GenRA](https://bio.tools/genra-py),
[chemPharos](https://db.chempharos.eu/datasets/Datasets.zul),
[RepDose Database Fraunhofer ITEM](https://repdose.item.fraunhofer.de/), and
[Le Portail Substances Chimiques (PSC)](https://substances.ineris.fr/le-portail-substances-chimiques).

In the afternoon, the second session consisted of three user stories on
data and tools in the session *How to make your data integrate with tools?*,
chaired by Ola. The first story was given by Jonne Rietdijk on morphological
profiling for chemical toxicity, proposed for toxicology testing in 2010 [@discusses:Krewski2010Toxicity]. Riedijk walked the participants through various
approaches, such as cell painting. Data was shared on Figshare [@discusses:Rietdijk2022],
comparing effects of exposure to cetyltrimethylammonium bromide, bisphenol A,
and bibutyltin dilaurate in several human cell lines. Images can be shared
with OMERO [@citesForInformation:Allan2012OMERO], which has advantages over
the more general Figshare.

The story provided by Ivo Djidrovski describes the rapid progress of large
language models (LLMs). His work focuses on using LLM agents capabilities,
which provide access to data and knowledge bases. He demoes the use of LLMs
in a chemical hazard assistant, based on the OECD QSAR Toolbox [@citesAsRecommendedReading:djidrovski2025qt].

After a break, Antreas Afantitis descrbes the NovaMechanics platforms
NanoSolveIT, Enalos Cloud, Pharos DMS, based on 20 years of experience in
the field. [Enalos cloud](https://novamechanics.com/services-tools/enalos-cloud-platform/)
enables non-expert users to leverage ML. Model outputs are accompanied by a
workflow of what the user has performed.
The [Nanopharos](https://pharos.novamechanics.com/) database integrates
experimental data with physics-based models and machine learning.

The last user story was provided by Ziye Zheng fo the IVL Swedish
Environmental Institute. It discussed [SafeChem](https://www.ivl.se/projekt/mistra-safechem.html), the regulatory relevance, lack of negative controls,
data mining from the ECHA REACH dossiers, and computational toxicology
approaches, including molecular descriptors, fingerprints, and descriptor-free
approaches, and comparing traditional machine learning and deep learning.

During the discussion at the end of this session, the workshop participants
identified several missing things (some gaps are filled by the wider
community in the year following the workshop): model context protocols (MCPs)
for toxicology, Open API definitions, clarity and/in documentation, also
for knowledge graphs, and better interoperability standards, for example,
with FAIR Implementation Profiles.

# Discussion

...

## Acknowledgements

...

## Funding

This workshop was funded by the ELIXIR Europe INTOXICOM grant (Grant No. NL-2023-INTOXICOM).

Participants acknowledge funding from ...

## References
