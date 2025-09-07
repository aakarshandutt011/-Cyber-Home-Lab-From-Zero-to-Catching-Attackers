cyber-home-lab/
│── README.md                # Project overview & documentation
│── LICENSE                  # (Optional) Add a license like MIT
│── .gitignore               # Ignore unnecessary files
│
├── screenshots/             # Project screenshots
│   ├── vm-deployment.png
│   ├── log-analytics.png
│   ├── sentinel-dashboard.png
│   ├── attack-logs.png
│   └── attack-map.png
│
├── configs/                 # Configurations, queries, JSON templates
│   ├── sentinel-detection-rules.json
│   ├── log-analytics-setup.md
│   └── sysmon-config.xml
│
├── notes/                   # Learning notes & extra documentation
│   ├── attack-analysis.md
│   ├── kql-queries.md
│   └── future-enhancements.md
│
└── scripts/                 # Automation or helper scripts
    ├── azure-vm-deploy.ps1   # PowerShell script (if used)
    ├── enable-logging.sh     # Example Bash script
    └── import-rules.ps1
