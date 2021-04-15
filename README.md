# genesysmod_update_2021
## Repository for collecting regional data for an update of GENeSYS-MOD in fall 2021

In this repository:
1. exogenous regional (baseyear) data for an updated run of GENeSYS-MOD in fall 2021 will be collected
2. additional national plans (in condensed form) will be also collected to maybe included in GENeSYS-MOD fall 2021 update

### Updated country level data
Please upload any data you want to be included in the fall 2021 update of GENeSYS-MOD to the corresponding region in human readable form (e.g., Excel/csv files). Especially existing generation capacities and cross-border transmission interconnections in the 2015 and 2020 are of interest. Final energy demands and sectoral demands for those years are also helpful for further model calibration/validation.

**Note:** Data from 2025 onwards is endogenously calculated by GENeSYS-MOD and will not be considered (exception: national plans (e.g., phase-out plans) will partly considered)

### Additional national plans
Please upload any national plans/targets you deem important for the updated run of GENeSYS-MOD in fall 2021 either as text-document or via changing the corresponding *national_plans.md* file in the regional subfolders. Clearly state the targets you want to be included. E.g. a target like
  - Germany plans to phaseout its nuclear generation capacities by 2021

can be easily included by GENeSYS-MOD.

**Note:** Data conflicting with the openENTRANCE pathways (i.e., net-zero emissions in 2040/2050) will not be considered. E.g.:
  - Country X plans to have 10 GW of coal fired PP in 2050
  - Country Y plans to have at least 30% thermal generation by natural gas in 2050
  
might be conflicting with net-zero emission targets.
