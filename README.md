# Liver Injury Network Explorer (prototype)

Interactive prototype built for the New Jersey Health Foundation Research Grant
application *Network-Based Discovery of Molecular Signatures of Cancer
Therapy-Induced Liver Injury* (Guimu Guo, PI, Computer Science, and
Sophia Orbach, Co-PI, Biomedical Engineering, Rowan University).

Live page: https://guimuguo.github.io/liver-network-demo/

**All data on the page are simulated.** Gene symbols and pathway groupings
reflect established liver-injury biology, but fold changes, module scores and
LDH values are generated deterministically in the page's JavaScript to
illustrate the planned workflow. No experiments have been run.

Features: guided 30-second tour, condition and evidence-layer filters, interactive
STRING-style network with module hulls, module ranking and details, dose-response
small multiples with table view and CSV export, and a robustness panel comparing a
top-10 single-gene list with the modules under replicate drop-out and confidence
thresholds.

The previous version is kept at `v1/index.html` (live at `/v1/`, git tag `v1`).

The page is a single self-contained `index.html` (D3 v7 from a CDN, no build
step). Open it locally or serve the folder with any static server.
