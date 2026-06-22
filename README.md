# Better Energy Storage Redux

Better Energy Storage Redux is a Satisfactory 1.2 / SML 3.12 content-only rebuild of the original Better Energy Storage concept.

The mod uses vanilla Power Storage behavior and vanilla-derived assets for stable save/load behavior and compatibility.

## Tiers

| Building | Unlock Tier | Storage Capacity | Authored Max Charge Rate |
| --- | ---: | ---: | ---: |
| Power Storage Mk1 | Tier 2 | 250 MWh | 250 MW |
| Power Storage Mk2 | Tier 3 | 500 MWh | 500 MW |
| Power Storage Mk3 | Tier 4 | 1,000 MWh | 1,000 MW |
| Power Storage Mk4 | Tier 5 | 5,000 MWh | 5,000 MW |
| Power Storage Mk5 | Tier 7 | 10,000 MWh | 10,000 MW |
| Power Storage Mk6 | Tier 8 | 20,000 MWh | 20,000 MW |

## Known Limitation

Mixed battery tiers on the same power grid may not preserve individual authored charge-rate caps because Satisfactory handles batteries as a grid-level storage group.

## Notes

This is a faithful content-only port. Native hooks into `UFGPowerCircuitGroup::TickBatteries` are intentionally not implemented in this version.
