# Raman Phase Analysis

Raman spectroscopy peak analysis and phase separation for a multilayer material system.
Analysis performed on 5-point scans collected across the sample surface.

---

## Figures

### All Scans
`figures/plot_all_scans.png`
Raw spectra from each of the 5 point scans, stacked for comparison.

### Mean Spectrum with Detected Peaks
`figures/plot_mean_peaks.png`
Mean spectrum across all scans with reproducible peaks labeled (cm⁻¹).
8 peaks identified: 384, 503, 585, 645, 679, 785, 986, 1352 cm⁻¹.

### Per-Scan Peak Identification
`figures/plot_strategy1_per_scan.png`
Individual scans with detected peaks marked — shows which peaks appear in which scans.

### Lorentzian Deconvolution
`figures/plot_strategy2_deconvolution.png`
Multi-peak Lorentzian fits for overlapping peak regions (645/679 cm⁻¹ overlap and others).

### Phase Correlation Heatmap
`figures/plot_correlation_heatmap.png`
Pearson correlation matrix of peak intensities across scans.
Peaks that rise and fall together belong to the same phase.

### Phase Intensity Profiles
`figures/plot_phase_profiles.png`
Normalized intensity of each phase group across the 5 scan positions.
Three phase groups identified:
- **Phase A** — 384, 503, 585, 645, 679 cm⁻¹
- **Phase B** — 785, 986 cm⁻¹
- **Phase C** — 1352 cm⁻¹

### Single-1 vs Single-4 Contrast
`figures/plot_single1_vs_single4.png`
Direct comparison of the most phase-contrasting scans.
Single-4 is dominated by Phase C; Single-1 shows the strongest Phase A/B signal.

---

## Status
- [x] Peak detection and reproducibility filtering
- [x] Phase grouping via intensity correlation
- [x] Lorentzian deconvolution of overlapping peaks
- [ ] 2D spatial phase mapping (100-scan surface map — in progress)
- [ ] Phase-separated representative spectra (final figure)
