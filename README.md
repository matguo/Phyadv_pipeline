# Phyadv_pipeline
This repository contains the supplementary materials accompanying our paper. The materials are designed to support the transparency, reproducibility, and comprehensiveness of the systematic review, including screening documentation, search strategies, and detailed analysis of physical adversarial attacks in computer vision.

## Database-Specific Search Syntaxes

The core Boolean query was adapted to each database's search interface syntax as follows:

| Database | Adapted Search Query / Syntax | Field Scope |
| :--- | :--- | :--- |
| **IEEE Xplore** | `(("Abstract":"adversarial attack" OR "Abstract":"adversarial example" OR "Abstract":"adversarial patch") AND ("Abstract":"physical" OR "Abstract":"real world") AND ("Abstract":"camouflage" OR "Abstract":"optical" OR "Abstract":"light" OR "Abstract":"illumination" OR "Abstract":"laser" OR "Abstract":"infrared" OR "Abstract":"camera" OR "Abstract":"sensor"))` | Abstract / Document Title |
| **Scopus** | `TITLE-ABS-KEY(("adversarial attack" OR "adversarial example" OR "adversarial patch") AND ("physical" OR "real world") AND ("camouflage" OR "optical" OR "light" OR "illumination" OR "laser" OR "infrared" OR "camera" OR "sensor"))` | Title, Abstract, Keywords |
| **Web of Science** | `TS=(("adversarial attack" OR "adversarial example" OR "adversarial patch") AND ("physical" OR "real world") AND ("camouflage" OR "optical" OR "light" OR "illumination" OR "laser" OR "infrared" OR "camera" OR "sensor"))` | Topic (TS) |
| **ACM Digital Library** | `Abstract:(+"adversarial attack" +"physical" +"camera") ...` (Standard Advanced Search Interface) | Abstract / Title |
| **ScienceDirect** | `Title, abstract, keywords: ("adversarial attack" OR "adversarial patch") AND ("physical" OR "real world") AND ("camouflage" OR "optical" OR "light")` | Title, Abstract, Keywords |
| **Springer** | `("adversarial attack" OR "adversarial example") AND ("physical" OR "real world")` (Advanced Search filtered by Computer Science & English) | Anywhere / Title |
