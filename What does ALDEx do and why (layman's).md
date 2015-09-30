#What does ALDEx do and why (layman's)
- Add prior to zeros
    - For conversion to log space
    - How likely you think a zero is a real zero
- Monte-Carlo Dirichlet instances
    - Converts read counts to proportions while maintaining scaling (seq depth)
    - Estimates probabilities for each feature (distribution of values, not single estimate)
    - Model technical replication - i.e. what is my read count distribution if I sequenced the sample again
- CLR transformation
    - Log space with linear distance between ratios of abundances (no longer counts)
    - Reduces dependency between features (OTU, gene, function)
    - Subcompositional coherence (same answer when parts are removed)
    - Accounts for differences in sequencing depth (normalization)
- Test significant differences between groups
    - Standard statistical approaches
- Multiple test correction
    - Duh


Just CLR - too much background noise in low counts

Just Dir - data re non-linear, scaling is difficult (normalizing)
