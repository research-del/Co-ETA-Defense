Co-ETA is a learning-based website fingerprinting (WF) defense** that enforces *bounded attacker recovery* under sustained adversarial adaptation.  
The defense perturbs encrypted traffic traces using a lightweight neural generator trained via co-evolutionary adversarial learning** against multiple 
state-of-the-art attackers.

Key Contributions

- **Co-evolutionary training** between a traffic anonymization generator and adaptive WF attackers
- Defense against **Deep Fingerprinting (DF)**, **TikTok**, and **Random Forest (RF)** attackers
- Demonstrates **bounded attacker recovery** under adaptive retraining
- Supports **closed-world** and **open-world** evaluation settings
- Lightweight perturbations with minimal utility and bandwidth impact

Repository structure
COETA-defense/
├── src/                          # Source code directory
│   ├── training/                 # Training modules
│   │   └── coevolution_training.py
│   ├── adaptive/                 # Adaptive attacker simulations
│   │   └── coevolution_all_adaptive.py
│   ├── evaluation/               # Evaluation scripts
│   │   ├── closedworld.py        # Closed-world evaluation
│   │   ├── openworld.py          # Open-world evaluation
│   │   └── openworld_multirun.py # Multi-run open-world evaluation
│   ├── analysis/                 # Performance analysis
│   │   └── overhead_analysis.py  # Bandwidth/latency analysis
│   ├── utils/                    # Utility functions
│   └── visualization/            # Visualization tools
│       └── openworld_PRC.py      # Precision-Recall Curve plotting
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies


Contact

This research was conducted at the School of Computer Science and Technology, Jiangsu University.

For research collaboration and academic inquiries:

Please contact our research group through official university channels
For code-related questions and technical issues:

Please contact (5103240323@stmail.ujs.edu.cn)
Check the documentation and existing issues first
