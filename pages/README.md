## About

The Disrupted Nighttime Sleep in Pediatric Narcolepsy (DNSPN) study, conducted from September 2019 – May 2023 at Boston Children’s Hospital under principal investigator Dr. Kiran Maski, MD, MPH, was supported by National Institute of Neurological Disorders and Stroke (NINDS)  grant K23NS104267.  This study investigated sleep-dependent memory consolidation impairments in pediatric narcolepsy type 1 (NT1). NT1 is characterized by near-total orexin neuron loss leading to daytime sleepiness, cataplexy, and disrupted nighttime sleep (DNS), occurring in 30–90% of adults and at least 50% of children/adolescents. 

The study enrolled 28 pediatric NT1 patients diagnosed clinically and 27 healthy controls (HC), ages 8–21 years, to examine how N2 sleep fragmentation and spindle alterations relate to cognitive deficits. Participants were recruited through community postings and hospital registries. Inclusion criteria for NT1 involved an Epworth Sleepiness Score >10 and scheduled overnight PSG and Multiple Sleep Latency Test (MSLT). Patients had to be drug naïve or weaned off stimulants/wake-promoting medications for five half-lives but could remain on SSRIs/SNRIs or tricyclic antidepressants for cataplexy control. Controls were free of neurodevelopmental or neurological disorders and medications affecting sleep, wakefulness, or cognition.

The primary outcomes were measures of sleep-dependent declarative memory consolidation assessed via a spatial declarative memory task before and after in-lab nocturnal polysomnography (PSG). Secondary outcomes focused on associations between sleep-dependent memory consolidation and sleep fragmentation measures, including N2 bout duration, sleep spindle characteristics, and percentage of N1 sleep.

## Methods
All participants had an in-lab overnight PSG at the Pediatric Sleep Laboratory at Boston Children’s Hospital.  Prior to their PSG, participants and their parents were sent surveys and were mailed an Actiwatch to wear for 7-10 days prior to the study to measure sleep wake activity.  Remote neurocognitive testing was done via video conferencing to assess baseline verbal and nonverbal intelligence quotient scores either 1 week before or after the overnight sleep study. 

### PSG clinic visit/data collection
Additional data collected on the night of the full lab PSG at Boston Children’s Pediatric Sleep Laboratory included:
- 3-minute psychomotor vigilance task (PVT).
- A spatial declarative memory task before habitual bedtime.
- Underwent repeat PVT in the morning, memory task retest 
- Subgroup completed alternate declarative memory task in morning to assess circadian influences.
- Urine drug screening to confirm drug-free status.

### Polysomnography (PSG) collection
- Equipment: XLTEK® PSG system with Natus SleepWorks software (Natus Medical Inc.).
- Montage included nine EEG leads (F3, F4, T3, T4, C3, Cz, C4, O1, O2), bilateral EOG, chin EMG, ECG, airflow sensors, respiratory belts, pulse oximetry, and leg EMG.
- Signals sampled at 200 Hz.
- PSG was conducted in-lab with registered sleep technicians following American Academy of Sleep Medicine (AASM) 2007 scoring guidelines.
- Lights-out/on times recorded by technician and annotated.

### Polysomnography scoring
- Manual scoring by certified technologists blinded to other data.
- Sleep staged per AASM 2007 pediatric criteria in 30-second epochs (Wake=0, N1=1, N2=2, N3=3–4, REM=5).
- Respiratory events scored as follows:
  - Obstructive apneas: ≥90% airflow reduction for duration of ≥2 missed breaths; associated with continued/increased inspiratory effort.
  - Central apneas: absence of thoracic and abdominal effort.
  - Hypopneas: ≥50% airflow reduction lasting ≥2 missed breaths, with ≥3% desaturation or arousal/awakening.
  - Mixed apneas: initial central apnea followed by obstructive component; duration ≥2 missed breaths.
- Arousal indices calculated as arousals per hour of sleep.
- Sleep quality assessed per channel; artifacts and study quality documented.
- Spindle detection performed automatically on artifact-free N2 sleep epochs over central electrodes using wavelet-based algorithm for 12–15 Hz band.

### Actigraphy collection
- Participants wore Actiwatch-L wrist actigraph for 7–10 days prior to study night to verify habitual sleep duration ≥7 hours.
- Movement data recorded and scored via validated algorithms.
- Sleep diaries complemented actigraphy to assist sleep period determination.

### Actigraphy scoring
- Sleep periods marked manually using event markers, sleep diaries, light levels, and activity counts.
- Automatic classification of sleep/wake for 30-second epochs using Actiware-Sleep software.
- Summary metrics generated included total sleep time, sleep efficiency, awakenings count and duration.
- Minimum 7 days with valid data required.

## Data overview

### Covariate/phenotype datasets (CSV)
- Demographic and clinical data include age, sex, race, SSRI use.
- PSG measures: total sleep time, sleep efficiency, latencies, percentages of NREM stages (N1, N2, N3) and REM, arousal index, number of wakings.
- MSLT outcomes: number of naps, mean sleep latency, number of SOREMPs.
- Unique subject identifiers enable linkage across data types.

The harmonized dataset contains many of the most frequently used demographic and sleep variables.  These variables were curated by the NSRR team.  Key variables include:
- **nsrr_ahi_hp3r_aasm07** - Apnea-Hypopnea Index: (All apneas + hypopneas with >=50% nasal cannula [or alternative sensor] reduction and >= 3% oxygen desaturation or with arousal) / hour of sleep
- **nsrr_phrnumar_f1** – Arousal Index: Number of arousals per hour of sleep from polysomnography
- **nsrr_pctdursp_s1** – percentage of total sleep duration (i.e., total sleep time, TST) in stage 1 from polysomnography
- **nsrr_pctdursp_s2** - percentage of total sleep duration (i.e., total sleep time, TST) in stage 2 from polysomnography
- **nsrr_pctdursp_s3** - percentage of total sleep duration (i.e., total sleep time, TST) in stage 3/4 from polysomnography
- **nsrr_pctdursp_sr** – percentage of total sleep duration (i.e., total sleep time, TST) in REM from polysomnography
- **nsrr_tib_f1** – Total In-bed Period: the interval between lights off/in-bed time and lights on/out-bed time from polysomnography
- **nsrr_tst_f1** - Total Sleep Duration: the interval between sleep onset and sleep offset while the participant is asleep from polysomnography
- **nsrr_ttldursp_sr** – Total duration of REM sleep from type 1 polysomnography
- **nsrr_ttleffsp_f1** – Sleep Efficiency: the ratio of total sleep duration (i.e., total sleep time) to in-bed period (i.e., time in bed) from polysomnography
- **nsrr_ttllatsp_f1** – Sleep Latency: the interval between lights-out/in-bed time and sleep onset from polysomnography
- **nsrr_waso_f1** – Wake After Sleep Onset: the total duration being awake between sleep onset and lights-on/out-bed time from polysomnography
- **nsrr_age** – subject age
- **nsrr_race** – subject race
- **nsrr_sex** – subject sex



### PSG signal and annotation files (EDF/XML)
- Raw PSG data recorded with XLTEK PSG system; signals sampled at 200 Hz.
- Data available in EDF format.
- Annotations scored manually per AASM 2007 pediatric criteria.
- Scored events include sleep stages, apneas, hypopneas, arousals.
- Lights-out/on annotated by technician.
- Events use standardized tags; "unsure" tags not specified.
- Detailed spindle and slow oscillation-spindle coupling characteristics derived from central EEG leads.

### Actigraphy signal and annotation files
Not specified in the provided sources.

### Actigraphy and polysomnography overlap
- Actigraphy collected for 7–10 days prior to polysomnography, including the PSG night, enabling cross-reference of habitual sleep patterns.
- Detailed alignment methods not specified.

## Access and usage restrictions
The dataset is available for non-commercial use only.

## Citation and acknowledgements
When using this dataset, please cite the following:

> [Maski K, Heckler G, Worhach J, Mylonas D, Wang G, Szilagyi K, Zhang B, Diniz Behn C, Scammell TE, Stickgold R. Impaired Sleep-Dependent Memory Consolidation in Pediatric Narcolepsy Type 1. Sleep. 2024 Oct 18:zsae238. doi: 10.1093/sleep/zsae238. Epub ahead of print. PMID: 39420719.](https://pubmed.ncbi.nlm.nih.gov/39420719/)

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

Please include the following text in the Acknowledgements:

> The National Sleep Research Resource was supported by the National Heart, Lung, and Blood Institute (R24 HL114473, 75N92019R002).

## References
- DNSPN NSRR GitHub Data Dictionary: https://github.com/nsrr/dnspn-data-dictionary
- DNSPN NSRR GitHub Documentation: https://github.com/nsrr/dnspn-documentation
- Primary publication: [Maski et al., 2024; DOI: 10.1093/sleep/zsae238](https://pubmed.ncbi.nlm.nih.gov/39420719/)
- NSRR resource citation: [Zhang et al., 2018; DOI: 10.1093/jamia/ocy064](https://pubmed.ncbi.nlm.nih.gov/29860441/)
- Additional documentation and data access contact: Boston Children's Hospital Pediatric Sleep Center.



