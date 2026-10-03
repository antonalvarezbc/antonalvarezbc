# Hi, I'm Antón Álvarez 👋🐾

**Conservation biologist working at the intersection of wildlife monitoring, data and AI.**
I build bridges between field technicians, ecologists, administrations and engineers so that technology (computer vision, camera traps, remote sensing, open data platforms) actually gets adopted where conservation happens: on the ground.

Based in Spain · Worked at **WWF Spain** from 2017 to 2026 · Mostly on the **Iberian lynx** (*Lynx pardinus*) and its ecosystem.

<details>
<summary>🇪🇸 En español</summary>

Biólogo de la conservación especializado en aplicar tecnología (visión por computador, fototrampeo, teledetección y plataformas de datos abiertos) al seguimiento y conservación de fauna amenazada. Trabaje como coordinador técnico en WWF España, con foco en el lince ibérico, el conejo de monte y los grandes carnívoros. Me muevo cómodo entre el campo, el código y la gestión de proyectos europeos. 
</details>

---

## 🔭 What I work on

- 🐆 **Iberian lynx monitoring with AI** — camera-trap pipelines, individual re-identification (re-ID) and connectivity monitoring between populations (LIFE LynxConnect).
- 📷 **Camera-trap data workflows** — Wildlife Insights ⇄ Wildbook integration, bulk imports, metadata curation, data standards.
- 🌡️ **Edge tech in the field** — thermal cameras for rabbit behaviour monitoring and solar-powered live-streaming cameras from lynx habitat ([**Territorio Lince**](https://territoriolince.wwf.es/)).
- 📰 **Text mining for conservation communication** — Structural Topic Modeling to measure the impact of media strategies on wolf coexistence narratives (LIFE EuroLargeCarnivores).

## 🛠️ Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**LynxAutomator**](https://github.com/antonalvarezbc/LynxAutomator) | Modular desktop app to automate camera-trap workflows: Wildlife Insights image downloader, Wildbook bulk-import generator (from folders, catalogues or WI CSVs), lynx monitoring spreadsheets, EXIF date fixer, video-frame extractor keeping capture dates. Presented at the AEET Ecoinformatics meeting. | Python · CustomTkinter · pandas · gsutil |
| [**WI-WB_Streamlit**](https://github.com/antonalvarezbc/WI-WB_Streamlit) | Web version of the Wildlife Insights → Wildbook data bridge. | Python · Streamlit |
| [**Wildbook**](https://github.com/antonalvarezbc/Wildbook) *(fork)* | Contributions to [WildMeOrg/Wildbook](https://github.com/WildMeOrg/Wildbook) as the person responsible for **Wildbook for the Iberian Lynx**: front-end tweaks and pull requests. | Java · JSP |
| [**WildbookExport**](https://github.com/antonalvarezbc/WildbookExport) *(fork)* | Desktop app to export images from a Wildbook instance. | TypeScript |

## 🧠 Computer vision for wildlife

- **CV4Ecology Summer School — Caltech (first cohort).** Developed a lynx re-ID project with *pose-invariant embeddings*: experimented with backbones, optimizers, custom loss functions, augmentations and batch strategies, and benchmarked against **HotSpotter** (SIFT-based, run in Docker). 
- **AI for Good Engineer — FruitPunch AI.** Bear face re-identification challenge: metric learning with `pytorch-metric-learning` (triplet loss, circle loss, several backbones) and responsible for evaluating **MegaDescriptor** (Swin-L) in its different configurations.
- **Wildbook for the Iberian Lynx** — early adopter (since ~2016) and coordinator of the collaboration with **Wild Me**; founder of the **GW-AI4Lynx** working group to curate the lynx catalogues (64,000+ ID-assigned images, 1,000+ individuals) across populations.
- **Wildlife Insights Trusted Tester** — wrote one of the first custom ingestion codes to migrate a camera-trap dataset to WI standards (Digikam + camtrapR). Also tested Agouti and Camelot.
- Research collaboration with the **University of Jaén** on unsupervised discarding of empty camera-trap images (*NOSpecimen*, IWANN 2023, LNCS 14135), using datasets I built and curated.

## 💼 Experience highlights

- **WWF Spain** (2017 – 2026)
  - Technical coordinator — **LIFE LynxConnect** (2021 –): threat reduction protocols and new camera-trap based monitoring techniques for Iberian lynx populations.
  - Technical coordinator — **PreveCo Operational Group** (2020–21): consortium of NGOs, farmers' organisations, administrations, companies and the Spanish agricultural insurance system; satellite-based damage detection prototype with AgriSat.
  - Innovation work for **LIFE Iberconejo**: data-flow architecture for a VUCA environment (open standards such as Darwin Core, SMART as backbone).
  - Drafted the major amendment that brought WWF Spain into **LIFE LUPILYNX**, approved by the European Commission.
  - Innovation lead in the **large carnivores group of WWF European offices**.
  - Consultant — **LIFE EuroLargeCarnivores** (2018–20) and Iberian lynx / European rabbit monitoring projects.
- **IBiCo** (2017–20) — Giant otter population monitoring in the Bojonawi reserve, Orinoco River (Colombia), with Fundación Omacha; lynx–carnivore interspecific competition.
- **SPEA / BirdLife** (2016) — Field technician in Madeira (LIFE Recover Natura, LIFE Fura-bardos).

## 📚 Selected publications & talks

- Garrote G., Pérez de Ayala R., **Álvarez-Bermúdez A.** et al. (2019). *Improving the REM method by applying a correction factor to estimate carnivore densities using data generated by conventional camera-trap designs.* **Oryx**.
- de la Rosa D., **Álvarez A.**, Pérez R., Garrote G., Rivera A.J., del Jesus M.J., Charte F. (2023). *NOSpecimen: A first approach to unsupervised discarding of empty photo trap images.* **IWANN 2023, LNCS 14135**.
- Garrote G., **Álvarez A.** et al. (2020). *Activity patterns of the Neotropical otter* Lontra longicaudis *in Orinoco River (Colombia).* **IUCN/SSC OSG Bulletin**.
- Book chapter on giant otter latrine-use patterns in *Reserva Natural Bojonawi* (Instituto Humboldt).
- Talks: *Wildbook for the Iberian lynx* (SECEM 2019) · *Camera trapping 2.0: AI applied to fauna monitoring* (2019) · *LynxAutomator* (AEET Ecoinformatics) · *Assessing the impact of communication strategies on wolf coexistence narratives: a Structural Topic Modeling approach (Pathways Europe 2024)*.
- Teaching: *AI applied to mammal monitoring, the Iberian lynx case* — Mammalnet MOOC (2021); camera-trapping & re-ID seminar — MSc Conservation Biology, UCM (2018).

## 🧰 Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![QGIS](https://img.shields.io/badge/QGIS-589632?logo=qgis&logoColor=white)


- **ML / CV:** PyTorch, metric learning, re-ID (MegaDescriptor, HotSpotter)
- **Ecology & stats:** R, density estimation (REM), activity patterns
- **Geo:** QGIS
- **Platforms:** Wildbook, Wildlife Insights, SMART, Agouti, Camelot, GBIF / Darwin Core
- **Field tech:** camera traps, thermal cameras, AXIS PTZ + OBS live-streaming, solar-powered setups
- **Management:** EU LIFE projects, multi-partner consortia, Spain–Portugal cross-border work, SCRUM fundamentals

## 🎓 Education

- **MSc in Conservation Biology** — Universidad Complutense de Madrid (2016–17), *first in my year*
- **BSc in Biology** — Universidad de Granada (2009–15)

## 🤝 Communities

SECEM (Spanish Society for Mammal Conservation and Study) · AEET Ecoinformatics working group · R-Hispano · GEO BON

---

<p align="center"><i>"Technology for conservation is not software in an office — it is making things work in the middle of the field."</i></p>