<div align="center">

<img src="assets/hero-v5.svg" alt="Deep Bendale: building intelligent systems. Applied AI Engineer, Systems Builder, Product Builder. Mumbai, India" width="100%">

[![GitHub](https://img.shields.io/badge/GitHub-deepbendale231-0D0D14?style=for-the-badge&logo=github&logoColor=white&labelColor=0D0D14&color=A855F7)](https://github.com/deepbendale231)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-deepbendale-0D0D14?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D0D14&color=00E5FF)](https://www.linkedin.com/in/deepbendale/)
[![Ainsemble](https://img.shields.io/badge/Ainsemble-DAW%20Plugin-0D0D14?style=for-the-badge&logo=musicbrainz&logoColor=white&labelColor=0D0D14&color=A855F7)](https://ainsemble.com/products/daw-plugin)
[![Email](https://img.shields.io/badge/Email-Start%20a%20project-0D0D14?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D0D14&color=A855F7)](mailto:deepbendale231@gmail.com)

[**About**](#-about) · [**Systems**](#-featured-systems) · [**Activity**](#-activity) · [**Experience**](#-experience) · [**Stack**](#-stack) · [**Contact**](#-contact)

</div>

<br>

## 👤 About

<img src="assets/about-v2.svg" alt="About Deep Bendale. I'm an Applied AI Engineer from Mumbai, and I like building real systems end to end. Right now I lead the cloud-sync feature for Ainsemble's DAW plugin: a cross-platform C++ plugin that syncs a producer's projects to the cloud, owned from requirements to release. Day to day that means architecture decisions, testing inside real DAW hosts, and shipping Windows and macOS installers. I also love working with data. Credit risk models, RAG assistants and analytics APIs are how I learn what a good system needs underneath. I'm a B.Tech IT student at DJSCE, Mumbai." width="100%">

<br>

<img src="assets/stats-v4.svg" alt="84 contributions in the last 12 months, 9 public repositories, 8 pull requests" width="100%">

## 🧩 Featured systems

<table>
<tr>
<td width="50%"><a href="https://github.com/deepbendale231/credit-decisioning-engine"><img src="assets/card-credit-v4.svg" alt="Credit Decisioning Engine: rules, calibrated XGBoost and SHAP. ROC-AUC 0.763, 3.84 points more approvals" width="100%"></a></td>
<td width="50%"><a href="https://github.com/deepbendale231/RAG-BASED-Teaching-LLM"><img src="assets/card-rag-v4.svg" alt="RAG Teaching Assistant: 11 videos, 105 timestamped chunks, local LLM" width="100%"></a></td>
</tr>
<tr>
<td width="50%"><a href="https://github.com/deepbendale231/Uber-Analytics"><img src="assets/card-uber-v4.svg" alt="Uber NCR Ride Analytics: 150K bookings, peak hour 18:00" width="100%"></a></td>
<td width="50%"><a href="https://github.com/deepbendale231/Pollution-Analytics"><img src="assets/card-pollution-v4.svg" alt="Pollution Analytics: 3,240 readings across 270 cities" width="100%"></a></td>
</tr>
</table>

<sub>Also: [Digital Lending Journey Teardown](https://github.com/deepbendale231/lending-journey-teardown) (PRD, RICE, RBI checklist, A/B plan) · [Uber live dashboard](https://uber-analytics.onrender.com) · [HouseIQ](https://github.com/deepbendale231/House-Prediction-ML-Model-)</sub>

## 📈 Activity

<img src="assets/activity-v4.svg" alt="Contribution heatmap for the last 52 weeks" width="100%">

<img src="assets/langs-v5.svg" alt="Language share across public repositories and weekly coding activity" width="100%">

## 💼 Experience

### Software Engineering Intern, DAW Plugin Feature Lead · [Ainsemble](https://ainsemble.com/products/daw-plugin)
<sub>Jun 2026 to present &nbsp;·&nbsp; <a href="https://ainsemble.com/products/daw-plugin">ainsemble.com/products/daw-plugin</a></sub>

Sole engineer responsible for architecting and building Ainsemble's DAW plugin from the ground up, through backend integration, cross-platform implementation, release engineering and beta testing.

- **End-to-end product engineering:** owned the full feature lifecycle, from requirements and architecture to implementation, testing and release. About 34,000 lines of native C++ across 129 source files, plus a React/TypeScript WebView interface.
- **Cross-platform DAW development:** a JUCE 8 / C++17 plugin for AU, VST3 and Standalone. macOS universal binaries for Apple Silicon and Intel, with Windows build and installer automation.
- **Backend integration:** reverse-engineered the undocumented production architecture across Django, FastAPI services, Azure Blob Storage, Elasticsearch and Firestore. Built API clients, authentication, session restoration, account management and cloud library sync.
- **Cloud sync and file management:** project export, import, download and restore, with bundle-aware handling of GarageBand and Logic projects, resumable Azure block uploads, upload-link refresh, duplicate handling and integrity checks.
- **Automatic project versioning:** a checkpointed, lock-protected versioning engine using semantic file fingerprints, atomic persistence, cross-process locking and change detection, so duplicate versions and unsafe uploads are prevented.
- **Reliability and reverse engineering:** fixed hard issues with GarageBand bundles, FL Studio project parsing and sample relinking, credential persistence, sync and session restoration, and added safeguards against accidental overwrites and inconsistent project states.
- **Security:** per-host credential storage in macOS Keychain and Windows Credential Manager, JWT session restoration, and automatic scrubbing of sensitive data from exported diagnostic logs.
- **Testing and release:** API, integration, concurrency and real-file round-trip tests, plus automated macOS and Windows packaging, including a signed, notarized and stapled universal macOS installer.
- **Beta delivery:** took the plugin through implementation, validation and beta delivery as part of Ainsemble's music collaboration platform.

[![Ainsemble DAW Plugin](https://img.shields.io/badge/Ainsemble-DAW%20Plugin%20↗-0D0D14?style=for-the-badge&labelColor=0D0D14&color=00E5FF)](https://ainsemble.com/products/daw-plugin)

<br>

### Data Science & Machine Learning Intern · New Vision Technologies and Engineers, Mumbai
<sub>Jan 2026 to May 2026</sub>

- Cut weekly reporting from about 3 hours to under 1 hour (over 65%) by automating ETL and report generation in Python and SQL
- Raised demand-forecast R² from 0.71 to 0.86 with XGBoost on 120K+ sales and inventory records
- Built Excel dashboards tracking 15+ KPIs for business stakeholders

## 🎓 Education

**B.Tech, Information Technology**: Dwarkadas J. Sanghvi College of Engineering, Mumbai · 2023 to May 2027 · CGPA 9.00 / 10
<br><sub>Wharton Business Analytics · IIT Madras BS in Data Science (Foundation)</sub>

## 🛠 Stack

<img src="assets/stack-v4.svg" alt="Python, C++, TypeScript, SQL, FastAPI, Next.js, XGBoost, scikit-learn, SHAP, pandas, PostgreSQL, MySQL, Docker, Git, GitHub Actions, Streamlit" width="100%">

## 🤝 Contact

<a href="mailto:deepbendale231@gmail.com"><img src="assets/footer-v4.svg" alt="Let's build something intelligent. deepbendale231@gmail.com, Mumbai, India" width="100%"></a>
