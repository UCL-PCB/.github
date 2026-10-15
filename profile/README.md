# Physical Characterisation of Buildings (PCB)

Code and tools from the [Physical Characterisation of Buildings Group](https://www.ucl.ac.uk/bartlett/environment-energy-resources/energy/research-ucl-energy-institute/physical-characterisation-buildings) at the UCL Energy Institute.

The group studies how buildings actually perform in use. We measure (hygro)thermal performance and ventilation in real buildings, then apply physics and statistics to the data. Our work covers:

- whole-house thermal performance of occupied homes
- decarbonising heating and cooling
- the thermal performance of building elements
- ventilation and indoor environmental quality
- running heating more flexibly

## Repositories

| Repo | What it is |
|---|---|
| `python-wall` | RC-network heat-transfer models and fitting routines (Minuit, emcee) for estimating the in-situ thermal performance of walls. Mirrored from Bitbucket `ei_bayes_group/python-wall`. |
| `pcb-models` | Heat transfer coefficient (HTC) models for monitored dwellings: steady-state fits, data filtering and energy prediction, with dynamic models run through `python-wall`. |
| `serl-cohort` | Brings the SERL Observatory smart-meter, survey, EPC and climate data into the `building-energy-analysis` framework. Work in progress. |
| `ghg-cohort` | Brings Green Homes Grant monitoring data (in-home temperature and humidity loggers, retrofit dates) into the same framework, on top of `serl-cohort`. Work in progress. |
| `pcb-equipment` | Loan system for the group's field equipment, running on UCL Microsoft 365 (SharePoint, Power Automate, Power Apps). Holds the design docs and runbooks. |
| `pcb-context` | Shared context and notes for the group's Claude Code sessions. |

Most repos are private to group members for now.
