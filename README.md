# Better Energy Storage Redux

Better Energy Storage Redux is a Satisfactory 1.2 / SML 3.12 content-only continuation of [Better Energy Storage](https://ficsit.app/mod/RqqMnXChdiBeB), originally created by [JanEricS](https://github.com/JanEricStorms).

The Redux rebuild is maintained by [KSwapBytes](https://github.com/KSwapBytes). It uses vanilla Power Storage behavior and vanilla-derived assets for stable save/load behavior and compatibility.

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

## Credits

- Original Better Energy Storage concept and mod: [JanEricS](https://github.com/JanEricStorms)
- Satisfactory 1.2 Redux rebuild and maintenance: [KSwapBytes](https://github.com/KSwapBytes)
- Satisfactory and its original assets: Coffee Stain Studios

See [CREDITS.md](CREDITS.md) for full attribution.

## License

Better Energy Storage Redux is distributed under the [GNU General Public License v3.0](LICENSE), matching the original project's license.
