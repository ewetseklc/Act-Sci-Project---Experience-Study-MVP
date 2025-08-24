<<<<<<< HEAD
# Experience Study MVP (Lapse)
Run the notebook to compute crude and credibility-blended lapse rates and output CSVs/PNGs.
**Methods:** Crude lapse = lapses/exposure by duration; credibility uses Z = n/(n + k) with k=5000 and overall mean as complement.
**Controls:** Fixed RNG seed (42); notebook writes only to /results; synthetic data clearly labeled; steps are reproducible end-to-end.

## Outputs
- results/lapse_rates_by_duration.csv — crude lapse by duration
- results/lapse_rates_by_duration_cred.csv — credibility-blended lapse by duration (k=5000)
- results/lapse_rates_by_duration_ci.csv — crude lapse with 95% CI bounds
- results/lapse_curve.png — crude vs credibility curve
- results/lapse_curve_with_ci.png — crude vs credibility with 95% CI ribbon
- results/lapse_curve_standard.png — Standard risk class curve
- results/lapse_curve_preferred.png — Preferred risk class curve
- results/lapse_onepager.png — clean summary chart with key stats

=======
# Act-Sci-Project---Experience-Study-MVP
>>>>>>> 5d046f5a094dde118569dafc69c30eac2beb80c2
