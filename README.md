# Neuropixels recordings in anesthetized rats (saline vs. LSD) with intracranial electrical stimulation

DANDI Archive: [DANDI:001765](https://dandiarchive.org/dandiset/001765)

Neuropixels 1.0 recordings from medial prefrontal cortex in seven anesthetized
Sprague-Dawley rats (3 LSD, 4 saline), 24 hours after administration of 0.2 mg/kg
LSD or saline (vehicle). During recording, electrical stimulation was delivered
to the basolateral amygdala (BLA).

## Layout

This is a BIDS *study* dataset:

- `sourcedata/` — raw BIDS dataset. Raw electrophysiology (AP 30 kHz, LFP 2.5 kHz)
  and NIDQ auxiliary channels with stimulation triggers, per subject, as NWB, with
  BIDS/BEP032 sidecars (probes, channels, electrodes, coordinate system).
- `derivatives/kilosort4-4.1.3/` — Kilosort4 spike sorting (subject NP06).
- `derivatives/bombcell-0.72/` — bombcell unit quality metrics (subject NP06).
- `dandiset.yaml` — DANDI Archive metadata (ignored by the BIDS validator via `.bidsignore`).

## Coordinates

Electrode coordinates use the Paxinos & Watson atlas in standard stereotaxic
convention (mm; AP and ML relative to bregma, DV relative to brain surface):
x = anterior-posterior (anterior positive), y = medial-lateral (right positive),
z = dorsal-ventral (dorsal positive, ventral negative).
Probe insertion: AP +3.4 mm, ML 0.75 mm (left hemisphere), DV -6.0 mm (probe tip),
perpendicular (0 deg). BLA stimulation site: AP -1.7, ML 4.5, DV -7.5 mm.

## Authors

- Lucas Dwiel (ORCID 0000-0002-9440-7842)
- Wilder Doucette

## License

CC-BY-4.0
