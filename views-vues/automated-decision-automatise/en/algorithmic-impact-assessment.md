---
layout: default
title: Algorithmic Impact Assessment (draft)
lang: en
altLang: fr
altLangPage: evaluation-impact-algorithmique
collectionDirectory: views-vues/automated-decision-automatise
aboutDecisionSection: About the Decision
dataBusinessProcessSection: Data and Business Process
systemFunctionalitySection: System Functionality
organizationalReadinessSection: Organizational Readiness
automatedDecisionViewTitle: How should I implement an Automated Decision System? (draft)
automatedDecisionViewFilename: automated-decision
aiaCriteria: 
  - "Impact on Individuals and Entities"
  - "Impact on Government Institutions"
  - "Data Management"
  - "Procedural Fairness"
  - "Complexity"
questions:
  "1": What parts of the decision-making process will be automated by this system? (Check all that apply)
  "1a": File triage or assignment
  "1b": Risk scoring or categorization
  "1c": Recommendation to take a certain course of action
  "1d": Full end-to-end decision
  "1.1": Does the recommendation or decision made by the system involve discretion?
  "1.1.1": Is the decision purely discretionary? (e.g., a review on compassionate grounds)
  "1.1.2": Have all the decision points that involve the exercise of human discretion or judgement been clearly identified?
  "2": Can this automated system result in the restriction of movement into, out of, or within Canada?
  "3": Can this system infer or predict potential criminal activity?
  "4": Can this system result in granting or restricting access to a premises or network?
  "4.1": What is the classfication of the premises? (Select one)
  "5": Does this system provide funds to an individual, business, or community?
  "5.1": Is this funding for a social or economic support program?
  "5.1.1": If funding were to be denied, could it leave the client in a precarious economic positions? (e.g., could render an individual homeless or a business to close)
  "5.2": Does the system issue transfer payments?
  "5.2.1": Is this grant, contribution, or transfer payment in excess of $5,000,000?
  "6": Does this system, result in the issuance of a fine, administrative monetary penalty, or a debt collection notice?
  "7": Does this system result in the issuance of a permit, license, patent, or trademark?
  "7.1": Does this involve the collection, transportation, storage, purchase or sale of a regulated good or substance?
  "7.1.1": Is this regulated good or substance dangerous, such as a firearm, toxin, or hazardous material?
  "7.2": Is this a construction or environmental permit?
  "7.3": Is this a patent or trademark?
  "8": Does this system confer a legal status that is otherwise required to receive a benefit or service (e.g., Indian status, veteran status)?
  "9": Does this system involve the distribution of human resources or material in the management of emergencies?
  "10": What are the key business drivers for automating the administrative decision-making process? (Check all that apply)
  "10a": Existing backlog of work or cases
  "10b": Improve overall quality of decisions
  "10c": Lower transaction costs of an existing program
  "10d": The system is performing tasks that humans could not accomplish in a reasonable period of time
  "10e": Improve client service delivery
  "10f": Using innovative approaches
  "10g": None of the above
  "11": Will your system make decisions specifically about Indigenous peoples or territory?
  "11.1": Have you engaged relevant Indigenous organizations in meaningful consultation in the design of the system?
  "12": Who collected the data used for training the system? (Check all that apply)
  "12a": Your institution
  "12b": Another federal institution
  "12c": Another level of government
  "12d": A foreign government
  "12e": A non-government third party
  "13": Who collects the input data used by the system? (Check all that apply)
  "13a": Your institution
  "13b": Another federal institution
  "13c": Another level of government
  "13d": A foreign government
  "13e": A non-government third party
  "14": Have you consulted with relevant stakeholder groups representing those likely to be affected by the decision?
  "15": Is there a process in place to document how data quality issues were resolved during the design process?
  "16-part1": Have you undertaken
  "16-link-url": "https://www.swc-cfc.gc.ca/gba-acs/approach-approche-en.html"
  "16-link-text": Gender Based Analysis Plus
  "16-part2": of the training data?
  "16.1": Based on the GBA+ results, have you documented mitigation strategies?
  "17": Does the Automated Decision System use personal information as input data?
  "17.1": Does the program have an existing Privacy Impact Assessment?
  "18": Have you assigned accountability for the design, development, maintenance, and improvement of the system?
  "19": What is the security classfication of the input data used by the system? (Select one)
  "20": Do you have a process in place to test and verify business rules?
  "21": Does the system require the analysis of unstructured data to render a recommendation or a decision?
  "22": Is the scope of the system clearly reflected in project documentation?
  "23": Have appropriate strategies been developed to manage the risk that outdated or unreliable data is used to make an automated decision?
  "24": Does your system use contactless machine vision for biometric recognition (e.g. facial, full-body person, gait)?
  "24.1": Does your system perform within acceptable parameters for all skin colours as defined by the Fitzpatrick Skin Type scale or similar measurement?
  "24.2": Where applicable, have you tested to ensure that the system performs within acceptable parameters with persons who have a disability that may cause them to be unduly disadvantaged by the machine vision component? (e.g., ensuring that a gait analysis tool does not unduly disadvantage an individual that uses a wheelchair)
  "25": Does the system interface with other IT systems?
  "25.1": Where it interfaces with other systems, have you clearly identified the business processes that occur between systems?
  "26": Which of the following information about system functionality are you planning to make publicly available? (Check all that apply)
  "26a": Training data sources
  "26b": Decision trees
  "26c": Confidence thresholds
  "26d": Pre-defined models
  "26e": Criteria
  "26f": Classification structures
  "26g": None of the above
  "27": Does the system enable human override of system decisions?
  "28": Does the system enable override of human decisions?
  "29": Does the system enable the override of other automated decision systems?
  "30": Do you have processes in place to log the instances where overrides were performed?
  "31": Did you develop verification processes to test for unintentional outcomes?
  "32": Can the system provide an audit trail that records recommendations or decisions?
  "32.1": Does the audit trail clearly set out all decision points made by the system?
  "32.2": Have you included change control processes in the audit trail to record modifications to the system's operation or performance?
  "32.3": Does the audit trail show who an authorized decision-maker is?
  "33": Is the system capable of incorporating recommendations or decisions into a statement, reasons or other written notification, where required?
  "34": Has the design team consulted the following experts within their organization?
  "34a": Communications
  "34b": Data and Information Management
  "34c": Enterprise Architecture
  "34d": Human Resources
  "34e": IT/Cybersecurity
  "34f": Legal
  "34g": Service Delivery
  "34h": Privacy
  "34.1": Has a formal opinion been issued?
  "34.2": Have the relevant areas of legislation been identified during the scoping phase?
  "35": Have you developed Key Performance Indicators and benchmarks to measure and improve the system’s performance?
  "35.1": Are you specifically measuring impacts (e.g., social, economic, environmental) that may result from the system?
  "36": Have you presented a concept case to the Government of Canada Enterprise Architecture Review Board?
  "37": Have you conducted a Security Assessment and Authorization?
  "38": Is there a process in place to monitor and grant access permission?
  "39": Is the system used by a different part of the organization than the ones who developed it?
  "40": Did you develop training programs or documentation to ensure that the system is used effectively and properly?
  "40.1": Do you have the means to ensure that training requirements are being met?
  "41": If the system is intended to undertake tasks currently undertaken by human staff, have you engaged with your departmental human resources?
  "42": Have you developed an external communications plan?
  "43": Have you developed an internal communications plan to address any potential changes to work practices for officers?
  "44": Do you have a mechanism to capture feedback by users of the system?
  "45": Do you have a recourse process planned or established for clients that wish to challenge the decision?
points:
  "1a":
    "yes": [ 1, 1, 0, 1, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "1b":
    "yes": [ 3, 2, 0, 2, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "1c":
    "yes": [ 4, 2, 0, 3, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "1d":
    "yes": [ 5, 3, 0, 4, 2 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "1.1":
    "yes": [ 2, 0, 0, 3, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "1.1.1":
    "yes": [ 5, 0, 0, 5, 4 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "1.1.2":
    "yes": [ -2, 0, 0, -2, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "2":
    "yes": [ 4, 3, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "3":
    "yes": [ 5, 5, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "4":
    "yes": [ 1, 1, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "4.1":
    "none": [ 0, 0, 0, 0, 0 ]
    "protected": [ 0, 1, 0, 0, 0 ]
    "protected-a": [ 0, 3, 0, 0, 0 ]
    "protected-b": [ 0, 4, 0, 0, 0 ]
    "protected-c": [ 0, 5, 0, 0, 0 ]
    "classified": [ 0, 2, 0, 0, 0 ]
    "confidential": [ 0, 3, 0, 0, 0 ]
    "secret": [ 0, 4, 0, 0, 0 ]
    "top-secret": [ 0, 5, 0, 0, 0 ]
  "5":
    "yes": [ 3, 2, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "5.1":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "5.1.1":
    "yes": [ 5, 0, 0, 2, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "5.2":
    "yes": [ 0, 1, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "5.2.1":
    "yes": [ 2, 2, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "6":
    "yes": [ 4, 2, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "7":
    "yes": [ 1, 1, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "7.1":
    "yes": [ 2, 2, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "7.1.1":
    "yes": [ 1, 3, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "7.2":
    "yes": [ 2, 2, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "7.3":
    "yes": [ 3, 2, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "8":
    "yes": [ 3, 2, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "9":
    "yes": [ 1, 4, 0, 0, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "10a":
    "yes": [ -1, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "10b":
    "yes": [ -1, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "10c":
    "yes": [ 0, -1, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "10d":
    "yes": [ 0, -1, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "10e":
    "yes": [ -2, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "10f":
    "yes": [ 0, -1, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "10g":
    "yes": [ 0, -1, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "11":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "11.1":
    "yes": [ -1, 0, 0, 0, 0 ]
    "no": [ 3, 1, 0, 0, 0 ]
  "12a":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "12b":
    "yes": [ 0, 0, 1, 0, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "12c":
    "yes": [ 0, 0, 2, 1, 2 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "12d":
    "yes": [ 0, 0, 2, 2, 2 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "12e":
    "yes": [ 0, 0, 3, 2, 2 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "13a":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "13b":
    "yes": [ 0, 0, 1, 0, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "13c":
    "yes": [ 0, 0, 2, 1, 2 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "13d":
    "yes": [ 0, 0, 2, 2, 2 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "13e":
    "yes": [ 0, 0, 3, 2, 2 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "14":
    "yes": [ -2, 0, 0, 0, 0 ]
    "no": [ 2, 0, 0, 2, 0 ]
  "15":
    "yes": [ 0, 0, -3, -2, 0 ]
    "no": [ 1, 1, 3, 2, 0 ]
  "16":
    "yes": [ -1, 0, -1, 0, 0 ]
    "no": [ 1, 0, 1, 0, 0 ]
  "16.1":
    "yes": [ -1, 0, 0, 0, 0 ]
    "no": [ 1, 0, 0, 0, 0 ]
    "na": [ 0, 0, 0, 0, 0 ]
  "17":
    "yes": [ 0, 0, 0, 0, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "17.1":
    "yes": [ 0, 0, -1, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "18":
    "yes": [ 0, 2, 0, 3, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "19":
    "protected": [ 0, 0, 0, 0, 0 ]
    "protected-a": [ 0, 0, 0, 0, 3 ]
    "protected-b": [ 0, 0, 0, 0, 4 ]
    "protected-c": [ 0, 0, 0, 0, 5 ]
    "classified": [ 0, 0, 0, 0, 2 ]
    "confidential": [ 0, 0, 0, 0, 3 ]
    "secret": [ 0, 0, 0, 0, 4 ]
    "top-secret": [ 0, 0, 0, 0, 5 ]
  "20":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 1, 2, 0 ]
  "21":
    "yes": [ 0, 0, 2, 0, 2 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "22":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 1, 2, 1 ]
  "23":
    "yes": [ 0, 0, -4, -3, 0 ]
    "no": [ 1, 1, 4, 3, 0 ]
  "24":
    "yes": [ 0, 0, 0, 0, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "24.1":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 2, 0, 0, 0, 0 ]
  "24.2":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 2, 0, 0, 0, 0 ]
  "25":
    "yes": [ 0, 0, 0, 0, 2 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "25.1":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 1, 0, 0 ]
  "26a":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "26b":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "26c":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "26d":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "26e":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "26f":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "26g":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "27":
    "yes": [ 0, -2, 0, -1, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "28":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "29":
    "yes": [ 0, -1, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "30":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 1, 2, 0 ]
  "31":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 2, 0, 1, 4, 0 ]
  "32":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 3, 1 ]
  "32.1":
    "yes": [ 0, -1, 0, 0, 0 ]
    "no": [ 0, 0, 0, 2, 1 ]
  "32.2":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 1, 3, 1 ]
  "32.3":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 2, 0 ]
  "33":
    "yes": [ -2, -1, 0, -2, 1 ]
    "no": [ 0, 0, 0, 4, 0 ]
  "34a":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 0, 0 ]
  "34b":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 2, 0, 0 ]
  "34c":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 0, 0 ]
  "34d":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 0, 0 ]
  "34e":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 2, 0, 0, 0 ]
  "34f":
    "yes": [ 0, 0, 0, -2, 0 ]
    "no": [ 0, 1, 0, 2, 0 ]
  "34g":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 0, 0 ]
  "34h":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 0, 0 ]
  "34.1":
    "yes": [ 0, -1, 0, -1, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "34.2":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 2, 0 ]
  "35":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 2, 1, 0, 0 ]
  "35.1":
    "yes": [ -3, 0, -1, -1, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "36":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 1, 0, 0 ]
  "37":
    "yes": [ 0, 0, -1, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "38":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 2, 0, 0 ]
  "39":
    "yes": [ 0, 0, 0, 0, 1 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "40":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 2, 0, 0, 0 ]
  "40.1":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 0, 0 ]
  "41":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 0, 0 ]
    "na": [ 0, 0, 0, 0, 0 ]
  "42":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 0, 0 ]
  "43":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 1, 0, 0, 0 ]
  "44":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 0, 0, 0, 0, 0 ]
  "45":
    "yes": [ 0, 0, 0, 0, 0 ]
    "no": [ 2, 0, 0, 5, 0 ]
criteriaThresholds:
  - [15, 40, 70]
  - [25, 50, 75]
  - [30, 60, 80]
  - [30, 60, 80]
  - [25, 50, 75]
multipliers:
  - []
  - []
  - [0.9, 1, 2]
  - [0.9, 1, 2]
  - [1, 1.15, 1.25, 1.5]
progressPercentThreshold: 1
---
{% assign dataVariable = site.playbookData[page.lang] %}{%
assign dataSource = site.data[dataVariable] %}
<section>

<div class="wb-inview" data-inview="progress-overlay">

## Introduction

</div>

The aim of the Algorithmic Impact Assessment (AIA) is to develop a framework to help institutions better understand and mitigate the risks associated with Automated Decision Systems.

In developing the AIA, the following three key goals have been identified:

- Increase capacity to evaluate the impact of Automated Decision Systems including legal and ethical issues, such as disparate impacts and due process violations;
- Recommend the appropriate governance, oversight and/or design recommendations to institutions based on their existing or proposed automated decision systems; and
- Provide a mechanism for greater openness and transparency for public consultation and external review of the design and deployment of Automated Decision Systems in the public sector.

</section>

{% include views-vues/automated-decision-automatise/aia-questionnaire-eia.html %}

{% include views-vues/automated-decision-automatise/aia-results-resultats-eia.html %}