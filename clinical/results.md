---
layout: page
title: Cmlinical Key Results
bigimg: /img/entete/installation-prototype-V0.jpeg
tags: [specifications]
---

> MAJ le 26 avril 2020

Attributes are:

    Openness
    Buildability
    Community Support
    Functionally Tested
    Reliability Tested
    COVID-19 Suitability
    Clinician Friendly

Openness

    Not Open
    Declared to be open, but no plans published
    Have a repo with at least some plans
    Has a clear license strategy, regular updates to plans
    Fully open, everything document, responsive community, clear license

Buildability

    Unbuildable
    Documents available but they require guesswork
    All software and hardware transparent and documented. Some manufacturing instructions, such as a build video
    Complete documentations suggested reproducibility
    Has been successfully reproduced by another team purely from documentation

Community Support

    Inactive; not point of contact
    Point of contact, but unresponsive
    Responsive leader or manager, more than one volunteer
    Active community, weekly activity and reports, git repo or other shared documents
    Large, active, open community

Functional Testing

      0.  In Design Phase, Not listed/tested

    Makes a bag move
    Tested with a test lung
    Tested for pressure and volume limits, with breath rate control
    Tested for alarms, multiple modes, O2 mixing
    All test green (if asserted as a feature)

Reliability Testing

      0.   Not Listed

    Operates for one hour
    Operates for 12 hours
    Operates for 12 hours passing all functional test acceptably (low exception rate)
    Independent team operates for 48 hours passing all functional tests, data logs reviewed
    Mean time between failure data starting to become meaningful

COVID-19 Suitability  

      0.  In design phase/Not listed

    Operates with supplemental oxygen
    Pressure or volume control or both
    PEEP
    Sophisticated alarm capability and stabilizability of all patient contact points
    Meets British RVMSv1 standards

Clinician Friendly

      0.   Unknown controls

    No controls
    Breath rate and volume control, standard ports
    Breath rate, volume and pressure control easy to set, standard ports, clear external labeling graphically and in the language of choice
    Alarms easy to set and understand; wholesale replication of an existing UI or conformance to a TBD UI standard
    Data logging, informative, easy control, battery backup for moving. No training needed in normal operation due to similarity with familiar designs.

Manufacturability (1000s)

Note: This is usually zero until Buildability of (1) unit (separate column) reaches 4.

     0. Insufficient plans to duplicate a single unit.
    1. Bill of Materials (BOM) clear.
    2. 2d parts, 3d parts, code, all clearly documented.
    3. Electrical schematics and air circuit schematics clear. PCBs if any present and documented. Wiring if required fully documented.
    4. Basic instructions and special instructions present. Video instructions helpful. Documented in language of choice, preferable more than one. Basic description of “smoke tests” and simple quality assurance present.
    5. Either evidence of BOM availability in units of 1000, or supply-chain flexibility of parts suggesting same. Documentation for handling supply-chain disruption present if minimal. Plans include manufacturing issues for non-expert workers. Detailed quality assurance plans present.
