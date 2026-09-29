# Awesome-Behavioral-Biometrics

## Top Behavioral Biometrics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Continuous Authentication, Fraud Detection & Identity Verification*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Behavioral Biometrics**. These tools analyze patterns in how users interact with devices — typing rhythm, mouse movement, touch gestures, and gait — to verify identity continuously and detect account takeover or fraud in real time.



**Examples** include BioCatch, Featurespace, TypingDNA, Zighra, BehavioSec, NuData Security, Unbotify, ThreatMark, Plurilock, Callsign, and SecuredTouch (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom behavioral modeling, and transparent biometric research — ideal for developers, researchers, and security engineers building vendor-independent continuous authentication systems. The open-source ecosystem provides strong foundations in keystroke dynamics, mouse trajectory analysis, and multi-modal data collection, though production-grade deployment requires significant tuning and domain expertise.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[BioCatch](https://www.biocatch.com/)**  

  Behavioral biometrics platform analyzing 2,500+ cognitive and physical interaction signals for fraud detection, continuous authentication, and scam prevention across digital banking and e-commerce.



- **[Featurespace](https://www.featurespace.com/)**  

  Adaptive behavioral analytics platform using machine learning for real-time fraud and financial crime detection, analyzing transaction and interaction patterns.



- **[TypingDNA](https://www.typingdna.com/)**  

  Keystroke dynamics platform providing typing biometrics for two-factor authentication, fraud prevention, and continuous authentication. Offers JavaScript recorder and authentication APIs.



- **[Zighra](https://www.zighra.com/)**  

  Behavioral biometrics and continuous authentication platform using on-device AI for frictionless identity verification.



- **[BehavioSec](https://www.behaviosec.com/)**  

  Behavioral biometrics platform (now part of LexisNexis Risk Solutions) analyzing typing, mouse, and touch patterns for continuous authentication and fraud detection.



- **[NuData Security](https://www.nudata.com/)**  

  Behavioral analytics platform (Mastercard company) using passive biometrics for fraud prevention and account takeover detection.



- **[Unbotify](https://www.unbotify.com/)**  

  Behavioral biometrics solution (now part of Datadome) using human interaction patterns to distinguish humans from bots and malicious automation.



- **[ThreatMark](https://threatmark.com/)**  

  Fraud detection and behavioral biometrics platform for digital banking, analyzing user behavior for account takeover and transaction anomaly detection.



- **[Plurilock](https://www.plurilock.com/)**  

  Behavioral biometrics platform providing continuous authentication for workstations and applications through typing and mouse dynamics.



- **[Callsign](https://www.callsign.com/)**  

  Identity and behavioral intelligence platform using behavioral biometrics and deep learning for authentication and fraud prevention.



- **[SecuredTouch](https://www.securedtouch.com/)**  

  Behavioral biometrics platform (now part of Ping Identity) providing continuous authentication for mobile and web applications.



## Open-Source GitHub Projects



- **[Neuro-Mimesis](https://github.com/sadvik-asus/Neuro_Mimesis)**  

  Next-generation security framework implementing Cognitive Identity Verification through mouse movement dynamics. Features continuous authentication, real-time Trust Score calculation, and an **Active Defense Protocol** that triggers on breach detection: webcam evidence capture, IP geolocation, emergency alerts, cursor jitter, and workstation lockdown. React + Flask + SQLite stack with OpenCV and PyAutoGUI for OS-level control. The system measures mouse entropy — AI bots move in straight lines, humans exhibit "jitter" and micro-corrections .



- **[Behavior-Based-Authentication (VanGuard2025)](https://github.com/VanGuard2025/Behavior-Based-Authentication)**  

  Real-time ML-powered authentication system continuously verifying users via keystroke dynamics and mouse behavior. Features adaptive anomaly detection, drift monitoring, and a modern web interface. Uses GRU sequence models and Autoencoders for behavioral modeling, with configurable thresholds for confidence and anomaly scores. Flask backend with WebSocket streaming and Chart.js visualizations for real-time behavioral analytics .



- **[Behavioral Biometrics Tracker (aaryanyaadav)](https://github.com/aaryanyaadav/Behavioral-Biometrics)**  

  Django-based mobile web application collecting touch pressure, swipe dynamics, device tilt, and keystroke patterns for continuous authentication. Features dual-storage system (local CSV + Firebase Realtime Database), 12-Factor App methodology, and admin export endpoints in CSV, JSON, and XLSX. Captures Characters Per Minute, error rates, dwell times, and flight times specifically for mobile interaction .



- **[Open-Behavioral-Auth (OBA)](https://github.com/topics/behavioral-biometrics)**  

  Privacy-first, open-source engine for passive MFA. Captures user "rhythms" — keystroke dynamics and pointer velocity — via a lightweight JavaScript SDK. Features adaptive threshold matching to handle behavioral drift across devices. Enables self-hosted Risk-Based Authentication (RBA) framework to detect anomalies without user friction .



- **[KeyStroke-Dynamics (Xenia101)](https://github.com/Xenia101/KeyStroke-Dynamics)**  

  Web-based user verification system using keystroke dynamics with k-NN classification. Achieved **96.8% average accuracy** across 5-fold cross-validation (97.6%, 92.2%, 97.1%, 100%, 97.1%). Uses Euclidean distance for feature comparison and Simhash with Hamming distance for large-scale deployment optimization. Python Flask + k-NN based .



- **[BEACON-Logger](https://zenodo.org/records/20062628)**  

  Python-based multimodal data acquisition tool for behavioral biometrics research in gaming environments. Synchronizes five data streams: keystroke dynamics (press/release, durations, inter-key latencies), mouse kinematics (X/Y, velocity, acceleration, click timing), network traffic (PCAP via Scapy/Npcap), hardware metadata (MAC, monitor aspect ratios, HID inventory), and game-specific configuration. Includes integrated screen recording for visual ground truth. Designed for continuous authentication and Zero Trust Architecture research .



- **[TypingDnaRecorder-JavaScript](https://github.com/TypingDNA/TypingDnaRecorder-JavaScript)**  

  JavaScript class for recording typing biometrics information and typing patterns in the browser. Official recorder from TypingDNA, enabling keystroke dynamics collection for authentication and fraud detection applications .



- **[SSPRA (State-Space Perturbation-Resistant Approach)](https://github.com/DrFrankSChen/SSPRA-State-Space-Perturbation-Resistant-Approach)**  

  Research code for a modality-agnostic continuous authentication framework using state-space temporal modeling and multimodal sensor fusion. Published in IEEE Transactions on Biometrics, Behavior, and Identity Science (2024). Fuses authentication evidence from all available modalities, maintaining monitoring when some modalities are temporarily absent. Updates probabilities of Safe, Suspense, and Attacked states. Includes runnable BB-MAS gait demo using accelerometer/gyroscope streams .



- **[PyWIB](https://personales.upv.es/thinkmind/IARIA_CONGRESS/IARIA_Congress_2026/iaria_congress_2026_1_170_50103.html)**  

  Python library for multi-modal web interaction behavior analysis. Unifies mouse-tracking and keystroke dynamics into a single processing pipeline. Designed for Human-Computer Interaction research, providing methods to process event logs and compute behavioral metrics. Open-source and available on GitHub .



- **[generative-mouse-trajectories](https://github.com/jrcalgo/generative-mouse-trajectories)**  

  GAN-based imitation learning of user mouse movements. Captures high-fidelity trajectory data (temporal, spatial, kinematic, and behavioral metrics) and trains Generative Adversarial Networks to simulate authentic human-like cursor movements. Applicable to behavioral biometrics, automated UI testing, and accessibility tools. Includes Rust-based collection environment and CSV export .



### Additional Strong Open-Source Options



- **Maze-trace CAPTCHA with behavioral biometrics** — CAPTCHA system with behavioral biometrics that is invisible to humans but impenetrable to agents. Updated 2026 .

- **Behavioral signature authentication for UPI** — Replaces PIN with handwritten signature using on-device biometrics. Working prototype with Python backend .

- **SecureAuth Enterprise** — Behavioral biometric authentication platform analyzing keystroke dynamics, mouse behavior, facial recognition, and WebAuthn for continuous verification .

- **Who Is Alyx? dataset** — Behavioral biometric dataset for user identification in XR. 71 users playing Half-Life: Alyx across two sessions with motion, eye-tracking, and physiological data. Best model achieves 95% mean accuracy within 2 minutes .

- **Wink Wink EEG dataset** — Multi-session EEG dataset for biometric authentication based on voluntary eye-movement patterns (winks and blinks). 18 participants, 8-channel EEG at 250 Hz .



**Frameworks for building custom behavioral biometrics solutions**: Combine **Neuro-Mimesis** for mouse entropy-based continuous authentication with active defense, **Behavior-Based-Authentication** for ML-powered keystroke + mouse verification with drift monitoring, and **Open-Behavioral-Auth** for privacy-first passive MFA with adaptive thresholds. For mobile-specific behavioral biometrics, **Behavioral Biometrics Tracker** provides touch pressure and device tilt capture. For research-grade multimodal data collection, **BEACON-Logger** offers synchronized keystroke, mouse, network, and hardware streams. Note that production-grade behavioral biometrics requires large-scale user datasets for model training, careful handling of behavioral drift, and rigorous privacy compliance — the open-source ecosystem provides strong algorithmic foundations and research frameworks, but enterprise-scale deployment remains primarily commercial.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Behavioral biometrics tools collect sensitive interaction data and must comply with data privacy regulations (GDPR, CCPA, BIPA in Illinois, etc.). Biometric data handling requires explicit consent and secure storage.

- Self-hosted open-source solutions require proper infrastructure, model training data, and ongoing tuning. Behavioral models are sensitive to device changes, context shifts, and user fatigue — continuous validation is essential.

- The open-source ecosystem provides strong algorithmic foundations and research frameworks, but enterprise-grade behavioral biometrics with global scale, real-time risk scoring, and regulatory compliance remains primarily a commercial offering.



---



**Made for security engineers, fraud prevention teams, identity architects, and behavioral researchers.**  

Let's make behavioral biometrics more open, transparent, and privacy-respecting.
