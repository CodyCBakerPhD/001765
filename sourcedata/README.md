# Raw data: Neuropixels recordings in anesthetized rats (saline vs. LSD) with intracranial electrical stimulation

Part of DANDI:001765 (https://dandiarchive.org/dandiset/001765).

Raw Neuropixels 1.0 electrophysiology from medial prefrontal cortex in seven anesthetized
Sprague-Dawley rats (3 LSD, 4 saline), recorded 24 hours after administration of 0.2 mg/kg
LSD or saline (vehicle), during electrical stimulation of the basolateral amygdala (BLA).

Each `sub-*/ecephys/*_ecephys.nwb` file contains the AP band (30 kHz), the LFP band (2.5 kHz)
and the NIDQ auxiliary channels that carry the stimulation triggers. BIDS/BEP032 sidecars describe
the probe (`*_probes.tsv`), channels (`*_channels.tsv`), and electrode positions in Paxinos & Watson
atlas space (`*_space-PaxinosWatson_electrodes.tsv`, `*_coordsystem.json`).

Converted from NWB with nwb2bids.
