Project 12 — Worker Voice in Platform Governance
Authors: Tarun Mikkilineni and Sai Vinay P
Target journal: Journal of Business Research

This project uses the 2023 and 2025 Fairwork Cloudwork Ratings reports to study documented appeal procedures, barriers reported by workers, and public recognition of organizing rights. The analysis compares the 14 platforms rated in both editions and examines the full 2025 roster of 16 platforms.
Repository files
Item	Contents
[Executed notebook](notebook/project-12-voice-of-workers.ipynb)	Python analysis with all 10 code cells and their saved outputs
[Complete submission ZIP](project-12-voice-of-workers-submission.zip)	Executed notebook, 29-file results archive, and target journal text file
[Results](Results/)	Three figures, one primary table, supplementary tables S1–S12, and audit and provenance files
[Data](data/)	Platform ratings, page-cited evidence ledgers, and the source manifest
[Research proposal](proposal/Project_12_Research_Proposal.docx)	Reconstructed proposal with the research questions, analysis plan, and references


Research questions and main findings
Research question	Main result
RQ1 — How did appeal procedures change across the two editions?	[Figure 1](Results/Figure_1_paired_ratings_and_changes.pdf). All 14 repeat platforms kept the same Fairwork 4.1 award status. The 2025 change log reported appeal-related changes for five of them.
RQ2 — How does appeal evidence differ by decision type?	[Figure 2](Results/Figure_2_decision_specific_evidence.pdf). The coded passages record appeal or review evidence for two account-suspension cases, two task-rejection cases, and zero nonpayment cases at the platform-by-decision level. Fairwork separately awarded its overall 4.1 threshold to eight platforms.
RQ3 — What barriers do workers report?	[Table 1](Results/Table_1_worker_account_evidence.csv). Four of six selected observations had overlapping or co-reported procedures. The accounts illustrate reported barriers.
RQ4 — How does due process overlap with recognition of organizing rights?	[Figure 3](Results/Figure_3_individual_and_collective_voice.pdf). Five platforms had both a 4.1 award and documented recognition. Three had the award only, two had recognition only, and six had neither documented.


Reproduce the analysis
1. Open the [executed notebook](notebook/project-12-voice-of-workers.ipynb) in Kaggle or Jupyter.
2. In Kaggle, enable internet access for the source downloads. For a local run, install the packages listed in [requirements.txt](Results/requirements.txt). To run offline, download the original PDFs listed in the [source manifest](Results/source_manifest.csv) and set FAIRWORK_INPUT_DIR to the folder containing them.
3. Run all cells. The notebook verifies both source PDFs against their SHA-256 checksums and generates project12_fairwork_results.zip. The [recorded environment](Results/run_environment.json) lists the software versions used for the verified rerun.
Verification and scope
An independent rerun of the code reproduced the saved findings and exhibits. The regenerated archive passed its integrity check. The [source audit](Results/evidence_source_audit.csv) documents checks of the manual coding and corrections against the reports. Independent recoding and adjudication are pending.

The findings describe the evidence reported in the two editions. The selected worker accounts lack independently verified matches to the policy in force at the time, which limits conclusions about how procedures worked in practice.
