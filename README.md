# ADR-Naomi metadata

These tables define common metadata for ADR and Naomi. It's not clear where they should best live.

### meta_indicators

This table defines all of the indicators for inputs and outputs.

The fields _accuracy_, _scale_, _prefix_, and _suffix_ define how numerical data are displayed following the [`scales`](https://scales.r-lib.org/) R package.


## TODO:

- [ ] Where should this live.
- [ ] `art_current` versus `art_num_attend` indicator.
- [ ] Language localisation.
- [ ] Confirm if okay to drop integer `*_id` columns with Avenir.
- [ ] Option for country / indicator / level specific numerical displays?
