# Research materials
1. [Databases for cuffless BP estimation](#database)

<a id='database'></a>
## 1. Databases
| Database | number of subjects | Waveforms | Sampling rate | Comments |
|:----------:|:----------:|:-----------|---------|:----------|
|[MIMIC-III Waveform Database Matched Subset](https://physionet.org/content/mimic3wdb-matched/1.0/)|10,282 distinct<br> ICU patients|- ECG <br> - PPG <br> - ABP <br> - and others| 125 Hz| - This is a subset of the MIMIC-III Waveform Database. <br> - Subjects' corresponding clinical records can be found in MIMIC-III Clinical Database <br> - The waveforms contain unspecific/unknown filtering delay, therefore pulse transit time extracted between different waveforms may be unreliable|
|[MIMIC-IV Waveform Database](https://physionet.org/content/mimic4wdb/0.1.0/)|198 ICU subjects| - ECG <br> - PPG <br> - ABP <br> - and others| 62.5 Hz| - Currently a relative small database, more subjects will be added. <br> - No unknown delay between waveforms as found in MIMIC-III, pulse transit time is accurate|
|[UCI cuffless BP estimation](https://archive.ics.uci.edu/dataset/340/cuff+less+blood+pressure+estimation)| 12,000 subsets from unknown number of subjects| - ECG <br> - PPG <br> - ABP| 125 Hz | - this is a processed version of MIMIC-II waveform database. Each subject data may be segmented into several subsets. <br> - Similar to MIMIC-III, the waveforms have unknown delays, pulse transit time may be unreliable|
|[The University of Queensland Vital Signs Dataset](https://outbox.eait.uq.edu.au/uqdliu3/uqvitalsignsdataset/index.html)| 32 surgical subjects| - ECG <br> - PPG <br> - ABP <br> - and others | 100 Hz| - The data duration ranges from 13 minutes to 5 hours for different subjects|
| [VitalDB databank](https://vitaldb.net/dataset/)| 6,388 surgical patients | - ECG <br> - PPG <br> - ABP <br> - and others | 500 Hz | - also includes subjects' demographic and diagnosis information <br> - waveform quality may be not good, process with care|
| [Daily living BP database](https://ieee-dataport.org/documents/wearable-physiological-and-blood-pressure-measurements-during-activities-daily-living)| 5 young healthy subjects| - ECG <br> - PPG <br> - ABP <br> - Acceleration and others| 64 Hz| - this database includes several activities to induce BP changes (such as Valsalva Maneuver, walk, handgrip) <br> - around 6 hours data collected for each subject, great for long term and normal daily BP tracking purpose.|
|[Bed-based Ballistocardiography dataset](https://ieee-dataport.org/open-access/bed-based-ballistocardiography-dataset)| 40 participants | - ECG <br> - PPG <br> - BCG <br> - ABP <br> - and others | 1K Hz| - over 4.5h of data were collected <br> - BP values are not in correct scale, conversion may require|
