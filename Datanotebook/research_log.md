# Research Log - Monday, May 18

* **Start Time:** 11:30 AM
* **End Time:** 1:30 PM
* **What I tried:** Installed Homebrew and Git via Mac terminal. Setup GitHub Desktop, switched to the dev branch, and configured local repository folder structure.
* **What I observed:** Encountered an initial error where GitHub Desktop couldn't see Git, resolved it by completely reinstalling the app. Also ran into issues with the gitignore. That is sorted out now. 
* **What I decided and why:** Placed the isotope-decay-network repository inside the my main desktop folder to keep all related assets unified.
* **What to do next:** Read the materials I have to. 


# Research Log - May 19 – June 2

No session log was kept during this period. 
Background reading was completed (see Master Checklist), 
but start/end times and daily observations were not recorded.
Reading covered: Wikipedia Magic number (physics), 
Wikipedia Table of nuclides, Wikipedia Radioactive decay, and Zhu et al. 2016.


# Research Log - Tuesday, June 2 

* **Start Time** 3:39 PM
* **What I did** I created my first entry in my note book and wrote the Pre-registration. 

# Research Log - Tuesday, June 3

* **Start Time** 1:29 PM

Collected my resource (Lab Notebook)

* **End Time:** Not recorded.


## Pre-Registration — June 3

* **Hypothesis:** Magic-number isotopes ($Z$ or $N ∈ {2,8,20,28,50,82,126}$) will show higher PageRank centrality in the heavy isotope decay network (50 ≤ Z ≤ 84) because decay chains converge on shell closures.
* **Primary metric:** PageRank, damping 0.85, tested at 0.70 and 0.95.
* **Secondary metric:** In-degree centrality.
Null result: If no correlation found, this means decay topology is driven by the valley of stability, not shell structure. Still a valid finding.
* **Scope fallback:** If data coverage < 50%, restrict to Z ≤ 83.


* **What I tried:** 

- I added the Pre-registration to the README. I then commited it to github desktop.
- I realised that I needed to create a seporate notebook to hold all my background research. I created it, and commited it to github. Also created table of contents and included the first few entries.
- I downloaded ### June 3, 2026 — [Start Time] – [End Time]
- Located and downloaded the official NuBase2020 dataset from ANL.
**Data Reference:** F.G. Kondev, M. Wang, W.J. Huang, S. Naimi, and G. Audi, *Chinese Physics C*, 45, 030001 (2021).

* **What I decided and why:** Moved file to `isotope-decay-network/data/nubase2020.txt`. 

Committing this raw text. I used the 

* **What do next:** Open Mathematica notebook `notebooks/network_parsing.nb` and test string import.

# Research Log - Tuesday, June 5

* **Start Time** 1:56 PM

* **What I did** 

I worked on finishing downloading my data. 
I set up the wolfram environment.

* **End time:** 8:26


2. In Your Physical Hardback Notebook (Do This Tonight)
On the page where you are logging today's setup, write a quick "Data Source Citation" entry by hand. You don't need to write the whole long string out perfectly, but write down the core details so judges know exactly where your data came from:

Data Reference: > NuBase2020 Dataset via Argonne National Laboratory.
Citation: F.G. Kondev et al., Chinese Physics C, Vol. 45, 030001 (2021).
URL: hosted at anl.gov (downloaded June 3, 2026).