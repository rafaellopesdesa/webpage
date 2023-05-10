---
title: "Research"
date: 2022-11-26T19:41:00-5:00
weight: 1
---

Current and past research projects. I am a member of the [ATLAS Collaboration](https://atlas.cern/).

Here you find my current and past research results in ATLAS. For my past research at D0 or CMS, check my [publications]({{"/services/publications/" | relative_url }}).

![Chapel Fly Over]({{"/images/church_flyover.png" | relative_url }})

# Current Research

## Off-shell Higgs Measurement

| ![Off-shell Higgs]({{"/images/fig_02l.png" | relative_url }}){: width="5000" } | Our team performed the measurement of the off-shell Higgs production in the $$H\to ZZ\to 4\ell$$ and $$H\to ZZ\to 2\ell 2\nu$$ channels. For the first time, the ggF and EW productions of off-shell Higgs bosons are measured separately by introducing signal regions binned in jets. Different NN-based discriminants are trained in each $$4\ell$$ region. In the $$2\ell 2\nu$$ regions, the transverse mass is used as a proxy for $$m_{ZZ}$$. A novel method is used to describe a detailed systematic model for $$gg\to ZZ$$ production using NNs to perform full phase-space reweighting.<br> <br>**Participants**: Will Leight, Michiel Veen, Martina Javurkova, Sam Krishnamurthy, Jay Sandesara |

## Searches for new low mass states in $$t\bar{t}a, a\to bb/\mu\mu$$ events

In models of Higgs portals, the new scalar inherits Yukawa couplings from the SM Higgs and couples strongly to the top quark. We are exploring, for the first time, the process $$t\bar{t}a$$. This process is similar to $$t\bar{t}H$$, but with a low mass state which can deay to a pair of $$b$$-quarks ($$bb$$) or muons $$\mu\mu$$. The first result, with muons, has just been submitted for publication.

## Searches for exotic Higgs decays in the $$H\to aa\to 4b/2b2\tau/4\tau$$ final-state

| ![Exotic Higgs Decays]({{"/images/exotic_summary.png" | relative_url }}){: width="5000" } | Our team is perfoming several searches for exotic Higgs decays. The final states we are investigating have the highest branching ratios in Higgs portal models. These new particles in exotic Higgs decays can be the mediator of dark matter interactions and can trigger strong first order EW phase transitions, which can explain the baryon-antibaryon asymmetry of the university. When the new state has low mass, the searches are challenging since the decay products merge in the detector. Our team is developing dedicated tools to identify low-$$p_T$$ merged decays.<br><br>**Participants**: Yuan-Tang Chou, Yikai Wu<br>**Collaborators**: DESY, IFAE, U. Michigan, SLAC |

## New simulation-based inference strategies

| ![SBI]({{"/images/madminer.png" | relative_url }}){: width="5000" } | Our team is developing new analyses simulation-based inference strategies based on deep learning. The method is a generalization of several methods previously described in the literature to include the effect of systematic uncertainties, control regions, and other practical aspects of a LHC analysis. The novel method consists of unbinned analyses where the test statistics is built per-event and, therefore, uses all the power of the LHC data. The statistical analysis is implemented with auto-differentiation for practical implementations when a large number of events are available.<br><br>**Participants**: Will Leight, Jay Sandesara<br>**Collaborators**: IJCLab/Saclay, UC Irvine |

## Cloud-based analysis

| ![GCP]({{"/images/gcp.jpg" | relative_url }}){: width="1500" } | LHC analyses are usually performed on the Worldwide LHC Computing Grid (WLCG). However, for analyses that make intense use of deep learning methods, the WLCG is not adequate since it does not provide a scalable ML infrastructure. We are partnering with Google to use the cloud-based Google Cloud Platform to perform LHC analyses.<br><br>**Participants**: Jay Sandesara<br>**Collaborators**: BNL, U. Texas Arlignton |

## DeXTer: Deep Set low $$p_T$$ $$X\to bb$$ tagger

| ![DeXTer]({{"/images/dexter.png" | relative_url }}){: width="5000" } | Signatures with two merged $$b$$-jets are very common in BSM searches. The excellent resolution of both the ATLAS and CMS trackers and calorimeters are able to resolve jets and identify when a jet is the product of two independent $$b$$-hadrons. All existing algorithms only work for high-$$p_T$$ jets. However, in the search for exotic Higgs decays, we have low-$$p_T$$ merged jets. Our team has *developed and calibrated* the first low-$$p_T$$ double-$$b$$ tagger. It relies on an end-to-end Deep Set NN that explores tracks, secondary vertices, jet substructure, and their correlations.<br><br>**Participants**:Yuan-Tang Chou |

## NET2

![MGHPCC]({{"/images/net2.jpg" | relative_url }}){: width="6000" } | We are building a new Tier 2 at the [Massachusetts Green High Performance Computing Center](https://www.mghpcc.org/) (MGHPCC) called the **Northeast Tier 2** (NET2) cluster. The opportunity to build a system from scratch gives us the freedom to implement several improvements, something that would be challenging in a deployed system. NET2 operates purely over a kubernetes virtualization layer, allowing for seamless integration with other resources at the MGHPCC and outside. NET2 is also the first US ATLAS Tier 2 cluster to use a tape system for operations, a project developed in collaboration with [NESE](https://nese.mghpcc.org/).<br><br>**Participants**:Eduardo Bach, Will Leight |

## ITk Pixel Inner System

![ITk Pixel Inner System]({{"/images/itk.jpg" | relative_url }})

## New materials for Silicon Trackers Mechanics

![TIM Tower]({{"/images/tim2.png" | relative_url }}){: width="300" }

# Past research

## $$H\to ZZ\to 4\ell$$ Simplified Template Cross Section

| ![Simplified Template Cross Section]({{"/images/stxs_2022.png" | relative_url }}){: width="4000" } | <br><br>Our team measured the Higgs production in the $$H\to ZZ\to 4\ell$$ channel using the Simplified Template Cross Section (stage 1) formalism. Several different production modes and kinematic regions are probed. Our team performed a detailed study of the acceptance in each bin, comparing predictions from different generators.<br><br>**Participants**: Roberto di Nardo, Sam Krishnamurthy |

## Searches for low mass $$H\to aa\to 4\mu$$

| ![Run 2 H->aa->4mu]({{"/images/low_4mu.png" | relative_url }}){: width="5000" } | <br>Our team performed a full Run 2 search for the low-mass $$H\to aa\to 4\mu$$ exotic Higgs decays. This measurement is an update of a previous measurement performed by [Verena](http://people.umass.edu/vimartin/) and uses similar methods. This measurement was the thesis topic of former UMass/UIUC ATLAS graduate student Huacheng Cai and it was done in collaboration with former UMass ATLAS postdoctoral researcher Peter Tornambé. |

## Searches for low mass $$H\to aa\to 4b$$

| ![Partial Run 2 H->aa->4b]({{"/images/old_4b_merged.png" | relative_url }}){: width="5000" } | <br><br>Our team performed the first search for low-mass $$H\to aa\to 4b$$ decays. In the low mass region, the two pair of $$b$$-jets merge. We used track subjets with standard ATLAS $$b$$-tagging algorightms to identify the merged decay. The work was an important proof of concept and the thesis work of former UIUC student Mazin Khader. |

## ITk Strip Bus Tape Robot

| ![BTR]({{"/images/btr.png" | relative_url }}){: width="3000" } | <br>A robotic system to measure very long flex circuits was built to test the bus tapes used in the future ITk Strip Detector. The robot has two probes mounted on independent *xyz* stages. A detailed optical calibration was designed. Strict alignment and flatness requirements of the parts build in the UMass machine shops ensured accurate measurements. <br><br>**Participants**: Tiago dos Santos Ramos<br>**Collaborators**: Oxford, DESY, Ljubljana U. |
