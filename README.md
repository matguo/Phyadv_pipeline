# Phyadv_pipeline
This repository contains the supplementary materials accompanying our paper. The materials are designed to support the transparency, reproducibility, and comprehensiveness of the systematic review, including screening documentation, search strategies, and detailed analysis of physical adversarial attacks in computer vision.

## Database-Specific Search Syntaxes

The core Boolean query was adapted to each database's search interface syntax as follows.  
**Search Date**: July 3 – July 10, 2025  
**Core Boolean Query**:
> `("adversarial attack" OR "adversarial example" OR "adversarial patch") AND ("physical" OR "real world") AND ("camouflage" OR "optical" OR "light" OR "illumination" OR "laser" OR "infrared" OR "camera" OR "sensor")`

| Database | Adapted Search Query / Syntax | Field Scope | Records | Notes |
| :--- | :--- | :--- | :---: | :--- |
| **IEEE Xplore** | `Abstract:("adversarial attack" OR "adversarial example" OR "adversarial patch") AND ("physical" OR "real world") AND ("camouflage" OR "optical" OR "light" OR "illumination" OR "laser" OR "infrared" OR "camera" OR "sensor")` | Abstract | 206 | Advanced Search, field limited to Abstract |
| **Scopus** | `TITLE-ABS-KEY(("adversarial attack" OR "adversarial example" OR "adversarial patch") AND ("physical" OR "real world") AND ("camouflage" OR "optical" OR "light" OR "illumination" OR "laser" OR "infrared" OR "camera" OR "sensor"))` | Title, Abstract, Keywords | 533 | Standard field code |
| **Web of Science** | `TS=(("adversarial attack" OR "adversarial example" OR "adversarial patch") AND ("physical" OR "real world") AND ("camouflage" OR "optical" OR "light" OR "illumination" OR "laser" OR "infrared" OR "camera" OR "sensor"))` | Topic (TS) | 45 | Standard field code |
| **ACM Digital Library** | `Abstract:("adversarial attack" OR "adversarial example" OR "adversarial patch") AND Abstract:("physical" OR "real world") AND Abstract:("camouflage" OR "optical" OR "light" OR "illumination" OR "laser" OR "infrared" OR "camera" OR "sensor")` | Abstract | 58 | Advanced Search, field limited to Abstract |
| **ScienceDirect** | `("adversarial attack" OR "adversarial example" OR "adversarial patch") AND ("physical" OR "real world") AND ("camouflage" OR "optical" OR "light" OR "illumination" OR "laser" OR "infrared" OR "camera" OR "sensor")` | Title, Abstract, Keywords (via dropdown) | 152 | The syntax above denotes the query content entered. Field selection was performed via the advanced search dropdown menu (requires interface verification). |
| **Springer** | `("adversarial attack" OR "adversarial example" OR "adversarial patch") AND ("physical" OR "real world") AND ("camouflage" OR "optical" OR "light" OR "illumination" OR "laser" OR "infrared" OR "camera" OR "sensor")` | Anywhere (filtered by Computer Science & English) | 1233 | Corrected version (previously missing the third condition). If the record count (1,233) was based on the incomplete query, please re-run and update this number. |
